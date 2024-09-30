---
name: Walmart
description: >-
  Walmart Inc. is an American multinational retail corporation that operates a
  chain of hypermarkets, discount department stores, and grocery stores in the
  United States, headquartered in Bentonville, Arkansas.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: >-
  https://raw.githubusercontent.com/api-search/commerce/main/_apis/walmart/apis.md
created: 2023/11/15
modified: '2024-07-03'
specificationVersion: '0.18'
tags: []
apis:
  - name: Walmart Marketplace Feeds API
    description: >-
      Feeds are constructed to handle bulk functions. A feed consists of an HTTP
      request with an attached file. The attached file contains the XML
      representing the objects that need to be created or updated. The Walmart
      APIs version 3.0 supports only Item and Feed types. Refer to the bulk
      endpoints in each section to see example Feeds for each feed type. Once
      you upload the Feeds, you can use the Feed ID to track the status of the
      feeds and the status of the item within those Feeds.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/api/us/mp/feeds
    baseURL: https://api.example.com
    tags:
      - Feeds
      - Statuses
      - Items
      - Status
      - Errors
      - Reports
    properties:
      - type: Documentation
        url: https://developer.walmart.com/api/us/mp/feeds
      - type: OpenAPI
        url: properties/walmart-marketplace-feeds-openapi-original.yml
    aid: walmart:walmart-marketplace-feeds-api
  - name: Walmart Marketplace Items API
    description: >-
      The Item Management APIs enable you to set up and manage items on
      Walmart.com. Once you have completed Registration and have access to your
      Consumer ID and Private Key, you can get started with the integration
      process
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/api/us/mp/items
    baseURL: https://api.example.com
    tags:
      - Catalog
      - Items
      - Search
      - Associations
      - (Multiple)
      - Bulk
      - Feeds
      - Setup
      - Walmart
      - Taxonomy
      - Count
      - Groups
      - Status
      - Retire
      - Sku
    properties:
      - type: OpenAPI
        url: properties/walmart-marketplace-items-openapi-original.yml
      - type: Documentation
        url: https://developer.walmart.com/api/us/mp/items
    aid: walmart:walmart-marketplace-items-api
  - name: Walmart Marketplace Prices API
    description: >-
      The price is a fundamental building block for your listing on Walmart.com.
      You can use the price management APIs to set up and manage the price for a
      given item
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/api/us/mp/price
    baseURL: https://api.example.com
    tags:
      - Collections
      - Repricer
      - Strategies
      - Incentive
      - Items
      - Assign
      - Prices
      - Assign/Unassign
      - Feeds
      - To/from
      - (Multiple)
      - Bulk
      - CAP
      - Cppreference
      - SKU
      - Sets
      - Up
    properties:
      - type: Documentation
        url: https://developer.walmart.com/api/us/mp/price
      - type: OpenAPI
        url: properties/walmart-marketplace-prices-openapi-original.yml
    aid: walmart:walmart-marketplace-prices-api
  - name: Walmart Promotions API
    description: >-
      Sellers can set regular or promotional prices for their items. Setting the
      Promotional prices is an option to create unique pricing for events such
      as clearance sales or to call out a comparison price
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/api/us/mp/promotion
    baseURL: https://api.example.com
    tags:
      - Prices
      - Promotional
      - Bulk
      - Feeds
      - Promo
      - Sku
    properties:
      - type: Documentation
        url: https://developer.walmart.com/api/us/mp/promotion
      - type: OpenAPI
        url: properties/walmart-marketplace-promotions-openapi-original.yml
    overlays: []
    aid: walmart:walmart-promotions-api
  - name: Walmart Orders API
    description: >-
      The Walmart Order Management APIs help Sellers to manage customer’s Sales
      Orders and to stay up-to-date on orders fulfillment, which orders to
      fulfill, and when to fulfill them.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/api/us/mp/orders
    baseURL: https://api.example.com
    tags:
      - Lines
      - Orders
      - Purchase
      - Ship
      - Shipping
      - Refunds
      - Cancel
      - Acknowledge
      - Released
    properties:
      - type: Documentation
        url: https://developer.walmart.com/api/us/mp/orders
      - type: OpenAPI
        url: properties/walmart-marketplace-orders-openapi-original.yml
    overlays: []
    aid: walmart:walmart-orders-api
  - name: Walmart Returns API
    description: >-
      Buyers can now Initiate Returns from Walmart.com for Marketplace seller
      items (Except for HAZMAT, OTHER or FREIGHT items). For item in the
      exception categories: HAZMAT or OTHER, sellers need to generate the return
      shipping label, and upload the label. For detailed instructions, and to
      download the Returns API JSON schema, see Returns guide.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/api/us/mp/returns
    baseURL: https://api.example.com
    tags:
      - Issues
      - Orders
      - Refunds
      - Returns
      - Feeds
      - Items
      - Overrides
    properties:
      - type: Documentation
        url: https://developer.walmart.com/api/us/mp/returns
      - type: OpenAPI
        url: properties/walmart-marketplace-returns-openapi-original.yml
    overlays: []
    aid: walmart:walmart-returns-api
  - name: Walmart Inventory API
    description: >-
      Maintaining up-to-date inventory for your items on Walmart.com ensures a
      great experience for your customers and greater sales opportunities for
      you.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/api/us/mp/inventory
    baseURL: https://api.example.com
    tags:
      - Inventory
      - Inventories
      - Items
      - Nodes
      - Ship
      - Single
      - Sku
      - Bulk
      - Feeds
      - Multiple
      - Fulfillment
      - WFS
    properties:
      - type: Documentation
        url: https://developer.walmart.com/api/us/mp/inventory
      - type: OpenAPI
        url: properties/walmart-marketplace-inventory-openapi-original.yml
    overlays: []
    aid: walmart:walmart-inventory-api
  - name: Walmart Dropship Vendor Costs API
    description: >-
      Drop ship vendor (DSV) suppliers can update the cost for a single item or
      multiple items in bulk with the Cost API.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/us-supplier/us-supplier-cost/
    baseURL: https://api.example.com
    tags:
      - Bulk
      - Cost
      - Feeds
      - Items
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/us-supplier/us-supplier-cost/
      - type: OpenAPI
        url: properties/walmart-dropship-vendor-costs-openapi-original.yml
    overlays: []
    aid: walmart:walmart-dropship-vendor-costs-api
  - name: Walmart Dropship Vendor Inventory API
    description: >-
      Walmart’s Inventory Management API provide drop ship vending (DSV)
      suppliers with mechanisms to update and view current item inventory levels
      at each ship node, also known as fulfillment centers. Suppliers assign
      each item they fulfill drop ship vending (DSV) through one or more ship
      nodes. Suppliers must accurately maintain the item’s inventory level at
      each ship node to ensure availability for customer orders.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/us-supplier/us-supplier-inventory/
    baseURL: https://api.example.com
    tags:
      - Count
      - Inventory
      - Items
      - Nodes
      - Ship
      - Single
      - Bulk
      - Feeds
      - Inventories
      - Specific
    properties:
      - type: Documentation
        url: >-
          https://developer.walmart.com/doc/us/us-supplier/us-supplier-inventory/
      - type: OpenAPI
        url: properties/walmart-dropship-vendor-inventory-openapi-original.yml
    overlays: []
    aid: walmart:walmart-dropship-vendor-inventory-api
  - name: Walmart Dropship Vendor Items API
    description: >-
      The Walmart Order Management API help 1P suppliers stay up to date on
      order fulfillment.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/us-supplier/us-supplier-orders/
    baseURL: https://api.example.com
    tags:
      - Bulk
      - Feeds
      - Items
      - Maintain
      - Media
      - Rich
      - (v4)
      - Products
      - Single
      - (v3)
      - Sku
      - Expose
      - Taxonomy
      - Types
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/us-supplier/us-supplier-orders/
      - type: OpenAPI
        url: properties/walmart-dropship-vendor-items-openapi-original.yml
    overlays: []
    aid: walmart:walmart-dropship-vendor-items-api
  - name: Walmart Dropship Vendor Lag Time API
    description: >-
      Drop ship vending (DSV) suppliers are expected to ship items the day they
      receive the purchase order (PO). However, there may be times when drop
      ship vendors (DSV) have an item that does not ship the same day. This
      delay is called a lag time. These Lag Time requests allow suppliers to
      update the lag time or to view the number of days between when an item is
      ordered and when it is shipped.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/us-supplier/us-supplier-lagtime/
    baseURL: https://api.example.com
    tags:
      - Bulk
      - Feeds
      - Items
      - Lag
      - Time
      - Based
      - ID
      - Lagtime
      - Products
      - Single
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/us-supplier/us-supplier-lagtime/
      - type: OpenAPI
        url: properties/walmart-dropship-vendor-lag-time-openapi-original.yml
    overlays: []
    aid: walmart:walmart-dropship-vendor-lag-time-api
  - name: Walmart Dropship Vendor On-Request Reports API
    description: >-
      The On Request Reports API lets users request item reports. Request a
      report at any time, subscribe to notifications when the report is ready,
      and download the requested report.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: >-
      https://developer.walmart.com/doc/us/us-supplier/us-supplier-onrequestreports/
    baseURL: https://api.example.com
    tags:
      - Reports
      - Details
      - Single
      - Download
      - URL
    properties:
      - type: Documentation
        url: >-
          https://developer.walmart.com/doc/us/us-supplier/us-supplier-onrequestreports/
      - type: OpenAPI
        url: >-
          properties/walmart-dropship-vendor-on-request-reports-openapi-original.yml
    overlays: []
    aid: walmart:walmart-dropship-vendor-on-request-reports-api
  - name: Walmart Dropship Vendor Orders API
    description: >-
      The Walmart Order Management API help 1P suppliers stay up to date on
      order fulfillment.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/us-supplier/us-supplier-orders/
    baseURL: https://api.example.com
    tags:
      - Lines
      - More
      - Orders
      - Purchase
      - Ship
      - Shipping
      - Cancel
      - Acknowledge
      - Single
      - Released
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/us-supplier/us-supplier-orders/
      - type: OpenAPI
        url: properties/walmart-dropship-vendor-orders-openapi-original.yml
    overlays: []
    aid: walmart:walmart-dropship-vendor-orders-api
  - name: Walmart Dropship Vendor Orders API
    description: >-
      The Walmart Order Management API help 1P suppliers stay up to date on
      order fulfillment.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/us-supplier/us-supplier-orders/
    baseURL: https://api.example.com
    tags:
      - Generate
      - Items
      - Reports
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/us-supplier/us-supplier-orders/
      - type: OpenAPI
        url: >-
          properties/walmart-dropship-vendor-pre-generated-reports-openapi-original.yml
    overlays: []
    aid: walmart:walmart-dropship-vendor-orders-api
  - name: Walmart Marketplace Authentication API
    description: >-
      Authentication creates and manages access tokens to ensure users are
      verified. The Walmart 1P Supplier APIs use open authorization (OAuth 2.0)
      for token-based authentication.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/api/us/supplier/auth
    baseURL: https://api.example.com
    tags:
      - Tokens
      - Detail
    properties:
      - type: Documentation
        url: https://developer.walmart.com/api/us/supplier/auth
      - type: OpenAPI
        url: properties/walmart-marketplace-authentication-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-authentication-api
  - name: Walmart Marketplace Fulfillment API
    description: >-
      The Walmarts Multichannel Solution is an extension of Walmart Fulfillment
      Services (WFS), uniquely placed to ensure quality, scale, and efficiency
      for a seller to grow a successful business. The entire assortment of
      inventory, supply chain management and fulfillment capabilities are
      centralized and managed by Walmart while seller’s items can be listed and
      sold at multiple online platforms and storefronts.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-fulfillment/
    baseURL: https://api.example.com
    tags:
      - Fulfillment
      - Quantities
      - Shipment
      - Hazmat
      - Hold
      - Items
      - Onhold
      - Search
      - Tracking
      - Inbound
      - Labels
      - Customers
      - Fulfillments
      - Orders
      - Deliveries
      - Details
      - Fetch
      - Options
      - Promise
      - Cancel
      - Shipments
      - Previews
      - Carrier
      - Quotes
      - Rates
      - Confirm
      - Print
      - Convert
      - Feeds
      - WFS
      - Health
      - Inventory
      - Reports
      - Wfs
      - Status
      - (deprecated)
      - Logs
      - Errors
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-fulfillment/
      - type: OpenAPI
        url: properties/walmart-marketplace-fulfillment-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-fulfillment-api
  - name: Walmart Marketplace Insights API
    description: >-
      To grow your business, you can use Insights API to learn actionable
      information critical to building your business and catalog offerings. With
      the Insights API you can learn actionable information about your current
      listings: Top trending items, unpublished items, and quality of item
      listings.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-insights/
    baseURL: https://api.example.com
    tags:
      - Details
      - Insights
      - Items
      - Listings
      - Quality
      - Badge
      - Pro
      - Prosellerbadge
      - Seller
      - Status
      - Unpublished
      - Counts
      - Top
      - Trending
      - Scores
      - Count
      - Issues
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-insights/
      - type: OpenAPI
        url: properties/walmart-marketplace-insights-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-insights-api
  - name: Walmart Marketplace Lag Time API
    description: >-
      Lag Time is the number of days between the date an item is ordered and
      when it is shipped. During Item Setup, Lag Time can be set to 0 days or 1
      day. Any other value used will be defaulted to 1 day.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-lagtime/
    baseURL: https://api.example.com
    tags:
      - Feeds
      - Lag
      - Time
      - Lagtime
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-lagtime/
      - type: OpenAPI
        url: properties/walmart-marketplace-lag-time-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-lag-time-api
  - name: Walmart Marketplace Notifications API
    description: >-
      Push notifications or Web Hooks trigger alerts to seller applications when
      specific events occur, such as an item is unpublished, a new purchase
      order is created, an item’s inventory is out of stock, etc. Whenever the
      trigger event occurs, Walmart will send a notification payload with event
      details to the seller-defined destination URL. Web Hooks help to optimize
      integration, automate workflows and reduce the number of times your
      application has to poll Walmart APIs within the throttle limits to
      determine if an event has occurred.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-notifications/
    baseURL: https://api.example.com
    tags:
      - Notifications
      - Tests
      - Webhooks
      - Subscriptions
      - Events
      - Types
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-notifications/
      - type: OpenAPI
        url: properties/walmart-marketplace-notifications-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-notifications-api
  - name: Walmart Marketplace On-Request Reports API
    description: >-
      The On-request Reports API enables you to request item reports immediately
      about your items for faster retrieval. Now you can request a report at any
      time, subscribe to notifications that report is ready, and then you can
      download it.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-onrequestreports/
    baseURL: https://api.example.com
    tags:
      - Reports
      - Status
      - Download
      - URL
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-onrequestreports/
      - type: OpenAPI
        url: properties/walmart-marketplace-on-request-reports-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-on-request-reports-api
  - name: Walmart Marketplace Recommendations API
    description: >-
      Assortment recommendations empower sellers understand and identify the
      customer demand in Walmart & market by curating personalised seller
      recommendations by leveraging demand signals such as Internal and external
      search, Best Sellers, Trending items, and more.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-assortmentrecommendations/
    baseURL: https://api.example.com
    tags:
      - Assortment
      - Growth
      - Recommendations
      - Categorization
      - Counts
      - Reject
      - Rejections
    properties:
      - type: Documentation
        url: >-
          https://developer.walmart.com/doc/us/mp/us-mp-assortmentrecommendations/
      - type: OpenAPI
        url: properties/walmart-marketplace-recommendations-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-recommendations-api
  - name: Walmart Marketplace Reports API
    description: >-
      The On-request Reports API enables you to request item reports immediately
      about your items for faster retrieval. Now you can request a report at any
      time, subscribe to notifications that report is ready, and then you can
      download it.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-onrequestreports/
    baseURL: https://api.example.com
    tags:
      - Available
      - Dates
      - Files
      - JSON
      - Payments
      - Performance
      - Recon
      - Reports
      - Statements
      - Versions
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-onrequestreports/
      - type: OpenAPI
        url: properties/walmart-marketplace-reports-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-reports-api
  - name: Walmart Marketplace Reviews API
    description: >-
      Use the Review Accelerator Program (RAP) APIs to increase the number of
      reviews for items with less than fifteen reviews.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-reviews/
    baseURL: https://api.example.com
    tags:
      - Accelerators
      - Bulk
      - Growth
      - Items
      - Reviews
      - Status
      - Post Purchase
      - RAP
      - Categories
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-reviews/
      - type: OpenAPI
        url: properties/walmart-marketplace-reviews-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-reviews-api
  - name: Walmart Marketplace Rules API
    description: >-
      Walmart is making program enhancements to the existing free 2-Day Shipping
      Program, to enable US marketplace sellers to add multiple fulfillment
      centers along with capability to manage them and easily configure item
      assortment setup for 2-Day program. The capability, Item assortment rules
      for 2-Day program setup, will part of the enhancements:
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-rules/
    baseURL: https://api.example.com
    tags:
      - Inactivate
      - Rules
      - Exceptions
      - Override
      - Assortment
      - Change
      - Types
      - Activate
      - Actions
      - Area
      - Shipping
      - Status
      - Results
      - Simulationcount
      - Simulations
      - Download
      - Sub Categories
      - Subcategories
      - Downloadexceptions
      - Areas
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-rules/
      - type: OpenAPI
        url: properties/walmart-marketplace-rules-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-rules-api
  - name: Walmart Marketplace Settings API
    description: >-
      The Settings API allows you to configure shipping delivery and fulfillment
      settings. You can create shipping templates to specify the precise
      delivery speed for your items. You can specify fulfillment center choices
      for your items. 
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-settings/
    baseURL: https://api.example.com
    tags:
      - Details
      - Settings
      - Shipping
      - Templates
      - Centers
      - Fulfillment
      - Shipnodes
      - Center
      - Accounts
      - Levels
      - 3plshipnodes
      - Associations
      - Party
      - Configurations
      - Shippingprofile
      - Activation
      - Status
      - Coverage
      - Carrier
      - Carriers
      - Methods
      - 3plprov
      - Ers
      - Providers
      - Partnerprofile
      - Partners
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-settings/
      - type: OpenAPI
        url: properties/walmart-marketplace-settings-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-settings-api
  - name: Walmart Marketplace Shipping API
    description: >-
      The Ship With Walmart for US API enables walmart.com sellers to buy
      shipping at competitively discounted rates directly from Walmart to ship
      their goods to US customers.  
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-sww/
    baseURL: https://api.example.com
    tags:
      - Labels
      - Shipping
      - Estimates
      - Detail
      - Orders
      - Purchase
      - Carriers
      - Supported
      - Carrier
      - Download
      - Names
      - Tracking
      - Trackings
      - Discard
      - Commercial
      - Invoices
      - Packages
      - Types
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-sww/
      - type: OpenAPI
        url: properties/walmart-marketplace-shipping-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-shipping-api
  - name: Walmart Marketplace Utilities API
    description: >-
      The Utility APIs allow you to search for all Walmart item departments, all
      categories within a department, or retrieve the taxonomy of categories per
      Feed type.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.walmart.com/doc/us/mp/us-mp-utilities/
    baseURL: https://api.example.com
    tags:
      - Taxonomy
      - Utilities
      - Departments
      - Categories
      - Department
      - Platforms
      - Status
    properties:
      - type: Documentation
        url: https://developer.walmart.com/doc/us/mp/us-mp-utilities/
      - type: OpenAPI
        url: properties/walmart-marketplace-utilities-openapi-original.yml
    overlays: []
    aid: walmart:walmart-marketplace-utilities-api
common:
  - type: Portal
    url: https://developer.walmart.com/
  - type: Docs
    url: https://developer.walmart.com/home/us-mp/
  - type: Sandbox
    url: https://developer.walmart.com/doc/sandbox/
  - type: Whats New
    url: https://developer.walmart.com/category/us/whats-new/
  - type: Support
    url: https://developer.walmart.com/home/help/
  - type: FAQ
    url: https://developer.walmart.com/faq/us/
  - type: Status
    url: https://developer.walmart.com/apiStatus
  - type: Terms of Service
    url: https://developer.walmart.com/faq/terms-and-conditions
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: walmart
---