---
name: Apigee
x-slug: apigee
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Families
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Companies Company Name Appfamilies
  x-api-slug: apigee-edge
  description: An expanded list of all app families in an organization, listing Apps
    in the collection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies
  tags: Organizations,Companies,Companies,Applications,Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamilies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamilies-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Appfamilies
  x-api-slug: apigee-edge
  description: Creates an app family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies
  tags: Organizations,Companies,Companies,Applications,Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamilies-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamilies-post-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Appfamilies Appfamily
    Name
  x-api-slug: apigee-edge
  description: Gets a list of apps in an appfamily.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Appfamilies Appfamily
    Name
  x-api-slug: apigee-edge
  description: Updates an existing app family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Appfamilies Appfamily
    Name
  x-api-slug: apigee-edge
  description: Deletes an App Family and all Apps it contains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-delete-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Appfamilies Appfamily
    Name Apps App Name
  x-api-slug: apigee-edge
  description: Removes an App from an App Family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}/apps/{app_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-nameappsapp-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-nameappsapp-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Appfamilies
  x-api-slug: apigee-edge
  description: An expanded list of all app families in an organization, listing Apps
    in the collection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies
  tags: Organizations,Developers,Developer,Email,Applications,Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamilies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamilies-get-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Appfamilies
  x-api-slug: apigee-edge
  description: Creates an app family for developers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies
  tags: Organizations,Developers,Developer,Email,Applications,Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamilies-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamilies-post-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Appfamilies
    Appfamily Name
  x-api-slug: apigee-edge
  description: Gets a list of apps in an appfamily.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies/{appfamily_name}
  tags: Organizations,Developers,Developer,Email,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-get-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Appfamilies
    Appfamily Name
  x-api-slug: apigee-edge
  description: Updates an existing app family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies/{appfamily_name}
  tags: Organizations,Developers,Developer,Email,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Developers Developer Email Appfamilies
    Appfamily Name
  x-api-slug: apigee-edge
  description: Deletes an App Family and all Apps it contains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies/{appfamily_name}
  tags: Organizations,Developers,Developer,Email,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-delete-openapi.md
- name: Apigee Edge Delete Organizations Name Developers Developer Email Appfamilies
    Appfamily Name Apps App Name
  x-api-slug: apigee-edge
  description: Removes an App from an App Family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies/{appfamily_name}/apps/{app_name}
  tags: Organizations,Developers,Developer,Email,Applications,Families,Applications,family,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-nameappsapp-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-nameappsapp-name-delete-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: Families
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/apigee/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---