# Laravel Learning Path

This repository contains the **ordered** list of Laravel topics to learn, step-by-step, with related links.

If you want to add a topic, link, or any other suggestion, please open Issues or Pull Requests.

**Notice 1**: The same table below is also available as a database, so you would be able to transform it to any other format you want - PDF, chart, etc. See file [roadmap.sql](roadmap.sql)

**Notice 2**: This content was filled into an adminpanel generated with our [QuickAdminPanel](https://quickadminpanel.com) - here's a [video demo of that process on Youtube](https://www.youtube.com/watch?v=i2ElUDUDRms). By purchasing QuickAdminPanel, you support my free initiatives, like this Roadmap.

--- 

## Beginner Level
Create your very first simple Laravel project

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course :question: Test__ 

| Topic | Learning Links |
| ----- | ----- |
| **Routing and Controllers: Basics** | |
| Callback Functions and Route::view() |📖 [Basic Routing](https://laravel.com/docs/9.x/routing#basic-routing) <br>📖 [View Routes](https://laravel.com/docs/9.x/routing#view-routes) <br>|
| Routing to a Single Controller Method |📖 [Basic Controllers with Routes](https://laravel.com/docs/9.x/controllers#basic-controllers) <br>|
| Route Parameters |📖 [Route Parameters](https://laravel.com/docs/9.x/routing#route-parameters) <br>|
| Route Naming |📖 [Names Routes](https://laravel.com/docs/9.x/routing#named-routes) <br>|
| Route Groups |📖 [Route Groups](https://laravel.com/docs/9.x/routing#route-groups) <br>|
| **Blade Basics** ||
| Displaying Variables in Blade |📖 [Blade: Displaying Data](https://laravel.com/docs/9.x/blade#displaying-data) <br>|
| Blade If-Else and Loop Structures |📖 [Blade: If-Statements](https://laravel.com/docs/9.x/blade#if-statements) <br>📖 [Blade Loops](https://laravel.com/docs/9.x/blade#loops) <br>|
| Layout: @include, @extends, @section, @yield |📖 [Blade: Layout Using Template Inheritance](https://laravel.com/docs/9.x/blade#layouts-using-template-inheritance) <br>|
| Blade Components |📖 [Blade Components](https://laravel.com/docs/9.x/blade#components) <br>🎬 [Laravel Blade Components: Two Examples - Laravel Breeze/UI](https://www.youtube.com/watch?v=HybWBINeXMw) <br>|
| **Auth Basics** ||
| Starter Kits: Breeze (Tailwind) or Laravel UI (Bootstrap) |📖 [Laravel Breeze Official Documentation](https://laravel.com/docs/9.x/starter-kits#laravel-breeze) <br>📖 [Laravel UI: Official Github Page](https://github.com/laravel/ui) <br>|
| Default Auth Model and Access its Fields from Anywhere |📖 [Retrieving the Authenticated User](https://laravel.com/docs/9.x/authentication#retrieving-the-authenticated-user) <br>|
| Check Auth in Controller / Blade |📖 [Determining If The Current User Is Authenticated](https://laravel.com/docs/9.x/authentication#determining-if-the-current-user-is-authenticated) <br>📖 [Blade: Authentication Directives](https://laravel.com/docs/9.x/blade#authentication-directives) <br>|
| Auth Middleware |📖 [Protecting Routes](https://laravel.com/docs/9.x/authentication#protecting-routes) <br>|
| **Database Basics** ||
| Database Migrations |📖 [Database Migrations](https://laravel.com/docs/9.x/migrations) <br>|
| Basic Eloquent Model and MVC: Controller -> Model -> View |📖 [Eloquent: Getting Started](https://laravel.com/docs/9.x/eloquent) <br>|
| Eloquent Relationships: belongsTo / hasMany / belongsToMany |📖 [Eloquent Relationships: One-to-Many](https://laravel.com/docs/9.x/eloquent-relationships#one-to-many) <br>📖 [Eloquent Relationships: BelongsTo](https://laravel.com/docs/9.x/eloquent-relationships#one-to-many-inverse) <br>📖 [Eloquent Relationships: Many-to-Many](https://laravel.com/docs/9.x/eloquent-relationships#many-to-many) <br>|
| Eager Loading and N+1 Query Problem |📖 [Relationships: Eager Loading](https://laravel.com/docs/9.x/eloquent-relationships#eager-loading) <br>|
| **Full Simple CRUD** ||
| Route Resource and Resourceful Controllers |📖 [Laravel Resource Controllers](https://laravel.com/docs/9.x/controllers#resource-controllers) <br>📄 [Simple Laravel CRUD with Resource Controllers [digitalocean.com]](https://www.digitalocean.com/community/tutorials/simple-laravel-crud-with-resource-controllers) <br>|
| Forms, Validation and Form Requests |📖 [Laravel Validation](https://laravel.com/docs/9.x/validation) <br>|
| File Uploads and Storage Folder Basics |📖 [Filesystem: File Uploads](https://laravel.com/docs/9.x/filesystem#file-uploads) <br>|
| Table Pagination |📖 [Database Pagination](https://laravel.com/docs/9.x/pagination) <br>|


### Beginner Demo-Project: Personal Blog

To achieve this Beginner level, you would need to practice by creating something like [this personal blog project](https://github.com/LaravelDaily/Laravel-Roadmap-Beginner-Challenge).

Inside of the repository above, you will find all the details of the task, with a few example solutions.

-----


## Advanced Beginner Level
The goal of this level is to find the first job or freelance gig

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__ 

| Topic | Learning Links |
| ----- | ----- |
| **Routing Advanced** ||
| Route Model Binding |📖 [Route Model Binding](https://laravel.com/docs/9.x/routing#route-model-binding) <br>🎬 [Laravel Route Model Binding: All You Need To Know](https://www.youtube.com/watch?v=6dEfxGLgevM) <br>|
| Route Redirect |📖 [Redirect Routes](https://laravel.com/docs/9.x/routing#redirect-routes) <br>|
| **Middleware** ||
| Create Custom Middleware Class |📖 [Defining Middleware](https://laravel.com/docs/9.x/middleware#defining-middleware) <br>|
| **Database Advanced** ||
| Database Seeders and Factories |📖 [Database: Seeding](https://laravel.com/docs/9.x/seeding) <br>📖 [Defining Model Factories](https://laravel.com/docs/9.x/database-testing#defining-model-factories) <br>|
| Eloquent Query Scopes |📖 [Eloquent: Query Scopes](https://laravel.com/docs/9.x/eloquent#query-scopes) <br>|
| Polymorphic relationships |📖 [Polymorphic Relationships](https://laravel.com/docs/9.x/eloquent-relationships#polymorphic-relationships) <br>|
| Eloquent Accessors and Mutators |📖 [Accessors & Mutators](https://laravel.com/docs/9.x/eloquent-mutators#accessors-and-mutators) <br>|
| Eloquent Collections |📖 [Eloquent Collections](https://laravel.com/docs/9.x/eloquent-collections) <br>📖 [General Laravel Collections](https://laravel.com/docs/9.x/collections) <br>|
| Soft Deletes |📖 [Soft Deleting](https://laravel.com/docs/9.x/eloquent#soft-deleting) <br>|
| **Auth Advanced** ||
| Authorization: Roles/Permissions, Gates, Policies |📖 [Authorization](https://laravel.com/docs/9.x/authorization) <br>🎬 [Laravel Roles and Permissions: All CORE Things You Need To Know](https://www.youtube.com/watch?v=kZOgH3-0Bko) <br>|
| Authorization: Extra Packages - Spatie Permission, Bouncer, etc |🎬 [Spatie Laravel Permission: Example Project Review](https://www.youtube.com/watch?v=NgToi0uiMNQ) <br>📄 [Two Best Laravel Packages to Manage Roles/Permissions](https://laravel-news.com/two-best-roles-permissions-packages) <br>📖 [spatie/laravel-permission](https://github.com/spatie/laravel-permission) <br>📖 [JosephSilber/bouncer](https://github.com/JosephSilber/bouncer) <br>|
| Authentication: Email Verification |📖 [Email Verification](https://laravel.com/docs/9.x/verification) <br>|
| **File Uploads Advanced** ||
| Drivers and Disks, Example of Amazon S3 |📖 [File Storage](https://laravel.com/docs/9.x/filesystem) <br>🎬 [Laravel: How to Upload Files to Amazon S3](https://www.youtube.com/watch?v=xZQM9q_QxMA) <br>|
| Extra Packages: Spatie Medialibrary, Intervention Image, etc |📖 [spatie/laravel-medialibrary](https://github.com/spatie/laravel-medialibrary) <br>📖 [intervention/image](https://github.com/Intervention/image) <br>|
| **API Basics** ||
| API Routes and Controllers |📖 [API Resource Routes](https://laravel.com/docs/9.x/controllers#api-resource-routes) <br>📖 [Default Route Files](https://laravel.com/docs/9.x/routing#the-default-route-files) <br>|
| Working with API Clients: Postman or Alternatives |📖 [Postman API Client](https://www.postman.com/product/api-client/) <br>|
| API Eloquent Resources |📖 [Eloquent: API Resources](https://laravel.com/docs/9.x/eloquent-resources) <br>|
| API Auth with Sanctum |📖 [Laravel Sanctum](https://laravel.com/docs/9.x/sanctum) <br>|
| API Error Handling and Status Codes |🎬 [Laravel API 404 Error: Customize Exception Message](https://www.youtube.com/watch?v=SlBJrLnyoMk) <br>📄 [HTTP Status Codes](https://httpstatuses.com/) <br>|
| **Debugging Errors** ||
| Log Files in Laravel |📖 [Logging](https://laravel.com/docs/9.x/logging) <br>|
| Try-Catch and Laravel Exceptions |📖 [Error Handling](https://laravel.com/docs/9.x/errors) <br>🎬 [Exceptions in Laravel: Why/How to Use and Create Your Own](https://www.youtube.com/watch?v=RTTXZVIL6tw) <br>|
| Local Debugging Tools: Debugbar, Telescope, Ray |📖 [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) <br>📖 [Laravel Telescope](https://laravel.com/docs/9.x/telescope) <br>📖 [Spatie Ray (Premium Tool)](https://myray.app/) <br>🎬 [Debug Eloquent Queries from API: Laravel Telescope](https://www.youtube.com/watch?v=SR3RzIfeozI) <br>🎬 [Spatie Ray: Laravel Debugging with Pleasure](https://www.youtube.com/watch?v=n4pMxyAXeqY) <br>|
| Customizing Error Pages and Messages |📖 [Custom HTTP Error Pages](https://laravel.com/docs/9.x/errors#custom-http-error-pages) <br>🎬 [Laravel Error Pages: Change Text or Customize Layouts](https://www.youtube.com/watch?v=iMAFUi6Z57k) <br>|
| (optional) Third Party Bug Trackers: Bugsnag, Flare, Sentry, Rollbar |📖 [Bugsnag Laravel](https://docs.bugsnag.com/platforms/php/laravel/) <br>📖 [Flare Homepage](https://flareapp.io/) <br>📖 [Sentry Laravel](https://docs.sentry.io/platforms/php/guides/laravel/) <br>📖 [Rollbar Laravel](https://docs.rollbar.com/docs/laravel) <br>🎬 [Bug Tracking in Laravel: Bugsnag vs Flare [Demo/Review]](https://www.youtube.com/watch?v=88UqUXhWwGA) <br>|
| **Sending Email** ||
| Mailables and Mail Facade |📖 [Mail & Mailables](https://laravel.com/docs/9.x/mail) <br>|
| Configure Drivers/Services: Mailgun, Mailtrap, etc |📰 [How to Send Email From Laravel, and Why We Need 3rd Party Providers For It](https://laraveldaily.com/how-to-send-email-from-laravel-and-why-we-need-3rd-party-providers-for-it/) <br>📖 [Mail: Drivers Prerequisites](https://laravel.com/docs/9.x/mail#driver-prerequisites) <br>|
| Notifications System: Email, SMS, Slack, etc. |📖 [Notifications](https://laravel.com/docs/9.x/notifications) <br>|
| **Automated Testing with PHPUnit** ||
| "Smoke" Tests to Check if Pages are Loading |📖 [Testing: Getting Started](https://laravel.com/docs/9.x/testing) <br>[:capital_abcd: Laravel: PHPUnit Testing for Beginners](https://laraveldaily.teachable.com/p/laravel-phpunit-testing-for-beginners) <br>|
| Configure Testing Database and Test CRUD Operations |📖 [Database Testing](https://laravel.com/docs/9.x/database-testing) <br>|
| **Deployment and Version Control** ||
| Git Version Control |📖 [Git](https://git-scm.com/) <br>🎬 [Git in Laravel. Part 1 - Branches: Main, Develop and Feature](https://www.youtube.com/watch?v=AmScEC-_72I) <br>|
| Deployment on Live Servers |📖 [Deployment](https://laravel.com/docs/9.x/deployment) <br>📄 [How to Deploy Laravel Projects to Live Server: The Ultimate Guide](https://laraveldaily.com/how-to-deploy-laravel-projects-to-live-server-the-ultimate-guide/) <br>📄 [What Server is Needed to Deploy Laravel Projects](https://laraveldaily.com/what-server-is-needed-to-deploy-laravel-projects/) <br>🎬 [How we Deploy Laravel: Branches, Staging Servers, Forge and Envoyer](https://www.youtube.com/watch?v=8DVuVftFZcQ) <br>|


### Advanced Beginner Demo-Project: Simple CRM

To achieve this Advanced Beginner level, you would need to practice by creating something like [this simple CRM project](https://github.com/LaravelDaily/Laravel-Roadmap-Advanced-Beginner-Challenge).

Inside of the repository above, you will find all the details of the task, with an example solution.

-----

## Mid Level
Master all Laravel features with 3-5 years of practical experience

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__ 

| Topic | Learning Links |
| ----- | ----- |
| **Routing Extra Features** ||
| Route Caching |📖 [Route Caching](https://laravel.com/docs/9.x/routing#route-caching) <br>|
| Rate Limiting |📖 [Rate Limiting](https://laravel.com/docs/9.x/routing#rate-limiting) <br>🎬 [Laravel: Create Public API with Cache and Rate Limits](https://www.youtube.com/watch?v=vrLcCxWlxOk) <br>|
| Invokable controllers |📖 [Single Action Controllers](https://laravel.com/docs/9.x/controllers#single-action-controllers) <br>|
| **Database/Eloquent Extra Features** ||
| Model Observers |📖 [Eloquent Observers](https://laravel.com/docs/9.x/eloquent#observers) <br>🎬 [Laravel Model: Check if Any Field Was Changed](https://www.youtube.com/watch?v=_xluet13xxE) <br>🎬 [Eloquent Observers or Events Listeners? Which is Better?](https://www.youtube.com/watch?v=DvoaU6cQQHM) <br>|
| Raw Database Queries |📖 [Query Builder: Raw Expressions](https://laravel.com/docs/9.x/queries#raw-expressions) <br>|
| All Eloquent Features |📖 [All About Eloquent](https://laravel.com/docs/9.x/eloquent) <br>[:capital_abcd: Eloquent: Expert Level](https://laraveldaily.teachable.com/p/laravel-eloquent-expert-level) <br>📄 [20 Laravel Eloquent Tips and Tricks](https://laravel-news.com/eloquent-tips-tricks) <br>|
| **Various Extra Laravel Features** ||
| Caching |📖 [Cache](https://laravel.com/docs/9.x/cache) <br>🎬 [Cache Eloquent Query Results to Load Pages Instantly](https://www.youtube.com/watch?v=JhKngeE0XJA) <br>|
| Creating Artisan Commands |📖 [Writing Artisan Commands](https://laravel.com/docs/9.x/artisan#writing-commands) <br>🎬 [How to Create Artisan Commands in Laravel](https://www.youtube.com/watch?v=-r3WnYy7g48) <br>|
| Task Scheduling |📖 [Task Scheduling](https://laravel.com/docs/9.x/scheduling) <br>|
| Login with X: Laravel Socialite |📖 [Laravel Socialite](https://laravel.com/docs/9.x/socialite) <br>|
| Laravel HTTP Client and Guzzle |📖 [HTTP Client](https://laravel.com/docs/9.x/http-client) <br>🎬 [Laravel and External APIs: Get Data with HTTP Client](https://www.youtube.com/watch?v=oEDDZsmMLc0) <br>|
| Custom Blade Directives |📖 [Extending Blade](https://laravel.com/docs/9.x/blade#extending-blade) <br>|
| Events and Listeners |📖 [Events and Listeners](https://laravel.com/docs/9.x/events) <br>🎬 [Laravel: 3 Ways to Send a Welcome Email (Controller vs Observer vs Events)](https://www.youtube.com/watch?v=ZWzH6SOzjhI) <br>🎬 [Laravel: Why Observers and Event Listeners are "Risky"](https://www.youtube.com/watch?v=A3bmLo77e5M) <br>|
| **Jobs and Queues** |[:capital_abcd: Queues in Laravel](https://laraveldaily.teachable.com/p/queues-in-laravel) <br>|
| Queueable Classes and Jobs |📖 [Creating Jobs](https://laravel.com/docs/9.x/queues#creating-jobs) <br>📖 [Queueing Notifications](https://laravel.com/docs/9.x/notifications#queueing-notifications) <br>📖 [Queued Event Listeners](https://laravel.com/docs/9.x/events#queued-event-listeners) <br>📖 [Queueing Mail](https://laravel.com/docs/9.x/mail#queueing-mail) <br>🎬 [Laravel Queues 101: Example with Sending Emails](https://www.youtube.com/watch?v=rVx8xKisbr8) <br>|
| Processing Failed Jobs |📖 [Dealing with Failed Jobs](https://laravel.com/docs/9.x/queues#dealing-with-failed-jobs) <br>|
| Job Dispatching, Batching and Chaining |📖 [Dispatching Jobs](https://laravel.com/docs/9.x/queues#dispatching-jobs) <br>|
| Configuring Queues: Drivers, Redis, Supervisor |📖 [Running the Queue Worker](https://laravel.com/docs/9.x/queues#running-the-queue-worker) <br>📖 [Configuring Supervisor](https://laravel.com/docs/9.x/queues#supervisor-configuration) <br>|
| Laravel Horizon (optional, if you use Redis) |📖 [Laravel Horizon](https://laravel.com/docs/9.x/horizon) <br>|
| **API Advanced** ||
| Upload Files via API |:page_facing_up: [Laravel API: How to Upload File from Vue.js](https://blog.quickadminpanel.com/laravel-api-how-to-upload-file-from-vue-js/) <br>|
| Generate API Documentation |:page_facing_up: [Laravel API Documentation with OpenAPI/Swagger](https://blog.quickadminpanel.com/laravel-api-documentation-with-openapiswagger/) <br>:clapper: [Scribe: New Package for Laravel API Documentation](https://www.youtube.com/watch?v=PjwGI8c2IfA) <br>|
| API Versioning |:page_facing_up: [Versioning your REST API with Laravel](https://codimth.com/blog/web/laravel/versioning-your-rest-api-laravel) <br>:clapper: [Versioning your API: from V1 to V2 and Beyond [video from my course]](https://laraveldaily.teachable.com/courses/how-to-create-laravel-api/lectures/17568998) <br>|
| API with OAuth and Laravel Passport |:book: [Laravel Passport](https://laravel.com/docs/8.x/passport) <br> :clapper: [Laravel API Auth Demo: Passport, oAuth and Sanctum](https://www.youtube.com/watch?v=8myQdPL8I1s)|
| Only-API Projects with Front-end like Vue.js |:capital_abcd: [Vue.js + Laravel: CRUD with SPA](https://laraveldaily.teachable.com/p/vue-laravel-crud-spa) <br>|
| Only-API Projects with Mobile Apps |:page_facing_up: [Using Sanctum to authenticate a mobile app](https://laravel-news.com/using-sanctum-to-authenticate-a-mobile-app) <br>|
| **(optional) Starter Kits: Laravel Jetstream and Fortify** ||
| Laravel Jetstream (requires Livewire/Inertia knowledge) |📖 [Laravel Jetstream](https://jetstream.laravel.com) <br>[:capital_abcd: Laravel Jetstream+Livewire: Real Mini-Project](https://laraveldaily.teachable.com/p/laravel-jetstream-livewire-project) <br>🎬 [Laravel Jetstream: How it Works and Example How to Customize](https://www.youtube.com/watch?v=d8YgWApHMfA) <br>|
| Laravel Fortify |📖 [Laravel Fortify](https://laravel.com/docs/9.x/fortify) <br>🎬 [Laravel Fortify: Four Auth Things to Customize](https://www.youtube.com/watch?v=Vr4LJU3kw1g) <br>|
| **Payments** ||
| Laravel Cashier with Stripe/Paddle |📖 [Laravel Cashier (Stripe)](https://laravel.com/docs/9.x/billing) <br>📖 [Laravel Cashier (Paddle)](https://laravel.com/docs/9.x/cashier-paddle) <br>|
| Custom Payment Providers: PayPal, Mollie, etc |📄 [Subscription billing with Laravel Cashier for Mollie](https://github.com/laravel/cashier-mollie) <br>📄 [How To Integrate Paypal Payment Gateway In Laravel](https://websolutionstuff.com/post/how-to-integrate-paypal-payment-gateway-in-laravel) <br>|
| **Automated Testing Advanced** ||
| TDD: Test-Driven Development |[:capital_abcd: Build A Laravel App With TDD](https://laracasts.com/series/build-a-laravel-app-with-tdd) <br>[:capital_abcd: TDD With Laravel](https://tddwithlaravel.com/) <br>|
| Mocking |📖 [Mocking](https://laravel.com/docs/9.x/mocking) <br>|
| (optional) Laravel Dusk |📖 [Laravel Dusk](https://laravel.com/docs/9.x/dusk) <br>|
| **Full-Text Search** ||
| Laravel Scout |📖 [Laravel Scout](https://laravel.com/docs/9.x/scout) <br>|
| Drivers: ElasticSearch, Algolia or MeiliSearch |📄 [ElasticSearch Driver for Laravel Scout](https://laravel-news.com/explorer) <br>📖 [Algolia: Scout Extended](https://www.algolia.com/doc/framework-integration/laravel/getting-started/introduction-to-scout-extended/?client=php) <br>📄 [Full-Text Search with MeiliSearch and Laravel Scout](https://tighten.co/blog/full-text-search-with-meilisearch-and-scout/) <br>|
| **Laravel Packages** ||
| Contributing to Packages, making Pull Requests |🎬 [How to Contribute to Laravel Docs (or any open-source repository)](https://www.youtube.com/watch?v=vEcT6JIFji0) <br>|
| Create Laravel Packages |📖 [Package Development](https://laravel.com/docs/9.x/packages) <br>[:capital_abcd: Laravel Package Development](https://laravelpackage.com/) <br>|


## Senior Level
Responsibility for architecture decisions on large projects

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__ 

| Topic | Learning Links |
| ----- | ----- |
| **PHP/Laravel Design Patterns** |:clapper: [Laravel Design Patterns - Bobby Bouwmann - Laracon EU 2018 Amsterdam](https://www.youtube.com/watch?v=qpo5KG0vIyE) <br>:capital_abcd: [Laracasts: Design Patterns in PHP](https://laracasts.com/series/design-patterns-in-php) <br>:clapper: [Colin Decarlo - Design Patterns with Laravel [Laracon 2018]](https://www.youtube.com/watch?v=e4ugSgGaCQ0) <br>:clapper: [Matt Stauffer - Patterns That Pay Off [Laracon 2018]](https://www.youtube.com/watch?v=enTb2E4vEos) <br>:capital_abcd: [Design Patterns in PHP](https://refactoring.guru/design-patterns/php) <br>:page_facing_up: [Design Patterns for Humans](https://github.com/kamranahmedse/design-patterns-for-humans) <br>|
| Creational Design Patterns |:page_facing_up: [Design Patterns PHP: Creational](https://designpatternsphp.readthedocs.io/en/latest/Creational/README.html) <br>|
| Structural Design Patterns |:page_facing_up: [Design Patterns PHP: Structural](https://designpatternsphp.readthedocs.io/en/latest/Structural/README.html) <br>|
| Behavioral Design Patterns |:page_facing_up: [Design Patterns PHP: Behavioral](https://designpatternsphp.readthedocs.io/en/latest/Behavioral/README.html) <br>|
| **Well-written Code** ||
| SOLID Code |:clapper: [Becoming a better developer by using the SOLID design principles by Katerina Trajchevska](https://www.youtube.com/watch?v=rtmFCcjEgEw) <br>:page_facing_up: [Writing Maintainable Code: SOLID Principles Explained in PHP (Laravel)](https://geekflare.com/php-solid-principles/) <br>:capital_abcd: [Laracasts: SOLID Principles in PHP](https://laracasts.com/series/solid-principles-in-php) <br>:clapper: [PHP Solid Principles [Playlist]](https://www.youtube.com/watch?v=ARxZV8OZ8Cg&list=PLNuh5_K9dfQ3jMU-2C2jYRGe2iXJkpCZj) <br>|
| Scalable Code |:capital_abcd: [Scaling Laravel](https://courses.serversforhackers.com/scaling-laravel) <br>:clapper: [Enterprise Laravel by Matt Stauffer](https://enterpriselaravel.com/) <br>:page_facing_up: [What the hell is scalable code anyway?](https://blog.sarasarya.com/what-the-hell-is-scalable-code-anyway-f6626ad78227) <br>|
| Maintainable Code |:page_facing_up: [How would you know if you've written readable and easily maintainable code? [forum thread]](https://softwareengineering.stackexchange.com/questions/141005/how-would-you-know-if-youve-written-readable-and-easily-maintainable-code) <br>:page_facing_up: [Crafting maintainable Laravel applications](https://jasonmccreary.me/articles/crafting-maintainable-laravel-applications/) <br>:page_facing_up: [7 Golden Rules of Clean, Simple and Maintainable Code](https://shhetri.github.io/clean-code/#/) <br>|
| Best Practices and Standards |:page_facing_up: [Repository: alexeymezenin / laravel-best-practices](https://github.com/alexeymezenin/laravel-best-practices) <br>:capital_abcd: [PHP: The Right Way](https://phptherightway.com/) <br>:page_facing_up: [Reddit: What are your Laravel best practices?](https://www.reddit.com/r/laravel/comments/f34t86/what_are_your_laravel_best_practices/) <br>|
| **Large Datasets** ||
| Large Database Structures |:capital_abcd: [How to Structure Databases in Laravel](https://laraveldaily.teachable.com/p/how-to-structure-database-in-laravel) <br>|
| NoSQL Solutions |:book: [MongoDB and Laravel Integration](https://www.mongodb.com/compatibility/mongodb-laravel-intergration) <br>:page_facing_up: [MongoDB + Laravel = Love — When to use NoSQL](https://faun.pub/when-to-use-nosql-getting-started-with-mongodb-in-laravel-f5376ceaf545) <br>|
| Eloquent/SQL Query Optimization |:page_facing_up: [18 Tips to optimize laravel database queries](https://dudi.dev/optimize-laravel-database-queries/) <br>:page_facing_up: [Optimizing Laravel Part 2: Improving Query Performance with Database Indexing](https://deliciousbrains.com/optimizing-laravel-database-indexing-performance/) <br>:capital_abcd: [Eloquent Performance Patterns](https://eloquent-course.reinink.ca/) <br>|
| Scaling to Multiple Databases |:page_facing_up: [Scaling Laravel App with Multiple Databases](https://devdojo.com/bobbyiliev/scaling-laravel-app-with-multiple-databases) <br>:page_facing_up: [Multiple DB Connections in Laravel](https://fideloper.com/laravel-multiple-database-connections) <br>|
| **Working with High-Traffic Projects** ||
| Stability and Zero-Downtime Deployments |:book: [Laravel Deployer](https://github.com/deployphp/deployer) <br>:book: [Envoyer - Zero Downtime PHP Deployment](https://envoyer.io/) <br>|
| Performance Optimization and Caching |:capital_abcd: [Performant Laravel](https://serversforhackers.com/laravel-perf) <br>:page_facing_up: [The Ultimate Performance Checklist For Laravel Apps](https://laravel-news.com/performance-checklist) <br>:page_facing_up: [How to Optimize PHP Laravel Web Application for High Performance?](https://geekflare.com/laravel-optimization/) <br>|
| **Ensuring Code Quality** ||
| Writing Testable Code |:page_facing_up: [How to write testable code](https://dev.to/ddarrko/how-to-write-more-testable-code-oi7) <br>:page_facing_up: [Refactoring towards testability](https://madewithlove.com/blog/software-engineering/refactoring-untestable-code-towards-testability/) <br>|
| Continuous Integration and Continuous Delivery (CI/CD) |:page_facing_up: [How to create a CI/CD for a Laravel application using GitHub Actions](https://blog.logrocket.com/how-to-create-a-ci-cd-for-a-laravel-application-using-github-actions/) <br>:page_facing_up: [Configure Laravel 8 for CI/CD with Jenkins and GitHub — Part 1](https://faun.pub/configure-laravel-8-for-ci-cd-with-jenkins-and-github-part-1-58b9be304292) <br>:page_facing_up: [Build, Test, and Deploy Your Laravel Application With GitHub Actions](https://www.twilio.com/blog/build-test-deploy-laravel-application-github-actions) <br>|
