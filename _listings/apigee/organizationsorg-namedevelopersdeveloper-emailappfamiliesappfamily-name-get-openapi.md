---
swagger: "2.0"
x-collection-name: Apigee
x-complete: 0
info:
  title: Apigee Edge Get Organizations Name Developers Developer Email Appfamilies
    Appfamily Name
  description: Gets a list of apps in an appfamily.
  version: 1.0.0
host: api.enterprise.apigee.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/{org_name}/companies/{company_name}/appfamilies:
    get:
      summary: Get Organizations Name Companies Company Name Appfamilies
      description: An expanded list of all app families in an organization, listing
        Apps in the collection.
      operationId: getOrganizationsOrgNameCompaniesCompanyNameAppfamilies
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappfamilies-get
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - Families
    post:
      summary: Post Organizations Name Companies Company Name Appfamilies
      description: Creates an app family.
      operationId: postOrganizationsOrgNameCompaniesCompanyNameAppfamilies
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappfamilies-post
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
      - in: query
        name: Content-Type
        description: Specify the content type
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - Families
  /organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}:
    get:
      summary: Get Organizations Name Companies Company Name Appfamilies Appfamily
        Name
      description: Gets a list of apps in an appfamily.
      operationId: getOrganizationsOrgNameCompaniesCompanyNameAppfamiliesAppfamilyName
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-get
      parameters:
      - in: path
        name: appfamily_name
        description: Mention app family name
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - Families
      - Applications
      - family
    post:
      summary: Post Organizations Name Companies Company Name Appfamilies Appfamily
        Name
      description: Updates an existing app family.
      operationId: postOrganizationsOrgNameCompaniesCompanyNameAppfamiliesAppfamilyName
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-post
      parameters:
      - in: path
        name: appfamily_name
        description: Mention app family name
      - in: path
        name: company_name
        description: Mention the company name
      - in: query
        name: Content-Type
        description: Specify the Content Type
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - Families
      - Applications
      - family
    delete:
      summary: Delete Organizations Name Companies Company Name Appfamilies Appfamily
        Name
      description: Deletes an App Family and all Apps it contains.
      operationId: deleteOrganizationsOrgNameCompaniesCompanyNameAppfamiliesAppfamilyName
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-delete
      parameters:
      - in: path
        name: appfamily_name
        description: Mention app family name
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - Families
      - Applications
      - family
  /organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}/apps/{app_name}:
    delete:
      summary: Delete Organizations Name Companies Company Name Appfamilies Appfamily
        Name Apps App Name
      description: Removes an App from an App Family.
      operationId: deleteOrganizationsOrgNameCompaniesCompanyNameAppfamiliesAppfamilyNameAppsAppName
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappfamiliesappfamily-nameappsapp-name-delete
      parameters:
      - in: path
        name: appfamily_name
        description: Mention app family name
      - in: path
        name: app_name
        description: Mention app name
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - Families
      - Applications
      - family
      - Applications
      - ""
  /organizations/{org_name}/developers/{developer_email}/appfamilies:
    get:
      summary: Get Organizations Name Developers Developer Email Appfamilies
      description: An expanded list of all app families in an organization, listing
        Apps in the collection
      operationId: getOrganizationsOrgNameDevelopersDeveloperEmailAppfamilies
      x-api-path-slug: organizationsorg-namedevelopersdeveloper-emailappfamilies-get
      parameters:
      - in: path
        name: developer_email
        description: Mention the developer email
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Developers
      - Developer
      - Email
      - Applications
      - Families
    post:
      summary: Post Organizations Name Developers Developer Email Appfamilies
      description: Creates an app family for developers.
      operationId: postOrganizationsOrgNameDevelopersDeveloperEmailAppfamilies
      x-api-path-slug: organizationsorg-namedevelopersdeveloper-emailappfamilies-post
      parameters:
      - in: query
        name: Content-Type
        description: Specify the content type
      - in: path
        name: developer_email
        description: Mention the developer email
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Developers
      - Developer
      - Email
      - Applications
      - Families
  /organizations/{org_name}/developers/{developer_email}/appfamilies/{appfamily_name}:
    get:
      summary: Get Organizations Name Developers Developer Email Appfamilies Appfamily
        Name
      description: Gets a list of apps in an appfamily.
      operationId: getOrganizationsOrgNameDevelopersDeveloperEmailAppfamiliesAppfamilyName
      x-api-path-slug: organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-get
      parameters:
      - in: path
        name: appfamily_name
        description: Mention app family name
      - in: path
        name: developer_email
        description: Mention the developer email
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Developers
      - Developer
      - Email
      - Applications
      - Families
      - Applications
      - family
    post:
      summary: Post Organizations Name Developers Developer Email Appfamilies Appfamily
        Name
      description: Updates an existing app family.
      operationId: postOrganizationsOrgNameDevelopersDeveloperEmailAppfamiliesAppfamilyName
      x-api-path-slug: organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-post
      parameters:
      - in: path
        name: appfamily_name
        description: Mention app family name
      - in: query
        name: Content-Type
        description: Specify the Content Type
      - in: path
        name: developer_email
        description: Mention the developer email
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Developers
      - Developer
      - Email
      - Applications
      - Families
      - Applications
      - family
    delete:
      summary: Delete Organizations Name Developers Developer Email Appfamilies Appfamily
        Name
      description: Deletes an App Family and all Apps it contains.
      operationId: deleteOrganizationsOrgNameDevelopersDeveloperEmailAppfamiliesAppfamilyName
      x-api-path-slug: organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-delete
      parameters:
      - in: path
        name: appfamily_name
        description: Mention app family name
      - in: path
        name: developer_email
        description: Mention the developer email
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Developers
      - Developer
      - Email
      - Applications
      - Families
      - Applications
      - family
  /organizations/{org_name}/developers/{developer_email}/appfamilies/{appfamily_name}/apps/{app_name}:
    delete:
      summary: Delete Organizations Name Developers Developer Email Appfamilies Appfamily
        Name Apps App Name
      description: Removes an App from an App Family.
      operationId: deleteOrganizationsOrgNameDevelopersDeveloperEmailAppfamiliesAppfamilyNameAppsAppName
      x-api-path-slug: organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-nameappsapp-name-delete
      parameters:
      - in: path
        name: appfamily_name
        description: Mention app family name
      - in: path
        name: app_name
        description: Mention app name
      - in: path
        name: developer_email
        description: Mention the developer email
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Developers
      - Developer
      - Email
      - Applications
      - Families
      - Applications
      - family
      - Applications
      - ""
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---