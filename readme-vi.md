# Lộ trình học tập Laravel

Kho lưu trữ này chứa danh sách ** có thứ tự ** các chủ đề Laravel để tìm hiểu, từng bước, với các liên kết liên quan.

Nếu bạn muốn thêm chủ đề, liên kết hoặc bất kỳ đề xuất nào khác, vui lòng mở Vấn đề hoặc Yêu cầu kéo.

**Lưu ý 1**: The same table below is also available as a database, so you would be able to transform it to any other
format you want - PDF, chart, etc. See file [roadmap.sql](roadmap.sql)

**Lưu ý 2**: This content was filled into an adminpanel generated with
our [QuickAdminPanel](https://quickadminpanel.com) - here's
a [video demo of that process on Youtube](https://www.youtube.com/watch?v=i2ElUDUDRms). By purchasing QuickAdminPanel,
you support my free initiatives, like this Roadmap.

--- 

## Beginner Level

Create your very first simple Laravel project

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__

| Topic | Learning Links |
| ----- | ----- |
| **Routing and Controllers: Basics** ||
| Callback Functions and Route::view() |:book: [Basic Routing](https://laravel.com/docs/8.x/routing#basic-routing) <br>:book: [View Routes](https://laravel.com/docs/8.x/routing#view-routes) <br>|
| Routing to a Single Controller Method |:book: [Basic Controllers with Routes](https://laravel.com/docs/8.x/controllers#basic-controllers) <br>|
| Route Parameters |:book: [Route Parameters](https://laravel.com/docs/8.x/routing#route-parameters) <br>|
| Route Naming |:book: [Names Routes](https://laravel.com/docs/8.x/routing#named-routes) <br>|
| Route Groups |:book: [Route Groups](https://laravel.com/docs/8.x/routing#route-groups) <br>|
| **Blade Basics** ||
| Displaying Variables in Blade |:book: [Blade: Displaying Data](https://laravel.com/docs/8.x/blade#displaying-data) <br>|
| Blade If-Else and Loop Structures |:book: [Blade: If-Statements](https://laravel.com/docs/8.x/blade#if-statements) <br>:book: [Blade Loops](https://laravel.com/docs/8.x/blade#loops) <br>|
| Layout: @include, @extends, @section, @yield |:book: [Blade: Layout Using Template Inheritance](https://laravel.com/docs/8.x/blade#layouts-using-template-inheritance) <br>|
| Blade Components |:book: [Blade Components](https://laravel.com/docs/8.x/blade#components) <br>:clapper: [Laravel Blade Components: Two Examples - Laravel Breeze/UI](https://www.youtube.com/watch?v=HybWBINeXMw) <br>|
| **Auth Basics** ||
| Starter Kits: Breeze (Tailwind) or Laravel UI (Bootstrap) |:book: [Laravel Breeze Official Documentation](https://laravel.com/docs/8.x/starter-kits#laravel-breeze) <br>:book: [Laravel UI: Official Github Page](https://github.com/laravel/ui) <br>|
| Default Auth Model and Access its Fields from Anywhere |:book: [Retrieving the Authenticated User](https://laravel.com/docs/8.x/authentication#retrieving-the-authenticated-user) <br>|
| Check Auth in Controller / Blade |:book: [Determining If The Current User Is Authenticated](https://laravel.com/docs/8.x/authentication#determining-if-the-current-user-is-authenticated) <br>:book: [Blade: Authentication Directives](https://laravel.com/docs/8.x/blade#authentication-directives) <br>|
| Auth Middleware |:book: [Protecting Routes](https://laravel.com/docs/8.x/authentication#protecting-routes) <br>|
| **Database Basics** ||
| Database Migrations |:book: [Database Migrations](https://laravel.com/docs/8.x/migrations) <br>|
| Basic Eloquent Model and MVC: Controller -> Model -> View |:book: [Eloquent: Getting Started](https://laravel.com/docs/8.x/eloquent) <br>|
| Eloquent Relationships: belongsTo / hasMany / belongsToMany |:book: [Eloquent Relationships: One-to-Many](https://laravel.com/docs/8.x/eloquent-relationships#one-to-many) <br>:book: [Eloquent Relationships: BelongsTo](https://laravel.com/docs/8.x/eloquent-relationships#one-to-many-inverse) <br>:book: [Eloquent Relationships: Many-to-Many](https://laravel.com/docs/8.x/eloquent-relationships#many-to-many) <br>|
| Eager Loading and N+1 Query Problem |:book: [Relationships: Eager Loading](https://laravel.com/docs/8.x/eloquent-relationships#eager-loading) <br>|
| **Full Simple CRUD** ||
| Route Resource and Resourceful Controllers |:book: [Laravel Resource Controllers](https://laravel.com/docs/8.x/controllers#resource-controllers) <br>:page_facing_up: [Simple Laravel CRUD with Resource Controllers [digitalocean.com]](https://www.digitalocean.com/community/tutorials/simple-laravel-crud-with-resource-controllers) <br>|
| Forms, Validation and Form Requests |:book: [Laravel Validation](https://laravel.com/docs/8.x/validation) <br>|
| File Uploads and Storage Folder Basics |:book: [Filesystem: File Uploads](https://laravel.com/docs/8.x/filesystem#file-uploads) <br>|
| Table Pagination |:book: [Database Pagination](https://laravel.com/docs/8.x/pagination) <br>|

## Advanced Beginner Level

The goal of this level is to find the first job or freelance gig

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__

| Topic | Learning Links |
| ----- | ----- |
| **Routing Advanced** ||
| Route Model Binding |:book: [Route Model Binding](https://laravel.com/docs/8.x/routing#route-model-binding) <br>:clapper: [Laravel Route Model Binding: All You Need To Know](https://www.youtube.com/watch?v=6dEfxGLgevM) <br>|
| Route Redirect |:book: [Redirect Routes](https://laravel.com/docs/8.x/routing#redirect-routes) <br>|
| **Middleware** ||
| Create Custom Middleware Class |:book: [Defining Middleware](https://laravel.com/docs/8.x/middleware#defining-middleware) <br>|
| **Database Advanced** ||
| Database Seeders and Factories |:book: [Database: Seeding](https://laravel.com/docs/8.x/seeding) <br>:book: [Defining Model Factories](https://laravel.com/docs/8.x/database-testing#defining-model-factories) <br>|
| Eloquent Query Scopes |:book: [Eloquent: Query Scopes](https://laravel.com/docs/8.x/eloquent#query-scopes) <br>|
| Polymorphic relationships |:book: [Polymorphic Relationships](https://laravel.com/docs/8.x/eloquent-relationships#polymorphic-relationships) <br>|
| Eloquent Accessors and Mutators |:book: [Accessors & Mutators](https://laravel.com/docs/8.x/eloquent-mutators#accessors-and-mutators) <br>|
| Eloquent Collections |:book: [Eloquent Collections](https://laravel.com/docs/8.x/eloquent-collections) <br>:book: [General Laravel Collections](https://laravel.com/docs/8.x/collections) <br>|
| Soft Deletes |:book: [Soft Deleting](https://laravel.com/docs/8.x/eloquent#soft-deleting) <br>|
| **Auth Advanced** ||
| Authorization: Roles/Permissions, Gates, Policies |:book: [Authorization](https://laravel.com/docs/8.x/authorization) <br>:clapper: [Laravel Roles and Permissions: All CORE Things You Need To Know](https://www.youtube.com/watch?v=kZOgH3-0Bko) <br>|
| Authorization: Extra Packages - Spatie Permission, Bouncer, etc |:clapper: [Spatie Laravel Permission: Example Project Review](https://www.youtube.com/watch?v=NgToi0uiMNQ) <br>:page_facing_up: [Two Best Laravel Packages to Manage Roles/Permissions](https://laravel-news.com/two-best-roles-permissions-packages) <br>:book: [spatie/laravel-permission](https://github.com/spatie/laravel-permission) <br>:book: [JosephSilber/bouncer](https://github.com/JosephSilber/bouncer) <br>|
| Authentication: Email Verification |:book: [Email Verification](https://laravel.com/docs/8.x/verification) <br>|
| **File Uploads Advanced** ||
| Drivers and Disks, Example of Amazon S3 |:book: [File Storage](https://laravel.com/docs/8.x/filesystem) <br>:clapper: [Laravel: How to Upload Files to Amazon S3](https://www.youtube.com/watch?v=xZQM9q_QxMA) <br>|
| Extra Packages: Spatie Medialibrary, Intervention Image, etc |:book: [spatie/laravel-medialibrary](https://github.com/spatie/laravel-medialibrary) <br>:book: [intervention/image](https://github.com/Intervention/image) <br>|
| **API Basics** ||
| API Routes and Controllers |:book: [API Resource Routes](https://laravel.com/docs/8.x/controllers#api-resource-routes) <br>:book: [Default Route Files](https://laravel.com/docs/8.x/routing#the-default-route-files) <br>|
| Working with API Clients: Postman or Alternatives |:book: [Postman API Client](https://www.postman.com/product/api-client/) <br>|
| API Eloquent Resources |:book: [Eloquent: API Resources](https://laravel.com/docs/8.x/eloquent-resources) <br>|
| API Auth with Sanctum |:book: [Laravel Sanctum](https://laravel.com/docs/8.x/sanctum) <br>|
| API Error Handling and Status Codes |:clapper: [Laravel API 404 Error: Customize Exception Message](https://www.youtube.com/watch?v=SlBJrLnyoMk) <br>:page_facing_up: [HTTP Status Codes](https://httpstatuses.com/) <br>|
| **Debugging Errors** ||
| Log Files in Laravel |:book: [Logging](https://laravel.com/docs/8.x/logging) <br>|
| Try-Catch and Laravel Exceptions |:book: [Error Handling](https://laravel.com/docs/8.x/errors) <br>:clapper: [Exceptions in Laravel: Why/How to Use and Create Your Own](https://www.youtube.com/watch?v=RTTXZVIL6tw) <br>|
| Local Debugging Tools: Debugbar, Telescope, Ray |:book: [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) <br>:book: [Laravel Telescope](https://laravel.com/docs/8.x/telescope) <br>:book: [Spatie Ray (Premium Tool)](https://myray.app/) <br>:clapper: [Debug Eloquent Queries from API: Laravel Telescope](https://www.youtube.com/watch?v=SR3RzIfeozI) <br>:clapper: [Spatie Ray: Laravel Debugging with Pleasure](https://www.youtube.com/watch?v=n4pMxyAXeqY) <br>|
| Customizing Error Pages and Messages |:book: [Custom HTTP Error Pages](https://laravel.com/docs/8.x/errors#custom-http-error-pages) <br>:clapper: [Laravel Error Pages: Change Text or Customize Layouts](https://www.youtube.com/watch?v=iMAFUi6Z57k) <br>|
| (optional) Third Party Bug Trackers: Bugsnag, Flare, Sentry, Rollbar |:book: [Bugsnag Laravel](https://docs.bugsnag.com/platforms/php/laravel/) <br>:book: [Flare Homepage](https://flareapp.io/) <br>:book: [Sentry Laravel](https://docs.sentry.io/platforms/php/guides/laravel/) <br>:book: [Rollbar Laravel](https://docs.rollbar.com/docs/laravel) <br>:clapper: [Bug Tracking in Laravel: Bugsnag vs Flare [Demo/Review]](https://www.youtube.com/watch?v=88UqUXhWwGA) <br>|
| **Sending Email** ||
| Mailables and Mail Facade |:book: [Mail & Mailables](https://laravel.com/docs/8.x/mail) <br>|
| Configure Drivers/Services: Mailgun, Mailtrap, etc |:page_facing_up: [How to Send Email From Laravel, and Why We Need 3rd Party Providers For It](https://laraveldaily.com/how-to-send-email-from-laravel-and-why-we-need-3rd-party-providers-for-it/) <br>:book: [Mail: Drivers Prerequisites](https://laravel.com/docs/8.x/mail#driver-prerequisites) <br>|
| Notifications System: Email, SMS, Slack, etc. |:book: [Notifications](https://laravel.com/docs/8.x/notifications) <br>|
| **Automated Testing with PHPUnit** ||
| "Smoke" Tests to Check if Pages are Loading |:book: [Testing: Getting Started](https://laravel.com/docs/8.x/testing) <br>:capital_abcd: [Laravel: PHPUnit Testing for Beginners](https://laraveldaily.teachable.com/p/laravel-phpunit-testing-for-beginners) <br>|
| Configure Testing Database and Test CRUD Operations |:book: [Database Testing](https://laravel.com/docs/8.x/database-testing) <br>|
| **Deployment and Version Control** ||
| Git Version Control |:book: [Git](https://git-scm.com/) <br>:clapper: [Git in Laravel. Part 1 - Branches: Main, Develop and Feature](https://www.youtube.com/watch?v=AmScEC-_72I) <br>|
| Deployment on Live Servers |:book: [Deployment](https://laravel.com/docs/8.x/deployment) <br>:page_facing_up: [How to Deploy Laravel Projects to Live Server: The Ultimate Guide](https://laraveldaily.com/how-to-deploy-laravel-projects-to-live-server-the-ultimate-guide/) <br>:page_facing_up: [What Server is Needed to Deploy Laravel Projects](https://laraveldaily.com/what-server-is-needed-to-deploy-laravel-projects/) <br>:clapper: [How we Deploy Laravel: Branches, Staging Servers, Forge and Envoyer](https://www.youtube.com/watch?v=8DVuVftFZcQ) <br>|

## Mid Level

Master all Laravel features with 3-5 years of practical experience

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__

| Topic | Learning Links |
| ----- | ----- |
| **Routing Extra Features** ||
| Route Caching |:book: [Route Caching](https://laravel.com/docs/8.x/routing#route-caching) <br>|
| Rate Limiting |:book: [Rate Limiting](https://laravel.com/docs/8.x/routing#rate-limiting) <br>:clapper: [Laravel: Create Public API with Cache and Rate Limits](https://www.youtube.com/watch?v=vrLcCxWlxOk) <br>|
| Invokable controllers |:book: [Single Action Controllers](https://laravel.com/docs/8.x/controllers#single-action-controllers) <br>|
| **Database/Eloquent Extra Features** ||
| Model Observers |:book: [Eloquent Observers](https://laravel.com/docs/8.x/eloquent#observers) <br>:clapper: [Laravel Model: Check if Any Field Was Changed](https://www.youtube.com/watch?v=_xluet13xxE) <br>:clapper: [Eloquent Observers or Events Listeners? Which is Better?](https://www.youtube.com/watch?v=DvoaU6cQQHM) <br>|
| Raw Database Queries |:book: [Query Builder: Raw Expressions](https://laravel.com/docs/8.x/queries#raw-expressions) <br>|
| All Eloquent Features |:book: [All About Eloquent](https://laravel.com/docs/8.x/eloquent) <br>:capital_abcd: [Eloquent: Expert Level](https://laraveldaily.teachable.com/p/laravel-eloquent-expert-level) <br>:page_facing_up: [20 Laravel Eloquent Tips and Tricks](https://laravel-news.com/eloquent-tips-tricks) <br>|
| **Various Extra Laravel Features** ||
| Custom Blade Directives |:book: [Extending Blade](https://laravel.com/docs/8.x/blade#extending-blade) <br>|
| Events and Listeners |:book: [Events and Listeners](https://laravel.com/docs/8.x/events) <br>:clapper: [Laravel: 3 Ways to Send a Welcome Email (Controller vs Observer vs Events)](https://www.youtube.com/watch?v=ZWzH6SOzjhI) <br>:clapper: [Laravel: Why Observers and Event Listeners are "Risky"](https://www.youtube.com/watch?v=A3bmLo77e5M) <br>|
| Laravel HTTP Client and Guzzle |:book: [HTTP Client](https://laravel.com/docs/8.x/http-client) <br>:clapper: [Laravel and External APIs: Get Data with HTTP Client](https://www.youtube.com/watch?v=oEDDZsmMLc0) <br>|
| Login with X: Laravel Socialite |:book: [Laravel Socialite](https://laravel.com/docs/8.x/socialite) <br>|
| Creating Artisan Commands |:book: [Writing Artisan Commands](https://laravel.com/docs/8.x/artisan#writing-commands) <br>:clapper: [How to Create Artisan Commands in Laravel](https://www.youtube.com/watch?v=-r3WnYy7g48) <br>|
| Task Scheduling |:book: [Task Scheduling](https://laravel.com/docs/8.x/scheduling) <br>|
| Caching |:book: [Cache](https://laravel.com/docs/8.x/cache) <br>:clapper: [Cache Eloquent Query Results to Load Pages Instantly](https://www.youtube.com/watch?v=JhKngeE0XJA) <br>|
| Real-time: Broadcasting, Echo and Pusher |:book: [Broadcasting](https://laravel.com/docs/8.x/broadcasting) <br>|
| **Jobs and Queues** |:capital_abcd: [Queues in Laravel](https://laraveldaily.teachable.com/p/queues-in-laravel) <br>|
| Queueable Classes and Jobs |:book: [Creating Jobs](https://laravel.com/docs/8.x/queues#creating-jobs) <br>:book: [Queueing Notifications](https://laravel.com/docs/8.x/notifications#queueing-notifications) <br>:book: [Queued Event Listeners](https://laravel.com/docs/8.x/events#queued-event-listeners) <br>:book: [Queueing Mail](https://laravel.com/docs/8.x/mail#queueing-mail) <br>:clapper: [Laravel Queues 101: Example with Sending Emails](https://www.youtube.com/watch?v=rVx8xKisbr8) <br>|
| Job Dispatching, Batching and Chaining |:book: [Dispatching Jobs](https://laravel.com/docs/8.x/queues#dispatching-jobs) <br>|
| Processing Failed Jobs |:book: [Dealing with Failed Jobs](https://laravel.com/docs/8.x/queues#dealing-with-failed-jobs) <br>|
| Configuring Queues: Drivers, Redis, Supervisor |:book: [Running the Queue Worker](https://laravel.com/docs/8.x/queues#running-the-queue-worker) <br>:book: [Configuring Supervisor](https://laravel.com/docs/8.x/queues#supervisor-configuration) <br>|
| Laravel Horizon (optional, if you use Redis) |:book: [Laravel Horizon](https://laravel.com/docs/8.x/horizon) <br>|
| **API Advanced** ||
| Upload Files via API |:page_facing_up: [Laravel API: How to Upload File from Vue.js](https://blog.quickadminpanel.com/laravel-api-how-to-upload-file-from-vue-js/) <br>|
| Generate API Documentation |:page_facing_up: [Laravel API Documentation with OpenAPI/Swagger](https://blog.quickadminpanel.com/laravel-api-documentation-with-openapiswagger/) <br>:clapper: [Scribe: New Package for Laravel API Documentation](https://www.youtube.com/watch?v=PjwGI8c2IfA) <br>|
| API Versioning |:page_facing_up: [Versioning your REST API with Laravel](https://codimth.com/blog/web/laravel/versioning-your-rest-api-laravel) <br>:clapper: [Versioning your API: from V1 to V2 and Beyond [video from my course]](https://laraveldaily.teachable.com/courses/how-to-create-laravel-api/lectures/17568998) <br>|
| Only-API Projects with Front-end like Vue.js |:capital_abcd: [Vue.js + Laravel: CRUD with SPA](https://laraveldaily.teachable.com/p/vue-laravel-crud-spa) <br>|
| Only-API Projects with Mobile Apps |:page_facing_up: [Using Sanctum to authenticate a mobile app](https://laravel-news.com/using-sanctum-to-authenticate-a-mobile-app) <br>|
| **(optional) Starter Kits: Laravel Jetstream and Fortify** ||
| Laravel Jetstream (requires Livewire/Inertia knowledge) |:book: [Laravel Jetstream](https://jetstream.laravel.com) <br>:capital_abcd: [Laravel Jetstream+Livewire: Real Mini-Project](https://laraveldaily.teachable.com/p/laravel-jetstream-livewire-project) <br>:clapper: [Laravel Jetstream: How it Works and Example How to Customize](https://www.youtube.com/watch?v=d8YgWApHMfA) <br>|
| Laravel Fortify |:book: [Laravel Fortify](https://laravel.com/docs/8.x/fortify) <br>:clapper: [Laravel Fortify: Four Auth Things to Customize](https://www.youtube.com/watch?v=Vr4LJU3kw1g) <br>|
| **Payments** ||
| Laravel Cashier with Stripe/Paddle |:book: [Laravel Cashier (Stripe)](https://laravel.com/docs/8.x/billing) <br>:book: [Laravel Cashier (Paddle)](https://laravel.com/docs/8.x/cashier-paddle) <br>|
| Custom Payment Providers: PayPal, Mollie, etc |:page_facing_up: [Subscription billing with Laravel Cashier for Mollie](https://github.com/laravel/cashier-mollie) <br>:page_facing_up: [How To Integrate Paypal Payment Gateway In Laravel](https://websolutionstuff.com/post/how-to-integrate-paypal-payment-gateway-in-laravel) <br>|
| **Automated Testing Advanced** ||
| TDD: Test-Driven Development |:capital_abcd: [Build A Laravel App With TDD](https://laracasts.com/series/build-a-laravel-app-with-tdd) <br>:capital_abcd: [TDD With Laravel](https://tddwithlaravel.com/) <br>|
| Mocking |:book: [Mocking](https://laravel.com/docs/8.x/mocking) <br>|
| (optional) Laravel Dusk |:book: [Laravel Dusk](https://laravel.com/docs/8.x/dusk) <br>|
| **Full-Text Search** ||
| Laravel Scout |:book: [Laravel Scout](https://laravel.com/docs/8.x/scout) <br>|
| Drivers: ElasticSearch, Algolia or MeiliSearch |:page_facing_up: [ElasticSearch Driver for Laravel Scout](https://laravel-news.com/explorer) <br>:book: [Algolia: Scout Extended](https://www.algolia.com/doc/framework-integration/laravel/getting-started/introduction-to-scout-extended/?client=php) <br>:page_facing_up: [Full-Text Search with MeiliSearch and Laravel Scout](https://tighten.co/blog/full-text-search-with-meilisearch-and-scout/) <br>|
| **Laravel Packages** ||
| Contributing to Packages, making Pull Requests |:clapper: [How to Contribute to Laravel Docs (or any open-source repository)](https://www.youtube.com/watch?v=vEcT6JIFji0) <br>|
| Create Laravel Packages |:book: [Package Development](https://laravel.com/docs/8.x/packages) <br>:capital_abcd: [Laravel Package Development](https://laravelpackage.com/) <br>|

## Senior Level

Responsibility for architecture decisions on large projects

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__

| Topic | Learning Links |
| ----- | ----- |
| **PHP/Laravel Design
Patterns** |:clapper: [Laravel Design Patterns - Bobby Bouwmann - Laracon EU 2018 Amsterdam](https://www.youtube.com/watch?v=qpo5KG0vIyE) <br>:capital_abcd: [Laracasts: Design Patterns in PHP](https://laracasts.com/series/design-patterns-in-php) <br>:clapper: [Colin Decarlo - Design Patterns with Laravel [Laracon 2018]](https://www.youtube.com/watch?v=e4ugSgGaCQ0) <br>:clapper: [Matt Stauffer - Patterns That Pay Off [Laracon 2018]](https://www.youtube.com/watch?v=enTb2E4vEos) <br>:capital_abcd: [Design Patterns in PHP](https://refactoring.guru/design-patterns/php) <br>|
| Creational Design Patterns |:page_facing_up: [Design Patterns PHP: Creational](https://designpatternsphp.readthedocs.io/en/latest/Creational/README.html) <br>|
| Structural Design Patterns |:page_facing_up: [Design Patterns PHP: Structural](https://designpatternsphp.readthedocs.io/en/latest/Structural/README.html) <br>|
| Behavioral Design Patterns |:page_facing_up: [Design Patterns PHP: Behavioral](https://designpatternsphp.readthedocs.io/en/latest/Behavioral/README.html) <br>|
| **Well-written Code** ||
| SOLID Code |:clapper: [Becoming a better developer by using the SOLID design principles by Katerina Trajchevska](https://www.youtube.com/watch?v=rtmFCcjEgEw) <br>:page_facing_up: [Writing Maintainable Code: SOLID Principles Explained in PHP (Laravel)](https://geekflare.com/php-solid-principles/) <br>:capital_abcd: [Laracasts: SOLID Principles in PHP](https://laracasts.com/series/solid-principles-in-php) <br>:clapper: [PHP Solid Principles [Playlist]](https://www.youtube.com/watch?v=ARxZV8OZ8Cg&list=PLNuh5_K9dfQ3jMU-2C2jYRGe2iXJkpCZj) <br>|
| Scalable Code ||
| Maintainable Code ||
| Reusable Code ||
| Best Practices and Standards ||
| **Large Datasets** ||
| Large Database Structures ||
| NoSQL Solutions ||
| SQL Query Optimization ||
| Scaling to Multiple Databases ||
| **Working with High-Traffic Projects** ||
| Stability and Zero-Downtime Deployments ||
| Performance Optimization and Caching ||
| **Ensuring Code Quality** ||
| Writing Testable Code ||
| Automated Testing: Process Optimization ||
| Continuous Integration and Continuous Delivery (CI/CD) ||