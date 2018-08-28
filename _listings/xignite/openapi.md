swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite VWAP
  description: provides-delayed-and-historical-volumeweightedaverage-price-vwap-information-
  version: 1.0.0
host: www.xignite.com
basePath: xVWAP.json/XigniteVWAP
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetRateFamilyTable:
    get:
      summary: Get Rate Family Table
      description: Returns a rate table for a rate family.
      operationId: postGetratefamilytable
      x-api-path-slug: getratefamilytable-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Rate
      - Family
      - Table
  /GetRateFamily:
    get:
      summary: Get Rate Family
      description: Returns a collection of related rate as of a specific date
      operationId: postGetratefamily
      x-api-path-slug: getratefamily-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Rate
      - Family
  /GetLatestRateFamily:
    get:
      summary: Get Latest Rate Family
      description: Returns latest values for a rate family.
      operationId: postGetlatestratefamily
      x-api-path-slug: getlatestratefamily-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Rate
      - Family
  /GetHistoricalRateFamily:
    get:
      summary: Get Historical Rate Family
      description: Returns a rate family and for a range of dates.
      operationId: postGethistoricalratefamily
      x-api-path-slug: gethistoricalratefamily-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Rate
      - Family
  /GetSwaptionFamily:
    get:
      summary: Get Swaption Family
      description: Returns a Swaption rate Family
      operationId: postGetswaptionfamily
      x-api-path-slug: getswaptionfamily-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Swaption
      - Family
  /GetHistoricalSwaptionFamily:
    get:
      summary: Get Historical Swaption Family
      description: Returns a Swaption rate Family
      operationId: postGethistoricalswaptionfamily
      x-api-path-slug: gethistoricalswaptionfamily-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Swaption
      - Family
  /GetSwapRateFamily:
    get:
      summary: Get Swap Rate Family
      description: Returns a Swap rate Family
      operationId: postGetswapratefamily
      x-api-path-slug: getswapratefamily-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Swap
      - Rate
      - Family
  /GetSwapRateFamilyExtended:
    get:
      summary: Get Swap Rate Family Extended
      description: Returns latest Swap rate family
      operationId: postGetswapratefamilyextended
      x-api-path-slug: getswapratefamilyextended-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Swap
      - Rate
      - Family
      - Extended
  /GetTreasuryRateFamily:
    get:
      summary: Get Treasury Rate Family
      description: Returns a real-time Treasury rate family.
      operationId: postGettreasuryratefamily
      x-api-path-slug: gettreasuryratefamily-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Treasury
      - Rate
      - Family
  /ListRatesByRateFamily:
    get:
      summary: List Rates By Rate Family
      description: List supported interest rates from a RateFamilyType.
      operationId: postListratesbyratefamily
      x-api-path-slug: listratesbyratefamily-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - List
      - Rates
      - Rate
      - Family