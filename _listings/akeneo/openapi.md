swagger: "2.0"
x-collection-name: Akeneo
x-complete: 1
info:
  title: Official Akeneo PIM API
  description: the-akeneo-api-brought-to-youfind-out-how-this-postman-collection-works-by-visiting-httpapi-akeneo-com
  version: 1.0.0
host: example.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/v1/families:
    get:
      summary: families
      description: Families.
      operationId: RestV1FamiliesGet
      x-api-path-slug: restv1families-get
      responses:
        200:
          description: OK
      tags:
      - Families
    patch:
      summary: families
      description: Families.
      operationId: RestV1FamiliesPatch
      x-api-path-slug: restv1families-patch
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Families
    post:
      summary: family
      description: Assuming that there is no "new_family" already existing
      operationId: RestV1FamiliesPost
      x-api-path-slug: restv1families-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Family
  /rest/v1/measure-families:
    get:
      summary: measure families (2.x only)
      description: Measure families (2.x only).
      operationId: RestV1MeasureFamiliesGet
      x-api-path-slug: restv1measurefamilies-get
      responses:
        200:
          description: OK
      tags:
      - Measure
      - Families
      - (2
      - X
      - Only)
  /rest/v1/families/camcorders:
    get:
      summary: family
      description: Assuming that the given code is the code of an existing family
      operationId: RestV1FamiliesCamcordersGet
      x-api-path-slug: restv1familiescamcorders-get
      responses:
        200:
          description: OK
      tags:
      - Family
    patch:
      summary: family
      description: Family.
      operationId: RestV1FamiliesCamcordersPatch
      x-api-path-slug: restv1familiescamcorders-patch
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Family
  /rest/v1/families/clothing/variants/clothing_colorsize:
    get:
      summary: family variant (2.x only)
      description: Assuming that the given codes are respectively the code of an existing
        family and an existing family variant
      operationId: RestV1FamiliesClothingVariantsClothingColorsizeGet
      x-api-path-slug: restv1familiesclothingvariantsclothing-colorsize-get
      responses:
        200:
          description: OK
      tags:
      - Family
      - Variant
      - (2
      - X
      - Only)
    patch:
      summary: family variant (2.x only)
      description: Assuming that the given codes are respectively the code of an existing
        family and an existing family variant
      operationId: RestV1FamiliesClothingVariantsClothingColorsizePatch
      x-api-path-slug: restv1familiesclothingvariantsclothing-colorsize-patch
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Family
      - Variant
      - (2
      - X
      - Only)
  /rest/v1/families/clothing/variants:
    get:
      summary: family variants (2.x only)
      description: Family variants (2.x only).
      operationId: RestV1FamiliesClothingVariantsGet
      x-api-path-slug: restv1familiesclothingvariants-get
      responses:
        200:
          description: OK
      tags:
      - Family
      - Variants
      - (2
      - X
      - Only)
    post:
      summary: family variant (2.x only)
      description: Assuming that the given code is the code of an existing family
      operationId: RestV1FamiliesClothingVariantsPost
      x-api-path-slug: restv1familiesclothingvariants-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Family
      - Variant
      - (2
      - X
      - Only)
    patch:
      summary: family variants (2.x only)
      description: Assuming that the given code is the code of an existing family
      operationId: RestV1FamiliesClothingVariantsPatch
      x-api-path-slug: restv1familiesclothingvariants-patch
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Family
      - Variants
      - (2
      - X
      - Only)
  /rest/v1/measure-families/area:
    get:
      summary: measure family (2.x only)
      description: Assuming that the given code is the code of an existing measure
        family
      operationId: RestV1MeasureFamiliesAreaGet
      x-api-path-slug: restv1measurefamiliesarea-get
      responses:
        200:
          description: OK
      tags:
      - Measure
      - Family
      - (2
      - X
      - Only)