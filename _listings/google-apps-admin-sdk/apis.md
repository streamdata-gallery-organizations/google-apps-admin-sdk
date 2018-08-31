---
name: Google Apps Admin SDK
x-slug: google-apps-admin-sdk
description: Administer domain resources, create reports, and manage subscriptions.
  Use the Directory API to create and manage users and groups for a domain, along
  with their aliases. Programmatically access the functionality found at the Admin
  console Organization and users tab. Use the Reports API to gain insights on content
  management with Google Drive activity reports. Audit administrator actions. Generate
  customer and user usage reports.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Apps Admin SDK
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/apis.md
specificationVersion: "0.14"
apis:
- name: Google Apps Admin SDK Merged API - Get Activities
  x-api-slug: activityusersuserkeyapplicationsapplicationname-get
  description: Retrieves a list of activities for a specific customer and application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/activityusersuserkeyapplicationsapplicationname-get-openapi.md
- name: Google Apps Admin SDK Merged API - Change Activity
  x-api-slug: activityusersuserkeyapplicationsapplicationnamewatch-post
  description: Push changes to activities
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/activityusersuserkeyapplicationsapplicationnamewatch-post-openapi.md
- name: Google Apps Admin SDK Merged API - Stop Watching Resource
  x-api-slug: adminreports-v1channelsstop-post
  description: Stop watching resources through this channel
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/adminreports-v1channelsstop-post-openapi.md
- name: Google Apps Admin SDK Merged API - Get Report by Date
  x-api-slug: usagedatesdate-get
  description: Retrieves a report which is a collection of properties / statistics
    for a specific customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/usagedatesdate-get-openapi.md
- name: Google Apps Admin SDK Merged API - Get User Report by Date
  x-api-slug: usageusersuserkeydatesdate-get
  description: Retrieves a report which is a collection of properties / statistics
    for a set of users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/usageusersuserkeydatesdate-get-openapi.md
- name: Google Apps Admin SDK Merged API - Archive Mail
  x-api-slug: groupidarchive-post
  description: Inserts a new mail into the archive of the Google group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/groupidarchive-post-openapi.md
- name: Google Apps Admin SDK Merged API - Assign License
  x-api-slug: productidskuskuiduser-post
  description: Assign License.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuiduser-post-openapi.md
- name: Google Apps Admin SDK Merged API - Revoke License
  x-api-slug: productidskuskuiduseruserid-delete
  description: Revoke License.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuiduseruserid-delete-openapi.md
- name: Google Apps Admin SDK Merged API - Get License
  x-api-slug: productidskuskuiduseruserid-get
  description: Get license assignment of a particular product and sku for a user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuiduseruserid-get-openapi.md
- name: Google Apps Admin SDK Merged API - Update License
  x-api-slug: productidskuskuiduseruserid-patch
  description: Assign License. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuiduseruserid-patch-openapi.md
- name: Google Apps Admin SDK Merged API - Update License
  x-api-slug: productidskuskuiduseruserid-put
  description: Assign License.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuiduseruserid-put-openapi.md
- name: Google Apps Admin SDK Merged API - Get License Assignment For Product
  x-api-slug: productidskuskuidusers-get
  description: List license assignments for given product and sku of the customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuidusers-get-openapi.md
- name: Google Apps Admin SDK Merged API - Get License Assignment For User
  x-api-slug: productidusers-get
  description: List license assignments for given product of the customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidusers-get-openapi.md
- name: Google Apps Admin SDK Merged API - Create Customer
  x-api-slug: customers-post
  description: Order a new customer's account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customers-post-openapi.md
- name: Google Apps Admin SDK Merged API - Get Customer
  x-api-slug: customerscustomerid-get
  description: Get a customer account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomerid-get-openapi.md
- name: Google Apps Admin SDK Merged API - Update Customer
  x-api-slug: customerscustomerid-patch
  description: Update a customer account's settings. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomerid-patch-openapi.md
- name: Google Apps Admin SDK Merged API - Update Customer
  x-api-slug: customerscustomerid-put
  description: Update a customer account's settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomerid-put-openapi.md
- name: Google Apps Admin SDK Merged API - Create Subscription
  x-api-slug: customerscustomeridsubscriptions-post
  description: Create or transfer a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptions-post-openapi.md
- name: Google Apps Admin SDK Merged API - Cancel Subscription
  x-api-slug: customerscustomeridsubscriptionssubscriptionid-delete
  description: Cancel, suspend or transfer a subscription to direct.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionid-delete-openapi.md
- name: Google Apps Admin SDK Merged API - Get Subscription
  x-api-slug: customerscustomeridsubscriptionssubscriptionid-get
  description: Get a specific subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionid-get-openapi.md
- name: Google Apps Admin SDK Merged API - Activate Subscription
  x-api-slug: customerscustomeridsubscriptionssubscriptionidactivate-post
  description: Activates a subscription previously suspended by the reseller
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidactivate-post-openapi.md
- name: Google Apps Admin SDK Merged API - Update Subscription
  x-api-slug: customerscustomeridsubscriptionssubscriptionidchangeplan-post
  description: Update a subscription plan. Use this method to update a plan for a
    30-day trial or a flexible plan subscription to an annual commitment plan with
    monthly or yearly payments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidchangeplan-post-openapi.md
- name: Google Apps Admin SDK Merged API - Update User License
  x-api-slug: customerscustomeridsubscriptionssubscriptionidchangerenewalsettings-post
  description: Update a user license's renewal settings. This is applicable for accounts
    with annual commitment plans only.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidchangerenewalsettings-post-openapi.md
- name: Google Apps Admin SDK Merged API - Update Suscription License
  x-api-slug: customerscustomeridsubscriptionssubscriptionidchangeseats-post
  description: Update a subscription's user license settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidchangeseats-post-openapi.md
- name: Google Apps Admin SDK Merged API - Upgrade Free Trial
  x-api-slug: customerscustomeridsubscriptionssubscriptionidstartpaidservice-post
  description: Immediately move a 30-day free trial subscription to a paid service
    subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidstartpaidservice-post-openapi.md
- name: Google Apps Admin SDK Merged API - Suspect Subscription
  x-api-slug: customerscustomeridsubscriptionssubscriptionidsuspend-post
  description: Suspends an active subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidsuspend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidsuspend-post-openapi.md
- name: Google Apps Admin SDK Merged API - Get Watch Details
  x-api-slug: resellernotifygetwatchdetails-get
  description: Returns all the details of the watch corresponding to the reseller.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/resellernotifygetwatchdetails-get-openapi.md
- name: Google Apps Admin SDK Merged API - Register Reseller
  x-api-slug: resellernotifyregister-post
  description: Registers a Reseller for receiving notifications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/resellernotifyregister-post-openapi.md
- name: Google Apps Admin SDK Merged API - Unregister Reseller
  x-api-slug: resellernotifyunregister-post
  description: Unregisters a Reseller for receiving notifications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/resellernotifyunregister-post-openapi.md
- name: Google Apps Admin SDK Merged API - List Subscriptions
  x-api-slug: subscriptions-get
  description: List of subscriptions managed by the reseller. The list can be all
    subscriptions, all of a customer's subscriptions, or all of a customer's transferable
    subscriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/subscriptions-get-openapi.md
- name: Google Apps Admin SDK Merged API - Get Group
  x-api-slug: groupuniqueid-get
  description: Gets one resource by id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/groupuniqueid-get-openapi.md
- name: Google Apps Admin SDK Merged API - Update Group
  x-api-slug: groupuniqueid-patch
  description: Updates an existing resource. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/groupuniqueid-patch-openapi.md
- name: Google Apps Admin SDK Merged API - Update Group
  x-api-slug: groupuniqueid-put
  description: Updates an existing resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google APIs, Applications, Documents, Licensing, SDK, Monetization, Reseller,
    Stack Network, Resellers, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/groupuniqueid-put-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.app.engine.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.apps.admin.sdk.stack.network
- type: x-blog
  url: https://gsuite-developers.googleblog.com/search/label/Admin%20SDK
- type: x-blog-rss
  url: https://gsuite-developers.googleblog.com/feeds/posts/default?alt=rss
- type: x-issues
  url: https://code.google.com/a/google.com/p/apps-api-issues/issues/list?q=label:API-Apps
- type: x-website
  url: https://developers.google.com/admin-sdk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---