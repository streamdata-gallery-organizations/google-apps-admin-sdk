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
x-alexaRank: ""
tags: Google Apps Admin SDK
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/apis.md
specificationVersion: "0.14"
apis:
- name: Google Apps Admin SDK API Get Activities
  x-api-slug: google-apps-admin-sdk-api
  description: Retrieves a list of activities for a specific customer and application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///activity/users/{userKey}/applications/{applicationName}
  tags: Activities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/activityusersuserkeyapplicationsapplicationname-get-openapi.md
- name: Google Apps Admin SDK API Change Activity
  x-api-slug: google-apps-admin-sdk-api
  description: Push changes to activities
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///activity/users/{userKey}/applications/{applicationName}/watch
  tags: Activities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/activityusersuserkeyapplicationsapplicationnamewatch-post-openapi.md
- name: Google Apps Admin SDK API Stop Watching Resource
  x-api-slug: google-apps-admin-sdk-api
  description: Stop watching resources through this channel
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///admin/reports_v1/channels/stop
  tags: Channel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/adminreports-v1channelsstop-post-openapi.md
- name: Google Apps Admin SDK API Get Report by Date
  x-api-slug: google-apps-admin-sdk-api
  description: Retrieves a report which is a collection of properties / statistics
    for a specific customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///usage/dates/{date}
  tags: Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/usagedatesdate-get-openapi.md
- name: Google Apps Admin SDK API Get User Report by Date
  x-api-slug: google-apps-admin-sdk-api
  description: Retrieves a report which is a collection of properties / statistics
    for a set of users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///usage/users/{userKey}/dates/{date}
  tags: Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/usageusersuserkeydatesdate-get-openapi.md
- name: Google Apps Admin SDK API Archive Mail
  x-api-slug: google-apps-admin-sdk-api
  description: Inserts a new mail into the archive of the Google group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{groupId}/archive
  tags: Archives
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/groupidarchive-post-openapi.md
- name: Google Apps Admin SDK API Assign License
  x-api-slug: google-apps-admin-sdk-api
  description: Assign License.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{productId}/sku/{skuId}/user
  tags: License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuiduser-post-openapi.md
- name: Google Apps Admin SDK API Revoke License
  x-api-slug: google-apps-admin-sdk-api
  description: Revoke License.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{productId}/sku/{skuId}/user/{userId}
  tags: License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuiduseruserid-delete-openapi.md
- name: Google Apps Admin SDK API Get License
  x-api-slug: google-apps-admin-sdk-api
  description: Get license assignment of a particular product and sku for a user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{productId}/sku/{skuId}/user/{userId}
  tags: License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuiduseruserid-get-openapi.md
- name: Google Apps Admin SDK API Update License
  x-api-slug: google-apps-admin-sdk-api
  description: Assign License. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{productId}/sku/{skuId}/user/{userId}
  tags: License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuiduseruserid-patch-openapi.md
- name: Google Apps Admin SDK API Update License
  x-api-slug: google-apps-admin-sdk-api
  description: Assign License.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{productId}/sku/{skuId}/user/{userId}
  tags: License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuiduseruserid-put-openapi.md
- name: Google Apps Admin SDK API Get License Assignment For Product
  x-api-slug: google-apps-admin-sdk-api
  description: List license assignments for given product and sku of the customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{productId}/sku/{skuId}/users
  tags: License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidskuskuidusers-get-openapi.md
- name: Google Apps Admin SDK API Get License Assignment For User
  x-api-slug: google-apps-admin-sdk-api
  description: List license assignments for given product of the customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{productId}/users
  tags: License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/productidusers-get-openapi.md
- name: Google Apps Admin SDK API Create Customer
  x-api-slug: google-apps-admin-sdk-api
  description: Order a new customer's account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers
  tags: Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customers-post-openapi.md
- name: Google Apps Admin SDK API Get Customer
  x-api-slug: google-apps-admin-sdk-api
  description: Get a customer account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}
  tags: Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomerid-get-openapi.md
- name: Google Apps Admin SDK API Update Customer
  x-api-slug: google-apps-admin-sdk-api
  description: Update a customer account's settings. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}
  tags: Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomerid-patch-openapi.md
- name: Google Apps Admin SDK API Update Customer
  x-api-slug: google-apps-admin-sdk-api
  description: Update a customer account's settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}
  tags: Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomerid-put-openapi.md
- name: Google Apps Admin SDK API Create Subscription
  x-api-slug: google-apps-admin-sdk-api
  description: Create or transfer a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}/subscriptions
  tags: Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptions-post-openapi.md
- name: Google Apps Admin SDK API Cancel Subscription
  x-api-slug: google-apps-admin-sdk-api
  description: Cancel, suspend or transfer a subscription to direct.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}/subscriptions/{subscriptionId}
  tags: Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionid-delete-openapi.md
- name: Google Apps Admin SDK API Get Subscription
  x-api-slug: google-apps-admin-sdk-api
  description: Get a specific subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}/subscriptions/{subscriptionId}
  tags: Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionid-get-openapi.md
- name: Google Apps Admin SDK API Activate Subscription
  x-api-slug: google-apps-admin-sdk-api
  description: Activates a subscription previously suspended by the reseller
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}/subscriptions/{subscriptionId}/activate
  tags: Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidactivate-post-openapi.md
- name: Google Apps Admin SDK API Update Subscription
  x-api-slug: google-apps-admin-sdk-api
  description: Update a subscription plan. Use this method to update a plan for a
    30-day trial or a flexible plan subscription to an annual commitment plan with
    monthly or yearly payments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}/subscriptions/{subscriptionId}/changePlan
  tags: Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidchangeplan-post-openapi.md
- name: Google Apps Admin SDK API Update User License
  x-api-slug: google-apps-admin-sdk-api
  description: Update a user license's renewal settings. This is applicable for accounts
    with annual commitment plans only.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}/subscriptions/{subscriptionId}/changeRenewalSettings
  tags: License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidchangerenewalsettings-post-openapi.md
- name: Google Apps Admin SDK API Update Suscription License
  x-api-slug: google-apps-admin-sdk-api
  description: Update a subscription's user license settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}/subscriptions/{subscriptionId}/changeSeats
  tags: License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidchangeseats-post-openapi.md
- name: Google Apps Admin SDK API Upgrade Free Trial
  x-api-slug: google-apps-admin-sdk-api
  description: Immediately move a 30-day free trial subscription to a paid service
    subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}/subscriptions/{subscriptionId}/startPaidService
  tags: Free Trial
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidstartpaidservice-post-openapi.md
- name: Google Apps Admin SDK API Suspect Subscription
  x-api-slug: google-apps-admin-sdk-api
  description: Suspends an active subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///customers/{customerId}/subscriptions/{subscriptionId}/suspend
  tags: LicenseSubscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidsuspend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/customerscustomeridsubscriptionssubscriptionidsuspend-post-openapi.md
- name: Google Apps Admin SDK API Get Watch Details
  x-api-slug: google-apps-admin-sdk-api
  description: Returns all the details of the watch corresponding to the reseller.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///resellernotify/getwatchdetails
  tags: Notification
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/resellernotifygetwatchdetails-get-openapi.md
- name: Google Apps Admin SDK API Register Reseller
  x-api-slug: google-apps-admin-sdk-api
  description: Registers a Reseller for receiving notifications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///resellernotify/register
  tags: Register
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/resellernotifyregister-post-openapi.md
- name: Google Apps Admin SDK API Unregister Reseller
  x-api-slug: google-apps-admin-sdk-api
  description: Unregisters a Reseller for receiving notifications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///resellernotify/unregister
  tags: Register
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/resellernotifyunregister-post-openapi.md
- name: Google Apps Admin SDK API List Subscriptions
  x-api-slug: google-apps-admin-sdk-api
  description: List of subscriptions managed by the reseller. The list can be all
    subscriptions, all of a customer's subscriptions, or all of a customer's transferable
    subscriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///subscriptions
  tags: Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/subscriptions-get-openapi.md
- name: Google Apps Admin SDK API Get Group
  x-api-slug: google-apps-admin-sdk-api
  description: Gets one resource by id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{groupUniqueId}
  tags: Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/groupuniqueid-get-openapi.md
- name: Google Apps Admin SDK API Update Group
  x-api-slug: google-apps-admin-sdk-api
  description: Updates an existing resource. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{groupUniqueId}
  tags: Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/groupuniqueid-patch-openapi.md
- name: Google Apps Admin SDK API Update Group
  x-api-slug: google-apps-admin-sdk-api
  description: Updates an existing resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https://///{groupUniqueId}
  tags: Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/groupuniqueid-put-openapi.md
- name: Google Apps Admin SDK API
  x-api-slug: google-apps-admin-sdk-api
  description: Administer domain resources, create reports, and manage subscriptions.
    Use the Directory API to create and manage users and groups for a domain, along
    with their aliases. Programmatically access the functionality found at the Admin
    console Organization and users tab. Use the Reports API to gain insights on content
    management with Google Drive activity reports. Audit administrator actions. Generate
    customer and user usage reports.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/nexusae0_icon2.png
  humanURL: https://developers.google.com/admin-sdk/
  baseURL: https:///
  tags: Google Apps Admin SDK
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-apps-admin-sdk/master/_listings/google-apps-admin-sdk/openapi.md
x-common:
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