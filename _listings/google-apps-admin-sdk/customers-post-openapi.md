---
swagger: "2.0"
x-collection-name: Google Apps Admin SDK
x-complete: 0
info:
  title: Google Apps Admin SDK API Create Customer
  version: 1.0.0
  description: Order a new customer's account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /activity/users/{userKey}/applications/{applicationName}:
    get:
      summary: Get Activities
      description: Retrieves a list of activities for a specific customer and application.
      operationId: reports.activities.list
      x-api-path-slug: activityusersuserkeyapplicationsapplicationname-get
      parameters:
      - in: query
        name: actorIpAddress
        description: IP Address of host where the event was performed
      - in: path
        name: applicationName
        description: Application name for which the events are to be retrieved
      - in: query
        name: customerId
        description: Represents the customer for which the data is to be fetched
      - in: query
        name: endTime
        description: Return events which occured at or before this time
      - in: query
        name: eventName
        description: Name of the event being queried
      - in: query
        name: filters
        description: Event parameters in the form [parameter1 name][operator][parameter1
          value],[parameter2 name][operator][parameter2 value],
      - in: query
        name: maxResults
        description: Number of activity records to be shown in each page
      - in: query
        name: pageToken
        description: Token to specify next page
      - in: query
        name: startTime
        description: Return events which occured at or after this time
      - in: path
        name: userKey
        description: Represents the profile id or the user email for which the data
          should be filtered
      responses:
        200:
          description: OK
      tags:
      - Activities
  /activity/users/{userKey}/applications/{applicationName}/watch:
    post:
      summary: Change Activity
      description: Push changes to activities
      operationId: reports.activities.watch
      x-api-path-slug: activityusersuserkeyapplicationsapplicationnamewatch-post
      parameters:
      - in: query
        name: actorIpAddress
        description: IP Address of host where the event was performed
      - in: path
        name: applicationName
        description: Application name for which the events are to be retrieved
      - in: query
        name: customerId
        description: Represents the customer for which the data is to be fetched
      - in: query
        name: endTime
        description: Return events which occured at or before this time
      - in: query
        name: eventName
        description: Name of the event being queried
      - in: query
        name: filters
        description: Event parameters in the form [parameter1 name][operator][parameter1
          value],[parameter2 name][operator][parameter2 value],
      - in: query
        name: maxResults
        description: Number of activity records to be shown in each page
      - in: query
        name: pageToken
        description: Token to specify next page
      - in: body
        name: resource
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: startTime
        description: Return events which occured at or after this time
      - in: path
        name: userKey
        description: Represents the profile id or the user email for which the data
          should be filtered
      responses:
        200:
          description: OK
      tags:
      - Activities
  /admin/reports_v1/channels/stop:
    post:
      summary: Stop Watching Resource
      description: Stop watching resources through this channel
      operationId: admin.channels.stop
      x-api-path-slug: adminreports-v1channelsstop-post
      parameters:
      - in: body
        name: resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Channel
  /usage/dates/{date}:
    get:
      summary: Get Report by Date
      description: Retrieves a report which is a collection of properties / statistics
        for a specific customer.
      operationId: reports.customerUsageReports.get
      x-api-path-slug: usagedatesdate-get
      parameters:
      - in: query
        name: customerId
        description: Represents the customer for which the data is to be fetched
      - in: path
        name: date
        description: Represents the date in yyyy-mm-dd format for which the data is
          to be fetched
      - in: query
        name: pageToken
        description: Token to specify next page
      - in: query
        name: parameters
        description: Represents the application name, parameter name pairs to fetch
          in csv as app_name1:param_name1, app_name2:param_name2
      responses:
        200:
          description: OK
      tags:
      - Report
  /usage/users/{userKey}/dates/{date}:
    get:
      summary: Get User Report by Date
      description: Retrieves a report which is a collection of properties / statistics
        for a set of users.
      operationId: reports.userUsageReport.get
      x-api-path-slug: usageusersuserkeydatesdate-get
      parameters:
      - in: query
        name: customerId
        description: Represents the customer for which the data is to be fetched
      - in: path
        name: date
        description: Represents the date in yyyy-mm-dd format for which the data is
          to be fetched
      - in: query
        name: filters
        description: Represents the set of filters including parameter operator value
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Token to specify next page
      - in: query
        name: parameters
        description: Represents the application name, parameter name pairs to fetch
          in csv as app_name1:param_name1, app_name2:param_name2
      - in: path
        name: userKey
        description: Represents the profile id or the user email for which the data
          should be filtered
      responses:
        200:
          description: OK
      tags:
      - Report
  /{groupId}/archive:
    post:
      summary: Archive Mail
      description: Inserts a new mail into the archive of the Google group.
      operationId: groupsmigration.archive.insert
      x-api-path-slug: groupidarchive-post
      parameters:
      - in: path
        name: groupId
        description: The group ID
      responses:
        200:
          description: OK
      tags:
      - Archives
  /{productId}/sku/{skuId}/user:
    post:
      summary: Assign License
      description: Assign License.
      operationId: licensing.licenseAssignments.insert
      x-api-path-slug: productidskuskuiduser-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: productId
        description: Name for product
      - in: path
        name: skuId
        description: Name for sku
      responses:
        200:
          description: OK
      tags:
      - License
  /{productId}/sku/{skuId}/user/{userId}:
    delete:
      summary: Revoke License
      description: Revoke License.
      operationId: licensing.licenseAssignments.delete
      x-api-path-slug: productidskuskuiduseruserid-delete
      parameters:
      - in: path
        name: productId
        description: Name for product
      - in: path
        name: skuId
        description: Name for sku
      - in: path
        name: userId
        description: email id or unique Id of the user
      responses:
        200:
          description: OK
      tags:
      - License
    get:
      summary: Get License
      description: Get license assignment of a particular product and sku for a user
      operationId: licensing.licenseAssignments.get
      x-api-path-slug: productidskuskuiduseruserid-get
      parameters:
      - in: path
        name: productId
        description: Name for product
      - in: path
        name: skuId
        description: Name for sku
      - in: path
        name: userId
        description: email id or unique Id of the user
      responses:
        200:
          description: OK
      tags:
      - License
    patch:
      summary: Update License
      description: Assign License. This method supports patch semantics.
      operationId: licensing.licenseAssignments.patch
      x-api-path-slug: productidskuskuiduseruserid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: productId
        description: Name for product
      - in: path
        name: skuId
        description: Name for sku for which license would be revoked
      - in: path
        name: userId
        description: email id or unique Id of the user
      responses:
        200:
          description: OK
      tags:
      - License
    put:
      summary: Update License
      description: Assign License.
      operationId: licensing.licenseAssignments.update
      x-api-path-slug: productidskuskuiduseruserid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: productId
        description: Name for product
      - in: path
        name: skuId
        description: Name for sku for which license would be revoked
      - in: path
        name: userId
        description: email id or unique Id of the user
      responses:
        200:
          description: OK
      tags:
      - License
  /{productId}/sku/{skuId}/users:
    get:
      summary: Get License Assignment For Product
      description: List license assignments for given product and sku of the customer.
      operationId: licensing.licenseAssignments.listForProductAndSku
      x-api-path-slug: productidskuskuidusers-get
      parameters:
      - in: query
        name: customerId
        description: CustomerId represents the customer for whom licenseassignments
          are queried
      - in: query
        name: maxResults
        description: Maximum number of campaigns to return at one time
      - in: query
        name: pageToken
        description: Token to fetch the next page
      - in: path
        name: productId
        description: Name for product
      - in: path
        name: skuId
        description: Name for sku
      responses:
        200:
          description: OK
      tags:
      - License
  /{productId}/users:
    get:
      summary: Get License Assignment For User
      description: List license assignments for given product of the customer.
      operationId: licensing.licenseAssignments.listForProduct
      x-api-path-slug: productidusers-get
      parameters:
      - in: query
        name: customerId
        description: CustomerId represents the customer for whom licenseassignments
          are queried
      - in: query
        name: maxResults
        description: Maximum number of campaigns to return at one time
      - in: query
        name: pageToken
        description: Token to fetch the next page
      - in: path
        name: productId
        description: Name for product
      responses:
        200:
          description: OK
      tags:
      - License
  /customers:
    post:
      summary: Create Customer
      description: Order a new customer's account.
      operationId: reseller.customers.insert
      x-api-path-slug: customers-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: customerAuthToken
        description: The customerAuthToken query string is required when creating
          a resold account that transfers a direct customers subscription or transfers
          another reseller customers subscription to your reseller management
      responses:
        200:
          description: OK
      tags:
      - Customer
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