# Laravel Learning Path

This repository contains the **ordered** list of Laravel topics to learn, step-by-step, with related links.

If you want to add a topic, link, or any other suggestion, please open Issues or Pull Requests.

**Notice 1**: The same table below is also available as a database, so you would be able to transform it to any other format you want - PDF, chart, etc. See file [roadmap.sql](roadmap.sql)

**Notice 2**: This content was filled into an adminpanel generated with our [QuickAdminPanel](https://quickadminpanel.com) - here's a [video demo of that process on Youtube](https://www.youtube.com/watch?v=i2ElUDUDRms). By purchasing QuickAdminPanel, you support my free initiatives, like this Roadmap.

--- 

## Beginner Level
Create your very first simple Laravel project

### Routing and Controllers Basics
| Topic | Learning Links | Type | 
| ----- | ----- | ----- |
| Callback Functions and Route::view() | [Basic Routing](https://laravel.com/docs/8.x/routing#basic-routing)| Official Docs |
| | [View Routes](https://laravel.com/docs/8.x/routing#view-routes) | Official Docs |
| Routing to a Single Controller Method | [Basic Controllers with Routes](https://laravel.com/docs/8.x/controllers#basic-controllers)| Official Docs |
| Route Parameters | [Route Parameters](https://laravel.com/docs/8.x/routing#route-parameters) | Official Docs |
| Route Naming | [Names Routes](https://laravel.com/docs/8.x/routing#named-routes)| Official Docs |
| Route Groups | [Route Groups](https://laravel.com/docs/8.x/routing#route-groups)| Official Docs |

### Blade Basics
| Topic | Learning Links | Type | 
| ----- | ----- | ----- |
| Displaying Variables in Blade | [Blade: Displaying Data](https://laravel.com/docs/8.x/blade#displaying-data) | Official Docs |
| Blade If-Else and Loop Structures |[Blade: If-Statements](https://laravel.com/docs/8.x/blade#if-statements) | Official Docs |
| | [Blade Loops](https://laravel.com/docs/8.x/blade#loops) | Official Docs |
| Layout: @include, @extends, @section, @yield | [Blade: Layout Using Template Inheritance](https://laravel.com/docs/8.x/blade#layouts-using-template-inheritance) | Official Docs |
| Blade Components | [Blade Components](https://laravel.com/docs/8.x/blade#components) | Official Docs |
| | [Laravel Blade Components: Two Examples - Laravel Breeze/UI](https://www.youtube.com/watch?v=HybWBINeXMw) | Video |


### Auth Basics
| Topic | Learning Links | Type | 
| ----- | ----- | ----- |
| Starter Kits: Breeze (Tailwind) or Laravel UI (Bootstrap) | [Laravel Breeze Official Documentation](https://laravel.com/docs/8.x/starter-kits#laravel-breeze) | Official Docs |
| | [Laravel UI: Official Github Page](https://github.com/laravel/ui) | Official Docs |
| Default Auth Model and Access its Fields from Anywhere |[Retrieving the Authenticated User](https://laravel.com/docs/8.x/authentication#retrieving-the-authenticated-user)  | Official Docs |
| Check Auth in Controller / Blade |[Determining If The Current User Is Authenticated](https://laravel.com/docs/8.x/authentication#determining-if-the-current-user-is-authenticated) | Official Docs |
| | [Blade: Authentication Directives](https://laravel.com/docs/8.x/blade#authentication-directives) | Official Docs |
| Auth Middleware | [Protecting Routes](https://laravel.com/docs/8.x/authentication#protecting-routes) | Official Docs |


### Database Basics
| Topic | Learning Links | Type | 
| ----- | ----- | ----- |
| Database Migrations | [Database Migrations](https://laravel.com/docs/8.x/migrations) | Official Docs |
| Basic Eloquent Model and MVC: Controller -> Model -> View | [Eloquent: Getting Started](https://laravel.com/docs/8.x/eloquent)  | Official Docs |
| Eloquent Relationships: belongsTo / hasMany / belongsToMany | [Eloquent Relationships: One-to-Many](https://laravel.com/docs/8.x/eloquent-relationships#one-to-many) | Official Docs |
| | [Eloquent Relationships: BelongsTo](https://laravel.com/docs/8.x/eloquent-relationships#one-to-many-inverse) | Official Docs |
| | [Eloquent Relationships: Many-to-Many](https://laravel.com/docs/8.x/eloquent-relationships#many-to-many) | Official Docs |
| Eager Loading and N+1 Query Problem | [Relationships: Eager Loading](https://laravel.com/docs/8.x/eloquent-relationships#eager-loading) | Official Docs |


### Full Simple CRUD
| Topic | Learning Links | Type | 
| ----- | ----- | ----- |
| Route Resource and Resourceful Controllers | [Laravel Resource Controllers](https://laravel.com/docs/8.x/controllers#resource-controllers) | Official Docs |
| | [Simple Laravel CRUD with Resource Controllers [digitalocean.com]](https://www.digitalocean.com/community/tutorials/simple-laravel-crud-with-resource-controllers) | Article |
| Forms, Validation and Form Requests | [Laravel Validation](https://laravel.com/docs/8.x/validation) | Official Docs |
| File Uploads and Storage Folder Basics | [Filesystem: File Uploads](https://laravel.com/docs/8.x/filesystem#file-uploads) | Official Docs |
| Table Pagination | [ Database Pagination](https://laravel.com/docs/8.x/pagination) | Official Docs |

--- 

## Advanced Beginner Level
The goal of this level is to find the first job or freelance gig

| Topic | Learning Links |
| ----- | ----- |
| **Routing Advanced** ||
| Route Model Binding |[Official Docs: Route Model Binding](https://laravel.com/docs/8.x/routing#route-model-binding) <br>[Video: Laravel Route Model Binding: All You Need To Know](https://www.youtube.com/watch?v=6dEfxGLgevM) <br>|
| Route Redirect |[Official Docs: Redirect Routes](https://laravel.com/docs/8.x/routing#redirect-routes) <br>|
| **Middleware** ||
| Create Custom Middleware Class |[Official Docs: Defining Middleware](https://laravel.com/docs/8.x/middleware#defining-middleware) <br>|
| **Database Advanced** ||
| Database Seeders and Factories |[Official Docs: Database: Seeding](https://laravel.com/docs/8.x/seeding) <br>[Official Docs: Defining Model Factories](https://laravel.com/docs/8.x/database-testing#defining-model-factories) <br>|
| Eloquent Query Scopes |[Official Docs: Eloquent: Query Scopes](https://laravel.com/docs/8.x/eloquent#query-scopes) <br>|
| Polymorphic relationships |[Official Docs: Polymorphic Relationships](https://laravel.com/docs/8.x/eloquent-relationships#polymorphic-relationships) <br>|
| Eloquent Accessors and Mutators |[Official Docs: Accessors & Mutators](https://laravel.com/docs/8.x/eloquent-mutators#accessors-and-mutators) <br>|
| Eloquent Collections |[Official Docs: Eloquent Collections](https://laravel.com/docs/8.x/eloquent-collections) <br>[Official Docs: General Laravel Collections](https://laravel.com/docs/8.x/collections) <br>|
| Soft Deletes |[Official Docs: Soft Deleting](https://laravel.com/docs/8.x/eloquent#soft-deleting) <br>|
| **Auth Advanced** ||
| Authorization: Roles/Permissions, Gates, Policies |[Official Docs: Authorization](https://laravel.com/docs/8.x/authorization) <br>[Video: Laravel Roles and Permissions: All CORE Things You Need To Know](https://www.youtube.com/watch?v=kZOgH3-0Bko) <br>|
| Authorization: Extra Packages - Spatie Permission, Bouncer, etc |[Video: Spatie Laravel Permission: Example Project Review](https://www.youtube.com/watch?v=NgToi0uiMNQ) <br>[Article: Two Best Laravel Packages to Manage Roles/Permissions](https://laravel-news.com/two-best-roles-permissions-packages) <br>[Official Docs: spatie/laravel-permission](https://github.com/spatie/laravel-permission) <br>[Official Docs: JosephSilber/bouncer](https://github.com/JosephSilber/bouncer) <br>|
| Authentication: Email Verification |[Official Docs: Email Verification](https://laravel.com/docs/8.x/verification) <br>|
| **File Uploads Advanced** ||
| Drivers and Disks, Example of Amazon S3 |[Official Docs: File Storage](https://laravel.com/docs/8.x/filesystem) <br>[Video: Laravel: How to Upload Files to Amazon S3](https://www.youtube.com/watch?v=xZQM9q_QxMA) <br>|
| Extra Packages: Spatie Medialibrary, Intervention Image, etc |[Official Docs: spatie/laravel-medialibrary](https://github.com/spatie/laravel-medialibrary) <br>[Official Docs: intervention/image](https://github.com/Intervention/image) <br>|
| **API Basics** ||
| API Routes and Controllers |[Official Docs: API Resource Routes](https://laravel.com/docs/8.x/controllers#api-resource-routes) <br>[Official Docs: Default Route Files](https://laravel.com/docs/8.x/routing#the-default-route-files) <br>|
| Working with API Clients: Postman or Alternatives |[Official Docs: Postman API Client](https://www.postman.com/product/api-client/) <br>|
| API Eloquent Resources |[Official Docs: Eloquent: API Resources](https://laravel.com/docs/8.x/eloquent-resources) <br>|
| API Auth with Sanctum |[Official Docs: Laravel Sanctum](https://laravel.com/docs/8.x/sanctum) <br>|
| API Error Handling and Status Codes |[Video: Laravel API 404 Error: Customize Exception Message](https://www.youtube.com/watch?v=SlBJrLnyoMk) <br>[Article: HTTP Status Codes](https://httpstatuses.com/) <br>|
| **Debugging Errors** ||
| Log Files in Laravel |[Official Docs: Logging](https://laravel.com/docs/8.x/logging) <br>|
| Try-Catch and Laravel Exceptions |[Official Docs: Error Handling](https://laravel.com/docs/8.x/errors) <br>[Video: Exceptions in Laravel: Why/How to Use and Create Your Own](https://www.youtube.com/watch?v=RTTXZVIL6tw) <br>|
| Local Debugging Tools: Debugbar, Telescope, Ray |[Official Docs: barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) <br>[Official Docs: Laravel Telescope](https://laravel.com/docs/8.x/telescope) <br>[Official Docs: Spatie Ray (Premium Tool)](https://myray.app/) <br>[Video: Debug Eloquent Queries from API: Laravel Telescope](https://www.youtube.com/watch?v=SR3RzIfeozI) <br>[Video: Spatie Ray: Laravel Debugging with Pleasure](https://www.youtube.com/watch?v=n4pMxyAXeqY) <br>|
| Customizing Error Pages and Messages |[Official Docs: Custom HTTP Error Pages](https://laravel.com/docs/8.x/errors#custom-http-error-pages) <br>[Video: Laravel Error Pages: Change Text or Customize Layouts](https://www.youtube.com/watch?v=iMAFUi6Z57k) <br>|
| (optional) Third Party Bug Trackers: Bugsnag, Flare, Sentry, Rollbar |[Official Docs: Bugsnag Laravel](https://docs.bugsnag.com/platforms/php/laravel/) <br>[Official Docs: Flare Homepage](https://flareapp.io/) <br>[Official Docs: Sentry Laravel](https://docs.sentry.io/platforms/php/guides/laravel/) <br>[Official Docs: Rollbar Laravel](https://docs.rollbar.com/docs/laravel) <br>[Video: Bug Tracking in Laravel: Bugsnag vs Flare [Demo/Review]](https://www.youtube.com/watch?v=88UqUXhWwGA) <br>|
| **Sending Email** ||
| Mailables and Mail Facade |[Official Docs: Mail & Mailables](https://laravel.com/docs/8.x/mail) <br>|
| Configure Drivers/Services: Mailgun, Mailtrap, etc |[Article: How to Send Email From Laravel, and Why We Need 3rd Party Providers For It](https://laraveldaily.com/how-to-send-email-from-laravel-and-why-we-need-3rd-party-providers-for-it/) <br>[Official Docs: Mail: Drivers Prerequisites](https://laravel.com/docs/8.x/mail#driver-prerequisites) <br>|
| Notifications System: Email, SMS, Slack, etc. |[Official Docs: Notifications](https://laravel.com/docs/8.x/notifications) <br>|
| **Automated Testing with PHPUnit** ||
| "Smoke" Tests to Check if Pages are Loading |[Official Docs: Testing: Getting Started](https://laravel.com/docs/8.x/testing) <br>[Course: Laravel: PHPUnit Testing for Beginners](https://laraveldaily.teachable.com/p/laravel-phpunit-testing-for-beginners) <br>|
| Configure Testing Database and Test CRUD Operations |[Official Docs: Database Testing](https://laravel.com/docs/8.x/database-testing) <br>|
| **Deployment and Version Control** ||
| Git Version Control |[Official Docs: Git](https://git-scm.com/) <br>[Video: Git in Laravel. Part 1 - Branches: Main, Develop and Feature](https://www.youtube.com/watch?v=AmScEC-_72I) <br>|
| Deployment on Live Servers |[Official Docs: Deployment](https://laravel.com/docs/8.x/deployment) <br>[Article: How to Deploy Laravel Projects to Live Server: The Ultimate Guide](https://laraveldaily.com/how-to-deploy-laravel-projects-to-live-server-the-ultimate-guide/) <br>[Article: What Server is Needed to Deploy Laravel Projects](https://laraveldaily.com/what-server-is-needed-to-deploy-laravel-projects/) <br>[Video: How we Deploy Laravel: Branches, Staging Servers, Forge and Envoyer](https://www.youtube.com/watch?v=8DVuVftFZcQ) <br>|


## Mid Level
Master all Laravel features with 3-5 years of practical experience

| Topic | Learning Links |
| ----- | ----- |
| **Routing Extra Features** ||
| Route Caching |[Official Docs: Route Caching](https://laravel.com/docs/8.x/routing#route-caching) <br>|
| Rate Limiting |[Official Docs: Rate Limiting](https://laravel.com/docs/8.x/routing#rate-limiting) <br>[Video: Laravel: Create Public API with Cache and Rate Limits](https://www.youtube.com/watch?v=vrLcCxWlxOk) <br>|
| Invokable controllers |[Official Docs: Single Action Controllers](https://laravel.com/docs/8.x/controllers#single-action-controllers) <br>|
| **Database/Eloquent Extra Features** ||
| Model Observers |[Official Docs: Eloquent Observers](https://laravel.com/docs/8.x/eloquent#observers) <br>[Video: Laravel Model: Check if Any Field Was Changed](https://www.youtube.com/watch?v=_xluet13xxE) <br>[Video: Eloquent Observers or Events Listeners? Which is Better?](https://www.youtube.com/watch?v=DvoaU6cQQHM) <br>|
| Raw Database Queries |[Official Docs: Query Builder: Raw Expressions](https://laravel.com/docs/8.x/queries#raw-expressions) <br>|
| All Eloquent Features |[Official Docs: All About Eloquent](https://laravel.com/docs/8.x/eloquent) <br>[Course: Eloquent: Expert Level](https://laraveldaily.teachable.com/p/laravel-eloquent-expert-level) <br>[Article: 20 Laravel Eloquent Tips and Tricks](https://laravel-news.com/eloquent-tips-tricks) <br>|
| **Various Extra Laravel Features** ||
| Caching |[Official Docs: Cache](https://laravel.com/docs/8.x/cache) <br>[Video: Cache Eloquent Query Results to Load Pages Instantly](https://www.youtube.com/watch?v=JhKngeE0XJA) <br>|
| Creating Artisan Commands |[Official Docs: Writing Artisan Commands](https://laravel.com/docs/8.x/artisan#writing-commands) <br>[Video: How to Create Artisan Commands in Laravel](https://www.youtube.com/watch?v=-r3WnYy7g48) <br>|
| Task Scheduling |[Official Docs: Task Scheduling](https://laravel.com/docs/8.x/scheduling) <br>|
| Login with X: Laravel Socialite |[Official Docs: Laravel Socialite](https://laravel.com/docs/8.x/socialite) <br>|
| Laravel HTTP Client and Guzzle |[Official Docs: HTTP Client](https://laravel.com/docs/8.x/http-client) <br>[Video: Laravel and External APIs: Get Data with HTTP Client](https://www.youtube.com/watch?v=oEDDZsmMLc0) <br>|
| Custom Blade Directives |[Official Docs: Extending Blade](https://laravel.com/docs/8.x/blade#extending-blade) <br>|
| Events and Listeners |[Official Docs: Events and Listeners](https://laravel.com/docs/8.x/events) <br>[Video: Laravel: 3 Ways to Send a Welcome Email (Controller vs Observer vs Events)](https://www.youtube.com/watch?v=ZWzH6SOzjhI) <br>[Video: Laravel: Why Observers and Event Listeners are "Risky"](https://www.youtube.com/watch?v=A3bmLo77e5M) <br>|
| **Jobs and Queues** |[Course: Queues in Laravel](https://laraveldaily.teachable.com/p/queues-in-laravel) <br>|
| Queueable Classes and Jobs |[Official Docs: Creating Jobs](https://laravel.com/docs/8.x/queues#creating-jobs) <br>[Official Docs: Queueing Notifications](https://laravel.com/docs/8.x/notifications#queueing-notifications) <br>[Official Docs: Queued Event Listeners](https://laravel.com/docs/8.x/events#queued-event-listeners) <br>[Official Docs: Queueing Mail](https://laravel.com/docs/8.x/mail#queueing-mail) <br>[Video: Laravel Queues 101: Example with Sending Emails](https://www.youtube.com/watch?v=rVx8xKisbr8) <br>|
| Processing Failed Jobs |[Official Docs: Dealing with Failed Jobs](https://laravel.com/docs/8.x/queues#dealing-with-failed-jobs) <br>|
| Job Dispatching, Batching and Chaining |[Official Docs: Dispatching Jobs](https://laravel.com/docs/8.x/queues#dispatching-jobs) <br>|
| Configuring Queues: Drivers, Redis, Supervisor |[Official Docs: Running the Queue Worker](https://laravel.com/docs/8.x/queues#running-the-queue-worker) <br>[Official Docs: Configuring Supervisor](https://laravel.com/docs/8.x/queues#supervisor-configuration) <br>|
| Laravel Horizon (optional, if you use Redis) |[Official Docs: Laravel Horizon](https://laravel.com/docs/8.x/horizon) <br>|
| **API Advanced** ||
| Upload Files via API |[Article: Laravel API: How to Upload File from Vue.js](https://blog.quickadminpanel.com/laravel-api-how-to-upload-file-from-vue-js/) <br>|
| Generate API Documentation |[Article: Laravel API Documentation with OpenAPI/Swagger](https://blog.quickadminpanel.com/laravel-api-documentation-with-openapiswagger/) <br>[Video: Scribe: New Package for Laravel API Documentation](https://www.youtube.com/watch?v=PjwGI8c2IfA) <br>|
| API Versioning |[Article: Versioning your REST API with Laravel](https://codimth.com/blog/web/laravel/versioning-your-rest-api-laravel) <br>[Video: Versioning your API: from V1 to V2 and Beyond [video from my course]](https://laraveldaily.teachable.com/courses/how-to-create-laravel-api/lectures/17568998) <br>|
| Only-API Projects with Front-end like Vue.js |[Course: Vue.js + Laravel: CRUD with SPA](https://laraveldaily.teachable.com/p/vue-laravel-crud-spa) <br>|
| Only-API Projects with Mobile Apps |[Article: Using Sanctum to authenticate a mobile app](https://laravel-news.com/using-sanctum-to-authenticate-a-mobile-app) <br>|
| **(optional) Starter Kits: Laravel Jetstream and Fortify** ||
| Laravel Jetstream (requires Livewire/Inertia knowledge) |[Official Docs: Laravel Jetstream](https://jetstream.laravel.com) <br>[Course: Laravel Jetstream+Livewire: Real Mini-Project](https://laraveldaily.teachable.com/p/laravel-jetstream-livewire-project) <br>[Video: Laravel Jetstream: How it Works and Example How to Customize](https://www.youtube.com/watch?v=d8YgWApHMfA) <br>|
| Laravel Fortify |[Official Docs: Laravel Fortify](https://laravel.com/docs/8.x/fortify) <br>[Video: Laravel Fortify: Four Auth Things to Customize](https://www.youtube.com/watch?v=Vr4LJU3kw1g) <br>|
| **Payments** ||
| Laravel Cashier with Stripe/Paddle |[Official Docs: Laravel Cashier (Stripe)](https://laravel.com/docs/8.x/billing) <br>[Official Docs: Laravel Cashier (Paddle)](https://laravel.com/docs/8.x/cashier-paddle) <br>|
| Custom Payment Providers: PayPal, Mollie, etc |[Article: Subscription billing with Laravel Cashier for Mollie](https://github.com/laravel/cashier-mollie) <br>[Article: How To Integrate Paypal Payment Gateway In Laravel](https://websolutionstuff.com/post/how-to-integrate-paypal-payment-gateway-in-laravel) <br>|
| **Automated Testing Advanced** ||
| TDD: Test-Driven Development |[Course: Build A Laravel App With TDD](https://laracasts.com/series/build-a-laravel-app-with-tdd) <br>[Course: TDD With Laravel](https://tddwithlaravel.com/) <br>|
| Mocking |[Official Docs: Mocking](https://laravel.com/docs/8.x/mocking) <br>|
| (optional) Laravel Dusk |[Official Docs: Laravel Dusk](https://laravel.com/docs/8.x/dusk) <br>|
| **Full-Text Search** ||
| Laravel Scout |[Official Docs: Laravel Scout](https://laravel.com/docs/8.x/scout) <br>|
| Drivers: ElasticSearch, Algolia or MeiliSearch |[Article: ElasticSearch Driver for Laravel Scout](https://laravel-news.com/explorer) <br>[Official Docs: Algolia: Scout Extended](https://www.algolia.com/doc/framework-integration/laravel/getting-started/introduction-to-scout-extended/?client=php) <br>[Article: Full-Text Search with MeiliSearch and Laravel Scout](https://tighten.co/blog/full-text-search-with-meilisearch-and-scout/) <br>|
| **Laravel Packages** ||
| Contributing to Packages, making Pull Requests |[Video: How to Contribute to Laravel Docs (or any open-source repository)](https://www.youtube.com/watch?v=vEcT6JIFji0) <br>|
| Create Laravel Packages |[Official Docs: Package Development](https://laravel.com/docs/8.x/packages) <br>[Course: Laravel Package Development](https://laravelpackage.com/) <br>|


## (TO BE DONE LATER) Senior Level


| Topic | Learning Links |
| ----- | ----- |


