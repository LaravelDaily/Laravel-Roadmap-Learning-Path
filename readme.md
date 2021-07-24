# Laravel Learning Path

This repository contains the **ordered** list of Laravel topics to learn, step-by-step, with related links.

If you want to add a topic, link, or any other suggestion, please open Issues or Pull Requests.

**Notice 1**: The same table below is also available as a database, so you would be able to transform it to any other format you want - PDF, chart, etc. See file [roadmap.sql](roadmap.sql)

**Notice 2**: This content was filled into an adminpanel generated with our [QuickAdminPanel](https://quickadminpanel.com) - here's a [video demo of that process on Youtube](https://www.youtube.com/watch?v=i2ElUDUDRms). By purchasing QuickAdminPanel, you support my free initiatives, like this Roadmap.

**Key**:<br>📖 [Official Docs](https://laravel.com/docs)<br>🎬 Videos<br>📰 Article

--- 

## Beginner Level
Create your very first simple Laravel project

| Topic | Learning Links |
| ----- | ----- |
| **Routing and Controllers: Basics** | |
| Callback Functions and Route::view() |📖 [Basic Routing](https://laravel.com/docs/8.x/routing#basic-routing) <br>📖 [View Routes](https://laravel.com/docs/8.x/routing#view-routes) <br>|
| Routing to a Single Controller Method |📖 [Basic Controllers with Routes](https://laravel.com/docs/8.x/controllers#basic-controllers) <br>|
| Route Parameters |📖 [Route Parameters](https://laravel.com/docs/8.x/routing#route-parameters) <br>|
| Route Naming |📖 [Names Routes](https://laravel.com/docs/8.x/routing#named-routes) <br>|
| Route Groups |📖 [Route Groups](https://laravel.com/docs/8.x/routing#route-groups) <br>|
| **Blade Basics** ||
| Displaying Variables in Blade |📖 [Blade: Displaying Data](https://laravel.com/docs/8.x/blade#displaying-data) <br>|
| Blade If-Else and Loop Structures |📖 [Blade: If-Statements](https://laravel.com/docs/8.x/blade#if-statements) <br>📖 [Blade Loops](https://laravel.com/docs/8.x/blade#loops) <br>|
| Layout: @include, @extends, @section, @yield |📖 [Blade: Layout Using Template Inheritance](https://laravel.com/docs/8.x/blade#layouts-using-template-inheritance) <br>|
| Blade Components |📖 [Blade Components](https://laravel.com/docs/8.x/blade#components) <br>🎬 [Laravel Blade Components: Two Examples - Laravel Breeze/UI](https://www.youtube.com/watch?v=HybWBINeXMw) <br>|
| **Auth Basics** ||
| Starter Kits: Breeze (Tailwind) or Laravel UI (Bootstrap) |📖 [Laravel Breeze Official Documentation](https://laravel.com/docs/8.x/starter-kits#laravel-breeze) <br>📖 [Laravel UI: Official Github Page](https://github.com/laravel/ui) <br>|
| Default Auth Model and Access its Fields from Anywhere |📖 [Retrieving the Authenticated User](https://laravel.com/docs/8.x/authentication#retrieving-the-authenticated-user) <br>|
| Check Auth in Controller / Blade |📖 [Determining If The Current User Is Authenticated](https://laravel.com/docs/8.x/authentication#determining-if-the-current-user-is-authenticated) <br>📖 [Blade: Authentication Directives](https://laravel.com/docs/8.x/blade#authentication-directives) <br>|
| Auth Middleware |📖 [Protecting Routes](https://laravel.com/docs/8.x/authentication#protecting-routes) <br>|
| **Database Basics** ||
| Database Migrations |📖 [Database Migrations](https://laravel.com/docs/8.x/migrations) <br>|
| Basic Eloquent Model and MVC: Controller -> Model -> View |📖 [Eloquent: Getting Started](https://laravel.com/docs/8.x/eloquent) <br>|
| Eloquent Relationships: belongsTo / hasMany / belongsToMany |📖 [Eloquent Relationships: One-to-Many](https://laravel.com/docs/8.x/eloquent-relationships#one-to-many) <br>📖 [Eloquent Relationships: BelongsTo](https://laravel.com/docs/8.x/eloquent-relationships#one-to-many-inverse) <br>📖 [Eloquent Relationships: Many-to-Many](https://laravel.com/docs/8.x/eloquent-relationships#many-to-many) <br>|
| Eager Loading and N+1 Query Problem |📖 [Relationships: Eager Loading](https://laravel.com/docs/8.x/eloquent-relationships#eager-loading) <br>|
| **Full Simple CRUD** ||
| Route Resource and Resourceful Controllers |📖 [Laravel Resource Controllers](https://laravel.com/docs/8.x/controllers#resource-controllers) <br>📰 [Simple Laravel CRUD with Resource Controllers [digitalocean.com]](https://www.digitalocean.com/community/tutorials/simple-laravel-crud-with-resource-controllers) <br>|
| Forms, Validation and Form Requests |📖 [Laravel Validation](https://laravel.com/docs/8.x/validation) <br>|
| File Uploads and Storage Folder Basics |📖 [Filesystem: File Uploads](https://laravel.com/docs/8.x/filesystem#file-uploads) <br>|
| Table Pagination |📖 [Database Pagination](https://laravel.com/docs/8.x/pagination) <br>|


## Advanced Beginner Level
The goal of this level is to find the first job or freelance gig

| Topic | Learning Links |
| ----- | ----- |
| **Routing Advanced** ||
| Route Model Binding |📖 [Route Model Binding](https://laravel.com/docs/8.x/routing#route-model-binding) <br>🎬 [Laravel Route Model Binding: All You Need To Know](https://www.youtube.com/watch?v=6dEfxGLgevM) <br>|
| Route Redirect |📖 [Redirect Routes](https://laravel.com/docs/8.x/routing#redirect-routes) <br>|
| **Middleware** ||
| Create Custom Middleware Class |📖 [Defining Middleware](https://laravel.com/docs/8.x/middleware#defining-middleware) <br>|
| **Database Advanced** ||
| Database Seeders and Factories |📖 [Database: Seeding](https://laravel.com/docs/8.x/seeding) <br>📖 [Defining Model Factories](https://laravel.com/docs/8.x/database-testing#defining-model-factories) <br>|
| Eloquent Query Scopes |📖 [Eloquent: Query Scopes](https://laravel.com/docs/8.x/eloquent#query-scopes) <br>|
| Polymorphic relationships |📖 [Polymorphic Relationships](https://laravel.com/docs/8.x/eloquent-relationships#polymorphic-relationships) <br>|
| Eloquent Accessors and Mutators |📖 [Accessors & Mutators](https://laravel.com/docs/8.x/eloquent-mutators#accessors-and-mutators) <br>|
| Eloquent Collections |📖 [Eloquent Collections](https://laravel.com/docs/8.x/eloquent-collections) <br>📖 [General Laravel Collections](https://laravel.com/docs/8.x/collections) <br>|
| Soft Deletes |📖 [Soft Deleting](https://laravel.com/docs/8.x/eloquent#soft-deleting) <br>|
| **Auth Advanced** ||
| Authorization: Roles/Permissions, Gates, Policies |📖 [Authorization](https://laravel.com/docs/8.x/authorization) <br>🎬 [Laravel Roles and Permissions: All CORE Things You Need To Know](https://www.youtube.com/watch?v=kZOgH3-0Bko) <br>|
| Authorization: Extra Packages - Spatie Permission, Bouncer, etc |🎬 [Spatie Laravel Permission: Example Project Review](https://www.youtube.com/watch?v=NgToi0uiMNQ) <br>📰 [Two Best Laravel Packages to Manage Roles/Permissions](https://laravel-news.com/two-best-roles-permissions-packages) <br>📖 [spatie/laravel-permission](https://github.com/spatie/laravel-permission) <br>📖 [JosephSilber/bouncer](https://github.com/JosephSilber/bouncer) <br>|
| Authentication: Email Verification |📖 [Email Verification](https://laravel.com/docs/8.x/verification) <br>|
| **File Uploads Advanced** ||
| Drivers and Disks, Example of Amazon S3 |📖 [File Storage](https://laravel.com/docs/8.x/filesystem) <br>🎬 [Laravel: How to Upload Files to Amazon S3](https://www.youtube.com/watch?v=xZQM9q_QxMA) <br>|
| Extra Packages: Spatie Medialibrary, Intervention Image, etc |📖 [spatie/laravel-medialibrary](https://github.com/spatie/laravel-medialibrary) <br>📖 [intervention/image](https://github.com/Intervention/image) <br>|
| **API Basics** ||
| API Routes and Controllers |📖 [API Resource Routes](https://laravel.com/docs/8.x/controllers#api-resource-routes) <br>📖 [Default Route Files](https://laravel.com/docs/8.x/routing#the-default-route-files) <br>|
| Working with API Clients: Postman or Alternatives |📖 [Postman API Client](https://www.postman.com/product/api-client/) <br>|
| API Eloquent Resources |📖 [Eloquent: API Resources](https://laravel.com/docs/8.x/eloquent-resources) <br>|
| API Auth with Sanctum |📖 [Laravel Sanctum](https://laravel.com/docs/8.x/sanctum) <br>|
| API Error Handling and Status Codes |🎬 [Laravel API 404 Error: Customize Exception Message](https://www.youtube.com/watch?v=SlBJrLnyoMk) <br>📰 [HTTP Status Codes](https://httpstatuses.com/) <br>|
| **Debugging Errors** ||
| Log Files in Laravel |📖 [Logging](https://laravel.com/docs/8.x/logging) <br>|
| Try-Catch and Laravel Exceptions |📖 [Error Handling](https://laravel.com/docs/8.x/errors) <br>🎬 [Exceptions in Laravel: Why/How to Use and Create Your Own](https://www.youtube.com/watch?v=RTTXZVIL6tw) <br>|
| Local Debugging Tools: Debugbar, Telescope, Ray |📖 [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) <br>📖 [Laravel Telescope](https://laravel.com/docs/8.x/telescope) <br>📖 [Spatie Ray (Premium Tool)](https://myray.app/) <br>🎬 [Debug Eloquent Queries from API: Laravel Telescope](https://www.youtube.com/watch?v=SR3RzIfeozI) <br>🎬 [Spatie Ray: Laravel Debugging with Pleasure](https://www.youtube.com/watch?v=n4pMxyAXeqY) <br>|
| Customizing Error Pages and Messages |📖 [Custom HTTP Error Pages](https://laravel.com/docs/8.x/errors#custom-http-error-pages) <br>🎬 [Laravel Error Pages: Change Text or Customize Layouts](https://www.youtube.com/watch?v=iMAFUi6Z57k) <br>|
| (optional) Third Party Bug Trackers: Bugsnag, Flare, Sentry, Rollbar |📖 [Bugsnag Laravel](https://docs.bugsnag.com/platforms/php/laravel/) <br>📖 [Flare Homepage](https://flareapp.io/) <br>📖 [Sentry Laravel](https://docs.sentry.io/platforms/php/guides/laravel/) <br>📖 [Rollbar Laravel](https://docs.rollbar.com/docs/laravel) <br>🎬 [Bug Tracking in Laravel: Bugsnag vs Flare [Demo/Review]](https://www.youtube.com/watch?v=88UqUXhWwGA) <br>|
| **Sending Email** ||
| Mailables and Mail Facade |📖 [Mail & Mailables](https://laravel.com/docs/8.x/mail) <br>|
| Configure Drivers/Services: Mailgun, Mailtrap, etc |📰 [How to Send Email From Laravel, and Why We Need 3rd Party Providers For It](https://laraveldaily.com/how-to-send-email-from-laravel-and-why-we-need-3rd-party-providers-for-it/) <br>📖 [Mail: Drivers Prerequisites](https://laravel.com/docs/8.x/mail#driver-prerequisites) <br>|
| Notifications System: Email, SMS, Slack, etc. |📖 [Notifications](https://laravel.com/docs/8.x/notifications) <br>|
| **Automated Testing with PHPUnit** ||
| "Smoke" Tests to Check if Pages are Loading |📖 [Testing: Getting Started](https://laravel.com/docs/8.x/testing) <br>[Course: Laravel: PHPUnit Testing for Beginners](https://laraveldaily.teachable.com/p/laravel-phpunit-testing-for-beginners) <br>|
| Configure Testing Database and Test CRUD Operations |📖 [Database Testing](https://laravel.com/docs/8.x/database-testing) <br>|
| **Deployment and Version Control** ||
| Git Version Control |📖 [Git](https://git-scm.com/) <br>🎬 [Git in Laravel. Part 1 - Branches: Main, Develop and Feature](https://www.youtube.com/watch?v=AmScEC-_72I) <br>|
| Deployment on Live Servers |📖 [Deployment](https://laravel.com/docs/8.x/deployment) <br>📰 [How to Deploy Laravel Projects to Live Server: The Ultimate Guide](https://laraveldaily.com/how-to-deploy-laravel-projects-to-live-server-the-ultimate-guide/) <br>📰 [What Server is Needed to Deploy Laravel Projects](https://laraveldaily.com/what-server-is-needed-to-deploy-laravel-projects/) <br>🎬 [How we Deploy Laravel: Branches, Staging Servers, Forge and Envoyer](https://www.youtube.com/watch?v=8DVuVftFZcQ) <br>|


## Mid Level
Master all Laravel features with 3-5 years of practical experience

| Topic | Learning Links |
| ----- | ----- |
| **Routing Extra Features** ||
| Route Caching |📖 [Route Caching](https://laravel.com/docs/8.x/routing#route-caching) <br>|
| Rate Limiting |📖 [Rate Limiting](https://laravel.com/docs/8.x/routing#rate-limiting) <br>🎬 [Laravel: Create Public API with Cache and Rate Limits](https://www.youtube.com/watch?v=vrLcCxWlxOk) <br>|
| Invokable controllers |📖 [Single Action Controllers](https://laravel.com/docs/8.x/controllers#single-action-controllers) <br>|
| **Database/Eloquent Extra Features** ||
| Model Observers |📖 [Eloquent Observers](https://laravel.com/docs/8.x/eloquent#observers) <br>🎬 [Laravel Model: Check if Any Field Was Changed](https://www.youtube.com/watch?v=_xluet13xxE) <br>🎬 [Eloquent Observers or Events Listeners? Which is Better?](https://www.youtube.com/watch?v=DvoaU6cQQHM) <br>|
| Raw Database Queries |📖 [Query Builder: Raw Expressions](https://laravel.com/docs/8.x/queries#raw-expressions) <br>|
| All Eloquent Features |📖 [All About Eloquent](https://laravel.com/docs/8.x/eloquent) <br>[Course: Eloquent: Expert Level](https://laraveldaily.teachable.com/p/laravel-eloquent-expert-level) <br>📰 [20 Laravel Eloquent Tips and Tricks](https://laravel-news.com/eloquent-tips-tricks) <br>|
| **Various Extra Laravel Features** ||
| Caching |📖 [Cache](https://laravel.com/docs/8.x/cache) <br>🎬 [Cache Eloquent Query Results to Load Pages Instantly](https://www.youtube.com/watch?v=JhKngeE0XJA) <br>|
| Creating Artisan Commands |📖 [Writing Artisan Commands](https://laravel.com/docs/8.x/artisan#writing-commands) <br>🎬 [How to Create Artisan Commands in Laravel](https://www.youtube.com/watch?v=-r3WnYy7g48) <br>|
| Task Scheduling |📖 [Task Scheduling](https://laravel.com/docs/8.x/scheduling) <br>|
| Login with X: Laravel Socialite |📖 [Laravel Socialite](https://laravel.com/docs/8.x/socialite) <br>|
| Laravel HTTP Client and Guzzle |📖 [HTTP Client](https://laravel.com/docs/8.x/http-client) <br>🎬 [Laravel and External APIs: Get Data with HTTP Client](https://www.youtube.com/watch?v=oEDDZsmMLc0) <br>|
| Custom Blade Directives |📖 [Extending Blade](https://laravel.com/docs/8.x/blade#extending-blade) <br>|
| Events and Listeners |📖 [Events and Listeners](https://laravel.com/docs/8.x/events) <br>🎬 [Laravel: 3 Ways to Send a Welcome Email (Controller vs Observer vs Events)](https://www.youtube.com/watch?v=ZWzH6SOzjhI) <br>🎬 [Laravel: Why Observers and Event Listeners are "Risky"](https://www.youtube.com/watch?v=A3bmLo77e5M) <br>|
| **Jobs and Queues** |[Course: Queues in Laravel](https://laraveldaily.teachable.com/p/queues-in-laravel) <br>|
| Queueable Classes and Jobs |📖 [Creating Jobs](https://laravel.com/docs/8.x/queues#creating-jobs) <br>📖 [Queueing Notifications](https://laravel.com/docs/8.x/notifications#queueing-notifications) <br>📖 [Queued Event Listeners](https://laravel.com/docs/8.x/events#queued-event-listeners) <br>📖 [Queueing Mail](https://laravel.com/docs/8.x/mail#queueing-mail) <br>🎬 [Laravel Queues 101: Example with Sending Emails](https://www.youtube.com/watch?v=rVx8xKisbr8) <br>|
| Processing Failed Jobs |📖 [Dealing with Failed Jobs](https://laravel.com/docs/8.x/queues#dealing-with-failed-jobs) <br>|
| Job Dispatching, Batching and Chaining |📖 [Dispatching Jobs](https://laravel.com/docs/8.x/queues#dispatching-jobs) <br>|
| Configuring Queues: Drivers, Redis, Supervisor |📖 [Running the Queue Worker](https://laravel.com/docs/8.x/queues#running-the-queue-worker) <br>📖 [Configuring Supervisor](https://laravel.com/docs/8.x/queues#supervisor-configuration) <br>|
| Laravel Horizon (optional, if you use Redis) |📖 [Laravel Horizon](https://laravel.com/docs/8.x/horizon) <br>|
| **API Advanced** ||
| Upload Files via API |📰 [Laravel API: How to Upload File from Vue.js](https://blog.quickadminpanel.com/laravel-api-how-to-upload-file-from-vue-js/) <br>|
| Generate API Documentation |📰 [Laravel API Documentation with OpenAPI/Swagger](https://blog.quickadminpanel.com/laravel-api-documentation-with-openapiswagger/) <br>🎬 [Scribe: New Package for Laravel API Documentation](https://www.youtube.com/watch?v=PjwGI8c2IfA) <br>|
| API Versioning |📰 [Versioning your REST API with Laravel](https://codimth.com/blog/web/laravel/versioning-your-rest-api-laravel) <br>🎬 [Versioning your API: from V1 to V2 and Beyond [video from my course]](https://laraveldaily.teachable.com/courses/how-to-create-laravel-api/lectures/17568998) <br>|
| Only-API Projects with Front-end like Vue.js |[Course: Vue.js + Laravel: CRUD with SPA](https://laraveldaily.teachable.com/p/vue-laravel-crud-spa) <br>|
| Only-API Projects with Mobile Apps |📰 [Using Sanctum to authenticate a mobile app](https://laravel-news.com/using-sanctum-to-authenticate-a-mobile-app) <br>|
| **(optional) Starter Kits: Laravel Jetstream and Fortify** ||
| Laravel Jetstream (requires Livewire/Inertia knowledge) |📖 [Laravel Jetstream](https://jetstream.laravel.com) <br>[Course: Laravel Jetstream+Livewire: Real Mini-Project](https://laraveldaily.teachable.com/p/laravel-jetstream-livewire-project) <br>🎬 [Laravel Jetstream: How it Works and Example How to Customize](https://www.youtube.com/watch?v=d8YgWApHMfA) <br>|
| Laravel Fortify |📖 [Laravel Fortify](https://laravel.com/docs/8.x/fortify) <br>🎬 [Laravel Fortify: Four Auth Things to Customize](https://www.youtube.com/watch?v=Vr4LJU3kw1g) <br>|
| **Payments** ||
| Laravel Cashier with Stripe/Paddle |📖 [Laravel Cashier (Stripe)](https://laravel.com/docs/8.x/billing) <br>📖 [Laravel Cashier (Paddle)](https://laravel.com/docs/8.x/cashier-paddle) <br>|
| Custom Payment Providers: PayPal, Mollie, etc |📰 [Subscription billing with Laravel Cashier for Mollie](https://github.com/laravel/cashier-mollie) <br>📰 [How To Integrate Paypal Payment Gateway In Laravel](https://websolutionstuff.com/post/how-to-integrate-paypal-payment-gateway-in-laravel) <br>|
| **Automated Testing Advanced** ||
| TDD: Test-Driven Development |[Course: Build A Laravel App With TDD](https://laracasts.com/series/build-a-laravel-app-with-tdd) <br>[Course: TDD With Laravel](https://tddwithlaravel.com/) <br>|
| Mocking |📖 [Mocking](https://laravel.com/docs/8.x/mocking) <br>|
| (optional) Laravel Dusk |📖 [Laravel Dusk](https://laravel.com/docs/8.x/dusk) <br>|
| **Full-Text Search** ||
| Laravel Scout |📖 [Laravel Scout](https://laravel.com/docs/8.x/scout) <br>|
| Drivers: ElasticSearch, Algolia or MeiliSearch |📰 [ElasticSearch Driver for Laravel Scout](https://laravel-news.com/explorer) <br>📖 [Algolia: Scout Extended](https://www.algolia.com/doc/framework-integration/laravel/getting-started/introduction-to-scout-extended/?client=php) <br>📰 [Full-Text Search with MeiliSearch and Laravel Scout](https://tighten.co/blog/full-text-search-with-meilisearch-and-scout/) <br>|
| **Laravel Packages** ||
| Contributing to Packages, making Pull Requests |🎬 [How to Contribute to Laravel Docs (or any open-source repository)](https://www.youtube.com/watch?v=vEcT6JIFji0) <br>|
| Create Laravel Packages |📖 [Package Development](https://laravel.com/docs/8.x/packages) <br>[Course: Laravel Package Development](https://laravelpackage.com/) <br>|


## (TO BE DONE LATER) Senior Level


| Topic | Learning Links |
| ----- | ----- |
