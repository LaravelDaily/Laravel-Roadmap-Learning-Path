# IMPORTANT: March 2022

It's horrible to see what is happening now in Ukraine, as Russian army is [bombarding houses, hospitals and kindergartens](https://twitter.com/DavidCornDC/status/1501620037785997316). 

Please [check out supportukrainenow.org](https://supportukrainenow.org/) for the ways how you can help people there. Spread the word.

And if you are from Russia and you are against this war, please express your protest in some way. I know you can get punished for this, but you are one of the hopes of those innocent people.

---

# Laravel Learning Path

This repository contains the **ordered** list of Laravel topics to learn, step-by-step, with related links.

If you want to add a topic, link, or any other suggestion, please open Issues or Pull Requests.

**Notice**: This content was filled into an adminpanel generated with our [QuickAdminPanel](https://quickadminpanel.com?utm_source=github&utm_campaign=roadmap) - here's a [video demo of that process on Youtube](https://www.youtube.com/watch?v=i2ElUDUDRms). By purchasing QuickAdminPanel, you support my free initiatives, like this Roadmap.

--- 

## Beginner Level
Create your very first simple Laravel project

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course :question: Test__ 

| Topic | Learning Links |
| ----- | ----- |
| **Routing and Controllers: Basics** | :question: [Let's Test Your Laravel Routing Skills: Complete 12 Tasks](https://www.youtube.com/watch?v=pENlD3izA3Q) |
| Callback Functions and Route::view() |:book: [Basic Routing](https://laravel.com/docs/routing#basic-routing) <br>:book: [View Routes](https://laravel.com/docs/routing#view-routes) <br>|
| Routing to a Single Controller Method |:book: [Basic Controllers with Routes](https://laravel.com/docs/controllers#basic-controllers) <br>|
| Route Parameters |:book: [Route Parameters](https://laravel.com/docs/routing#route-parameters) <br>|
| Route Naming |:book: [Names Routes](https://laravel.com/docs/routing#named-routes) <br> :clapper: [Laravel: Why You Need Route Names?](https://www.youtube.com/watch?v=7lalb6HtR1c) <br>|
| Route Groups |:book: [Route Groups](https://laravel.com/docs/routing#route-groups) <br> :clapper: [Laravel Route Grouping: Simple to Very Complex](https://www.youtube.com/watch?v=I6kyfSmPhn8) <br> :clapper: [More videos](videos/route-groups.md) |
| **Blade Basics** | :question: [Let's Test Your Laravel Blade Skills: Complete 8 Tasks](https://www.youtube.com/watch?v=P8s7UHuUhbg)<br>:clapper: [9 Quick Tips about Laravel Blade](https://www.youtube.com/watch?v=-Glz1InN68o) <br>|
| Displaying Variables in Blade |:book: [Blade: Displaying Data](https://laravel.com/docs/blade#displaying-data) <br>|
| Blade If-Else and Loop Structures |:book: [Blade: If-Statements](https://laravel.com/docs/blade#if-statements) <br>:book: [Blade Loops](https://laravel.com/docs/blade#loops) <br>|
| Layout: @include, @extends, @section, @yield |:book: [Blade: Layout Using Template Inheritance](https://laravel.com/docs/blade#layouts-using-template-inheritance) <br>|
| Blade Components |:book: [Blade Components](https://laravel.com/docs/blade#components) <br>:clapper: [Laravel Blade Components: Two Examples - Laravel Breeze/UI](https://www.youtube.com/watch?v=HybWBINeXMw) <br>|
| **Auth Basics** | :question: [Test Your Laravel Auth Skills: Complete 7 Tasks](https://www.youtube.com/watch?v=v_3NmwtN_S0)<br>:clapper: [8 Tips & Tricks about Laravel Auth](https://www.youtube.com/watch?v=-dpp4CJS6Vk) <br> |
| Starter Kits: Breeze (Tailwind) or Laravel UI (Bootstrap) |:book: [Laravel Breeze Official Documentation](https://laravel.com/docs/starter-kits#laravel-breeze) <br>:book: [Laravel UI: Official Github Page](https://github.com/laravel/ui) <br> :clapper: [Laravel 8 Auth: 5 "Latest" Things You Need to Know](https://www.youtube.com/watch?v=L1FVdHdEm_8) <br> [More videos](videos/auth-starter-kits.md)<br>|
| Default Auth Model and Access its Fields from Anywhere |:book: [Retrieving the Authenticated User](https://laravel.com/docs/authentication#retrieving-the-authenticated-user) <br>|
| Check Auth in Controller / Blade |:book: [Determining If The Current User Is Authenticated](https://laravel.com/docs/authentication#determining-if-the-current-user-is-authenticated) <br>:book: [Blade: Authentication Directives](https://laravel.com/docs/blade#authentication-directives) <br>|
| Auth Middleware |:book: [Protecting Routes](https://laravel.com/docs/authentication#protecting-routes) <br>|
| **Database Basics** ||
| Database Migrations |:question: [Test Your Laravel Migrations Skills: Complete 10 Tasks](https://www.youtube.com/watch?v=tPU1hNKI_lc)<br>:book: [Database Migrations](https://laravel.com/docs/migrations) <br> :clapper: [Laravel Migrations: Table Created but Foreign Key Failed?](https://www.youtube.com/watch?v=DWzUBpsEEHY) <br> [More videos](videos/database-migrations.md) |
| Basic Eloquent Model and MVC: Controller -> Model -> View |:question: [Test Your Eloquent Basic Skills: 11 Tasks to Complete](https://www.youtube.com/watch?v=AmvLs9sRSH8)<br>:book: [Eloquent: Getting Started](https://laravel.com/docs/eloquent) <br>|
| Eloquent Relationships: belongsTo / hasMany / belongsToMany |:question: [Test Your Eloquent Relationships Skills: 9 Tasks to Complete](https://www.youtube.com/watch?v=ohj0Mc09DyE)<br>:book: [Eloquent Relationships: One-to-One](https://laravel.com/docs/eloquent-relationships#one-to-one) <br>:book: [Eloquent Relationships: One-to-Many](https://laravel.com/docs/eloquent-relationships#one-to-many) <br>:book: [Eloquent Relationships: BelongsTo](https://laravel.com/docs/eloquent-relationships#one-to-many-inverse) <br>:book: [Eloquent Relationships: Many-to-Many](https://laravel.com/docs/eloquent-relationships#many-to-many) <br> :clapper: [How to Safely Change DB Relations in Live Laravel Project?](https://www.youtube.com/watch?v=nRmoywPJRdM) |
| Eager Loading and N+1 Query Problem |:book: [Relationships: Eager Loading](https://laravel.com/docs/eloquent-relationships#eager-loading) <br> :clapper: [Laravel N+1 Query Detector: Don't Forget Eager Loading](https://www.youtube.com/watch?v=MbN7BIcUnPA) <br>|
| **Full Simple CRUD** ||
| Route Resource and Resourceful Controllers |:book: [Laravel Resource Controllers](https://laravel.com/docs/controllers#resource-controllers) <br>:page_facing_up: [Simple Laravel CRUD with Resource Controllers [digitalocean.com]](https://www.digitalocean.com/community/tutorials/simple-laravel-crud-with-resource-controllers) <br> :clapper: [Laravel Nested Resource Controllers: Two-Level Deep](https://www.youtube.com/watch?v=9R_9Xe3Fgnw) <br> :clapper: [More videos](videos/route-resource-resourceful-controllers.md) <br>|
| Forms, Validation and Form Requests |:question: [Test Your Laravel Validation Skills: Complete 9 Tasks](https://www.youtube.com/watch?v=3ihjumeOMV4)<br>:book: [Laravel Validation](https://laravel.com/docs/validation) <br> :clapper: [New in Laravel 6.13: Format Validation Error Field Name](https://www.youtube.com/watch?v=KD1SqLO58eE) :clapper: [More videos](videos/forms-validation-requests.md) |
| File Uploads and Storage Folder Basics |:question: [Test Your Laravel File Upload Skills: Complete 7 Tasks](https://www.youtube.com/watch?v=_SrQRnOx3q8)<br>:book: [Filesystem: File Uploads](https://laravel.com/docs/filesystem#file-uploads) <br> :clapper: [Laravel: How to Upload File During User Registration](https://www.youtube.com/watch?v=xyQT2pnv_4E) <br> [More videos](videos/file-uploads-and-storage-folder-basics.md) <br> |
| Table Pagination |:book: [Database Pagination](https://laravel.com/docs/pagination) <br>|


### Beginner Demo-Project: Personal Blog

To achieve this Beginner level, you would need to practice by creating something like [this personal blog project](https://github.com/LaravelDaily/Laravel-Roadmap-Beginner-Challenge).

Inside of the repository above, you will find all the details of the task, with a few example solutions.

-----


## Advanced Beginner Level
The goal of this level is to find the first job or freelance gig

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__ 

| Topic | Learning Links |
| ----- | ----- |
| **Routing Advanced** | :clapper: [Laravel: 8 Tips for Advanced Routing](https://www.youtube.com/watch?v=_BIhuX8owTo) <br> :clapper: [More videos](videos/routing-advanced.md) <br> |
| Route Model Binding |:book: [Route Model Binding](https://laravel.com/docs/routing#route-model-binding) <br>:clapper: [Laravel Route Model Binding: All You Need To Know](https://www.youtube.com/watch?v=6dEfxGLgevM) <br> :clapper: [More videos](videos/route-model-binding.md)|
| Route Redirect |:book: [Redirect Routes](https://laravel.com/docs/routing#redirect-routes) <br>|
| **Middleware** ||
| Create Custom Middleware Class |:book: [Defining Middleware](https://laravel.com/docs/middleware#defining-middleware) <br>|
| **Database Advanced** ||
| Database Seeders and Factories |:book: [Database: Seeding](https://laravel.com/docs/seeding) <br>:book: [Defining Model Factories](https://laravel.com/docs/eloquent-factories#defining-model-factories) <br> :clapper: [Laravel Factories: Generate and Re-use Fake Records](https://www.youtube.com/watch?v=MHBDUJ51Pqs) <br> :clapper: [More videos](videos/database-seeders-and-factories.md)|
| Eloquent Query Scopes |:book: [Eloquent: Query Scopes](https://laravel.com/docs/eloquent#query-scopes) <br> :clapper: [Same Eloquent Where Condition? Refactor into Local Scopes](https://www.youtube.com/watch?v=90xGUIuZsHE) <br>|
| Polymorphic relationships |:book: [Polymorphic Relationships](https://laravel.com/docs/eloquent-relationships#polymorphic-relationships) <br> :clapper: [Laravel.io Portal: Polymorphic Relations Example](https://www.youtube.com/watch?v=EjJaNGW7vAg) <br>|
| Eloquent Accessors and Mutators |:book: [Accessors & Mutators](https://laravel.com/docs/eloquent-mutators#accessors-and-mutators) <br>|
| Eloquent Collections |:book: [Eloquent Collections](https://laravel.com/docs/eloquent-collections) <br>:book: [General Laravel Collections](https://laravel.com/docs/collections) <br>|
| Soft Deletes |:book: [Soft Deleting](https://laravel.com/docs/eloquent#soft-deleting) <br>|
| **Auth Advanced** ||
| Authorization: Roles/Permissions, Gates, Policies |:book: [Authorization](https://laravel.com/docs/authorization) <br>:clapper: [Laravel Roles and Permissions: All CORE Things You Need To Know](https://www.youtube.com/watch?v=kZOgH3-0Bko) <br> [More videos](videos/authorization-roles-permissions-gates-policies.md)|
| Authorization: Extra Packages - Spatie Permission, Bouncer, etc |:clapper: [Spatie Laravel Permission: Example Project Review](https://www.youtube.com/watch?v=NgToi0uiMNQ) <br>:page_facing_up: [Two Best Laravel Packages to Manage Roles/Permissions](https://laravel-news.com/two-best-roles-permissions-packages) <br>:book: [spatie/laravel-permission](https://github.com/spatie/laravel-permission) <br>:book: [JosephSilber/bouncer](https://github.com/JosephSilber/bouncer) <br>|
| Authentication: Email Verification |:book: [Email Verification](https://laravel.com/docs/verification) <br> :clapper: [How to Translate/Customize Laravel Auth Default Emails](https://www.youtube.com/watch?v=c01k5Zo_CuI) |
| **File Uploads Advanced** |:capital_abcd: [File Uploads in Laravel](https://laraveldaily.com/course/laravel-file-uploads?utm_source=github&utm_campaign=roadmap) <br>|
| Drivers and Disks, Example of Amazon S3 |:book: [File Storage](https://laravel.com/docs/filesystem) <br>:clapper: [Laravel: How to Upload Files to Amazon S3](https://www.youtube.com/watch?v=xZQM9q_QxMA) <br>|
| Extra Packages: Spatie Medialibrary, Intervention Image, etc |:book: [spatie/laravel-medialibrary](https://github.com/spatie/laravel-medialibrary) <br>:book: [intervention/image](https://github.com/Intervention/image) <br> :clapper: [Spatie Media Library Pro: Laravel File Uploads with Great UX [REVIEW]](https://www.youtube.com/watch?v=oqW6vlJgXYE) <br> :clapper: [More videos](videos/file-upload-extra-packages.md) <br>|
| **API Basics** |:capital_abcd: [How to Create Laravel API](https://laraveldaily.com/course/laravel-api?utm_source=github&utm_campaign=roadmap) <br> :clapper: [Create Model with API Controller - in one Artisan Command](https://www.youtube.com/watch?v=DZw2wKzfRVU) <br> [Laravel API: Be Careful When Doing Changes](https://www.youtube.com/watch?v=yXnIW4DkuHQ) <br>|
| API Routes and Controllers |:book: [API Resource Routes](https://laravel.com/docs/controllers#api-resource-routes) <br>:book: [Default Route Files](https://laravel.com/docs/routing#the-default-route-files) <br> :clapper: [Junior Code Review: Simple Laravel API - in 5 Different Ways](https://www.youtube.com/watch?v=MxQJlFUYO30) <br>|
| Working with API Clients: Postman or Alternatives |:book: [Postman API Client](https://www.postman.com/product/api-client/) <br>|
| API Eloquent Resources |:book: [Eloquent: API Resources](https://laravel.com/docs/eloquent-resources) <br> :clapper: [Laravel API Result: Add Fields with Map or Appends](https://www.youtube.com/watch?v=FNU3gYgiEgQ) <br>|
| API Auth with Sanctum |:book: [Laravel Sanctum](https://laravel.com/docs/sanctum) <br> :clapper: [Laravel API Auth with Sanctum and API Tokens](https://www.youtube.com/watch?v=gyWLxpYWxFQ)<br> :clapper: [More videos](videos/api-auth-with-sanctum.md)<br>|
| API Error Handling and Status Codes |:clapper: [Laravel API 404 Error: Customize Exception Message](https://www.youtube.com/watch?v=SlBJrLnyoMk) <br>:page_facing_up: [HTTP Status Codes](https://httpstatuses.com/) <br>|
| **Debugging Errors** ||
| Log Files in Laravel |:book: [Logging](https://laravel.com/docs/logging) <br>|
| Try-Catch and Laravel Exceptions |:book: [Error Handling](https://laravel.com/docs/errors) <br>:clapper: [Exceptions in Laravel: Why/How to Use and Create Your Own](https://www.youtube.com/watch?v=RTTXZVIL6tw) <br>|
| Local Debugging Tools: Debugbar, Telescope, Ray |:book: [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) <br>:book: [Laravel Telescope](https://laravel.com/docs/telescope) <br>:book: [Spatie Ray (Premium Tool)](https://myray.app/) <br>:clapper: [Debug Eloquent Queries from API: Laravel Telescope](https://www.youtube.com/watch?v=SR3RzIfeozI) <br>:clapper: [Spatie Ray: Laravel Debugging with Pleasure](https://www.youtube.com/watch?v=n4pMxyAXeqY) <br>|
| Customizing Error Pages and Messages |:book: [Custom HTTP Error Pages](https://laravel.com/docs/errors#custom-http-error-pages) <br>:clapper: [Laravel Error Pages: Change Text or Customize Layouts](https://www.youtube.com/watch?v=iMAFUi6Z57k) <br> :clapper: [New in Laravel 8.26: Override 404 Page with Route Missing](https://www.youtube.com/watch?v=nvDCQDkcjN0) <br>|
| (optional) Third Party Bug Trackers: Bugsnag, Flare, Sentry, Rollbar |:book: [Bugsnag Laravel](https://docs.bugsnag.com/platforms/php/laravel/) <br>:book: [Flare Homepage](https://flareapp.io/) <br>:book: [Sentry Laravel](https://docs.sentry.io/platforms/php/guides/laravel/) <br>:book: [Rollbar Laravel](https://docs.rollbar.com/docs/laravel) <br>:clapper: [Bug Tracking in Laravel: Bugsnag vs Flare [Demo/Review]](https://www.youtube.com/watch?v=88UqUXhWwGA) <br>|
| **Sending Email** | :clapper: [Laravel: 3 Ways to Send a Welcome Email (Controller vs Observer vs Events)](https://www.youtube.com/watch?v=ZWzH6SOzjhI) |
| Mailables and Mail Facade |:book: [Mail & Mailables](https://laravel.com/docs/mail) <br>|
| Configure Drivers/Services: Mailgun, Mailtrap, etc |:page_facing_up: [How to Send Email From Laravel, and Why We Need 3rd Party Providers For It](https://laraveldaily.com/how-to-send-email-from-laravel-and-why-we-need-3rd-party-providers-for-it/) <br>:book: [Mail: Drivers Prerequisites](https://laravel.com/docs/mail#driver-prerequisites) <br>|
| Notifications System: Email, SMS, Slack, etc. |:book: [Notifications](https://laravel.com/docs/notifications) <br> :clapper: [Laravel Notifications: "Database" Driver - Demo Project](https://www.youtube.com/watch?v=5DREuAvFnps)|
| **Automated Testing with PHPUnit** | :clapper: [PHPUnit in Laravel: Simple Example of Why/How to Test](https://www.youtube.com/watch?v=DRhhfy2sG1E) <br>|
| "Smoke" Tests to Check if Pages are Loading |:book: [Testing: Getting Started](https://laravel.com/docs/testing) <br>:capital_abcd: [Testing Laravel: Course by Spatie](https://spatie.be/products/testing-laravel) <br>:capital_abcd: [My Course: Laravel Testing For Beginners: PHPUnit, Pest, TDD](https://laraveldaily.com/course/laravel-testing?utm_source=github&utm_campaign=roadmap) <br> :clapper: [Laravel TDD in "Live" Mode: Checkout Code Review](https://www.youtube.com/watch?v=5XywKLjCD3g) |
| Configure Testing Database and Test CRUD Operations |:book: [Database Testing](https://laravel.com/docs/database-testing) <br>|
| **Deployment and Version Control** ||
| Git Version Control |:book: [Git](https://git-scm.com/) <br>:clapper: [Git in Laravel. Part 1 - Branches: Main, Develop and Feature](https://www.youtube.com/watch?v=AmScEC-_72I) <br> :clapper: [More videos](videos/git-version-control.md)|
| Deployment on Live Servers |:book: [Deployment](https://laravel.com/docs/deployment) <br>:page_facing_up: [How to Deploy Laravel Projects to Live Server: The Ultimate Guide](https://laraveldaily.com/how-to-deploy-laravel-projects-to-live-server-the-ultimate-guide/) <br>:page_facing_up: [What Server is Needed to Deploy Laravel Projects](https://laraveldaily.com/what-server-is-needed-to-deploy-laravel-projects/) <br>:clapper: [How we Deploy Laravel: Branches, Staging Servers, Forge and Envoyer](https://www.youtube.com/watch?v=8DVuVftFZcQ) <br>|


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
| Route Caching |:book: [Route Caching](https://laravel.com/docs/routing#route-caching) <br>|
| Rate Limiting |:book: [Rate Limiting](https://laravel.com/docs/routing#rate-limiting) <br>:clapper: [Laravel: Create Public API with Cache and Rate Limits](https://www.youtube.com/watch?v=vrLcCxWlxOk) <br>|
| Invokable controllers |:book: [Single Action Controllers](https://laravel.com/docs/controllers#single-action-controllers) <br>|
| **Database/Eloquent Extra Features** ||
| Model Observers |:book: [Eloquent Observers](https://laravel.com/docs/eloquent#observers) <br>:clapper: [Laravel Model: Check if Any Field Was Changed](https://www.youtube.com/watch?v=_xluet13xxE) <br>:clapper: [Eloquent Observers or Events Listeners? Which is Better?](https://www.youtube.com/watch?v=DvoaU6cQQHM) <br>|
| Raw Database Queries |:book: [Query Builder: Raw Expressions](https://laravel.com/docs/queries#raw-expressions) <br>|
| All Eloquent Features |:book: [All About Eloquent](https://laravel.com/docs/eloquent) <br>:capital_abcd: [Eloquent: Expert Level](https://laraveldaily.teachable.com/p/laravel-eloquent-expert-level?utm_source=github&utm_campaign=roadmap) <br>:page_facing_up: [20 Laravel Eloquent Tips and Tricks](https://laravel-news.com/eloquent-tips-tricks) <br> :clapper: [Laravel Collections: 5 Methods with Real Examples](https://www.youtube.com/watch?v=isAz2GduuA0) <br> [More videos](videos/all-eloquent-features.md) <br>|
| **Various Extra Laravel Features** ||
| Custom Blade Directives |:book: [Extending Blade](https://laravel.com/docs/blade#extending-blade) <br>|
| Events and Listeners |:book: [Events and Listeners](https://laravel.com/docs/events) <br>:clapper: [Laravel: 3 Ways to Send a Welcome Email (Controller vs Observer vs Events)](https://www.youtube.com/watch?v=ZWzH6SOzjhI) <br>:clapper: [Laravel: Why Observers and Event Listeners are "Risky"](https://www.youtube.com/watch?v=A3bmLo77e5M) <br>|
| Laravel HTTP Client and Guzzle |:book: [HTTP Client](https://laravel.com/docs/http-client) <br>:clapper: [Laravel and External APIs: Get Data with HTTP Client](https://www.youtube.com/watch?v=oEDDZsmMLc0) <br>|
| Login with X: Laravel Socialite |:book: [Laravel Socialite](https://laravel.com/docs/socialite) <br>|
| Creating Artisan Commands |:book: [Writing Artisan Commands](https://laravel.com/docs/artisan#writing-commands) <br>:clapper: [How to Create Artisan Commands in Laravel](https://www.youtube.com/watch?v=-r3WnYy7g48) <br>|
| Task Scheduling |:book: [Task Scheduling](https://laravel.com/docs/scheduling) <br>:clapper: [Laravel Task Scheduling: Run Artisan Command Hourly](https://www.youtube.com/watch?v=r-KrsQ0dN80) <br>|
| Caching |:book: [Cache](https://laravel.com/docs/cache) <br>:clapper: [Cache Eloquent Query Results to Load Pages Instantly](https://www.youtube.com/watch?v=JhKngeE0XJA) <br>|
| Real-time: Broadcasting, Echo and Pusher |:book: [Broadcasting](https://laravel.com/docs/broadcasting) <br>|
| **Jobs and Queues** |:capital_abcd: [Queues in Laravel](https://laraveldaily.com/course/laravel-queues?utm_source=github&utm_campaign=roadmap) <br>|
| Queueable Classes and Jobs |:book: [Creating Jobs](https://laravel.com/docs/queues#creating-jobs) <br>:book: [Queueing Notifications](https://laravel.com/docs/notifications#queueing-notifications) <br>:book: [Queued Event Listeners](https://laravel.com/docs/events#queued-event-listeners) <br>:book: [Queueing Mail](https://laravel.com/docs/mail#queueing-mail) <br>:clapper: [Laravel Queues 101: Example with Sending Emails](https://www.youtube.com/watch?v=rVx8xKisbr8) <br>|
| Job Dispatching, Batching and Chaining |:book: [Dispatching Jobs](https://laravel.com/docs/queues#dispatching-jobs) <br>|
| Processing Failed Jobs |:book: [Dealing with Failed Jobs](https://laravel.com/docs/queues#dealing-with-failed-jobs) <br>|
| Configuring Queues: Drivers, Redis, Supervisor |:book: [Running the Queue Worker](https://laravel.com/docs/queues#running-the-queue-worker) <br>:book: [Configuring Supervisor](https://laravel.com/docs/queues#supervisor-configuration) <br>|
| Laravel Horizon (optional, if you use Redis) |:book: [Laravel Horizon](https://laravel.com/docs/horizon) <br>|
| **API Advanced** ||
| Upload Files via API |:page_facing_up: [Laravel API: How to Upload File from Vue.js](https://blog.quickadminpanel.com/laravel-api-how-to-upload-file-from-vue-js/) <br>|
| Generate API Documentation |:page_facing_up: [Laravel API Documentation with OpenAPI/Swagger](https://blog.quickadminpanel.com/laravel-api-documentation-with-openapiswagger/) <br>:clapper: [Scribe: New Package for Laravel API Documentation](https://www.youtube.com/watch?v=PjwGI8c2IfA) <br>|
| API Versioning |:page_facing_up: [Versioning your REST API with Laravel](https://codimth.com/blog/web/laravel/versioning-your-rest-api-laravel) <br>:clapper: [Versioning your API: from V1 to V2 and Beyond [video from my course]](https://laraveldaily.com/lesson/laravel-api/versioning-v1-v2?utm_source=github&utm_campaign=roadmap) <br>|
| API with OAuth and Laravel Passport |:book: [Laravel Passport](https://laravel.com/docs/passport) <br> :clapper: [Laravel API Auth Demo: Passport, oAuth and Sanctum](https://www.youtube.com/watch?v=8myQdPL8I1s)|
| Only-API Projects with Front-end like Vue.js / React.js |:capital_abcd: [Vue.js 3 + Laravel 9 SPA: CRUD with Auth](https://laraveldaily.com/course/vue-laravel-spa?utm_source=github&utm_campaign=roadmap) <br>:capital_abcd: [React.js + Laravel: SPA CRUD with Auth](https://laraveldaily.com/course/react-laravel-spa?utm_source=github&utm_campaign=roadmap) <br>|
| Only-API Projects with Mobile Apps |:capital_abcd: [Flutter Mobile App with Laravel API](https://laraveldaily.com/course/flutter-laravel?utm_source=github&utm_campaign=roadmap) <br>:page_facing_up: [Using Sanctum to authenticate a mobile app](https://laravel-news.com/using-sanctum-to-authenticate-a-mobile-app) <br>|
| **(optional) Starter Kits: Laravel Jetstream and Fortify** ||
| Laravel Jetstream (requires Livewire/Inertia knowledge) |:book: [Laravel Jetstream](https://jetstream.laravel.com) <br>:capital_abcd: [Laravel Jetstream+Livewire: Real Mini-Project](https://laraveldaily.teachable.com/p/laravel-jetstream-livewire-project?utm_source=github&utm_campaign=roadmap) <br>:clapper: [Laravel Jetstream: How it Works and Example How to Customize](https://www.youtube.com/watch?v=d8YgWApHMfA) <br>|
| Laravel Fortify |:book: [Laravel Fortify](https://laravel.com/docs/fortify) <br>:clapper: [Laravel Fortify: Four Auth Things to Customize](https://www.youtube.com/watch?v=Vr4LJU3kw1g) <br>|
| **Payments** ||
| Laravel Cashier with Stripe/Paddle |:book: [Laravel Cashier (Stripe)](https://laravel.com/docs/billing) <br>:book: [Laravel Cashier (Paddle)](https://laravel.com/docs/cashier-paddle) <br>|
| Custom Payment Providers: PayPal, Mollie, etc |:page_facing_up: [Subscription billing with Laravel Cashier for Mollie](https://github.com/laravel/cashier-mollie) <br>:page_facing_up: [How To Integrate Paypal Payment Gateway In Laravel](https://websolutionstuff.com/post/how-to-integrate-paypal-payment-gateway-in-laravel) <br>|
| **Automated Testing Advanced** ||
| TDD: Test-Driven Development |:capital_abcd: [Build A Laravel App With TDD](https://laracasts.com/series/build-a-laravel-app-with-tdd) <br>:capital_abcd: [TDD With Laravel](https://tddwithlaravel.com/) <br>|
| Mocking |:book: [Mocking](https://laravel.com/docs/mocking) <br>|
| (optional) Laravel Dusk |:book: [Laravel Dusk](https://laravel.com/docs/dusk) <br>|
| **Full-Text Search** ||
| Laravel Scout |:book: [Laravel Scout](https://laravel.com/docs/scout) <br>|
| Drivers: ElasticSearch, Algolia or MeiliSearch |:page_facing_up: [ElasticSearch Driver for Laravel Scout](https://laravel-news.com/explorer) <br>:book: [Algolia: Scout Extended](https://www.algolia.com/doc/framework-integration/laravel/getting-started/introduction-to-scout-extended/?client=php) <br>:page_facing_up: [Full-Text Search with MeiliSearch and Laravel Scout](https://tighten.co/blog/full-text-search-with-meilisearch-and-scout/) <br>|
| **Laravel Packages** ||
| Contributing to Packages, making Pull Requests |:clapper: [How to Contribute to Laravel Docs (or any open-source repository)](https://www.youtube.com/watch?v=vEcT6JIFji0) <br>|
| Create Laravel Packages |:book: [Package Development](https://laravel.com/docs/packages) <br>:capital_abcd: [Laravel Package Development](https://laravelpackage.com/) <br>|


## Senior Level
Responsibility for architecture decisions on large projects

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__ 

| Topic | Learning Links |
| ----- | ----- |
| **PHP/Laravel Design Patterns** |:clapper: [Laravel Design Patterns - Bobby Bouwmann - Laracon EU 2018 Amsterdam](https://www.youtube.com/watch?v=qpo5KG0vIyE) <br>:capital_abcd: [Laracasts: Design Patterns in PHP](https://laracasts.com/series/design-patterns-in-php) <br>:clapper: [Colin Decarlo - Design Patterns with Laravel [Laracon 2018]](https://www.youtube.com/watch?v=e4ugSgGaCQ0) <br>:clapper: [Matt Stauffer - Patterns That Pay Off [Laracon 2018]](https://www.youtube.com/watch?v=enTb2E4vEos) <br>:capital_abcd: [Design Patterns in PHP](https://refactoring.guru/design-patterns/php) <br>:page_facing_up: [Design Patterns for Humans](https://github.com/kamranahmedse/design-patterns-for-humans) <br>|
| Creational Design Patterns |:page_facing_up: [Design Patterns: Creational](https://refactoring.guru/design-patterns/creational-patterns) <br>|
| Structural Design Patterns |:page_facing_up: [Design Patterns: Structural](https://refactoring.guru/design-patterns/structural-patterns) <br>|
| Behavioral Design Patterns |:page_facing_up: [Design Patterns: Behavioral](https://refactoring.guru/design-patterns/behavioral-patterns) <br>|
| **Well-written Code** ||
| SOLID Code |:capital_abcd: [SOLID Code in Laravel](https://laraveldaily.com/course/solid-laravel?utm_source=github&utm_campaign=roadmap) <br>:clapper: [Becoming a better developer by using the SOLID design principles by Katerina Trajchevska](https://www.youtube.com/watch?v=rtmFCcjEgEw) <br>:page_facing_up: [Writing Maintainable Code: SOLID Principles Explained in PHP (Laravel)](https://geekflare.com/php-solid-principles/) <br>:capital_abcd: [Laracasts: SOLID Principles in PHP](https://laracasts.com/series/solid-principles-in-php) <br>:clapper: [PHP Solid Principles [Playlist]](https://www.youtube.com/watch?v=ARxZV8OZ8Cg&list=PLNuh5_K9dfQ3jMU-2C2jYRGe2iXJkpCZj) <br>|
| Scalable Code |:capital_abcd: [Scaling Laravel](https://courses.serversforhackers.com/scaling-laravel) <br>:clapper: [Enterprise Laravel by Matt Stauffer](https://enterpriselaravel.com/) <br>:page_facing_up: [What the hell is scalable code anyway?](https://blog.sarasarya.com/what-the-hell-is-scalable-code-anyway-f6626ad78227) <br>|
| Maintainable Code |:capital_abcd: [10+ Laravel Refactoring Examples](https://laraveldaily.com/course/laravel-refactoring?utm_source=github&utm_campaign=roadmap) <br>:page_facing_up: [How would you know if you've written readable and easily maintainable code? [forum thread]](https://softwareengineering.stackexchange.com/questions/141005/how-would-you-know-if-youve-written-readable-and-easily-maintainable-code) <br>:page_facing_up: [Crafting maintainable Laravel applications](https://jasonmccreary.me/articles/crafting-maintainable-laravel-applications/) <br>:page_facing_up: [7 Golden Rules of Clean, Simple and Maintainable Code](https://shhetri.github.io/clean-code/#/) <br>|
| Best Practices and Standards |:page_facing_up: [Repository: alexeymezenin / laravel-best-practices](https://github.com/alexeymezenin/laravel-best-practices) <br>:capital_abcd: [PHP: The Right Way](https://phptherightway.com/) <br>:page_facing_up: [Reddit: What are your Laravel best practices?](https://www.reddit.com/r/laravel/comments/f34t86/what_are_your_laravel_best_practices/) <br>|
| **Large Datasets** ||
| Large Database Structures |:capital_abcd: [How to Structure Databases in Laravel](https://laraveldaily.com/course/laravel-database-structure?utm_source=github&utm_campaign=roadmap) <br>:capital_abcd: [GraphQL in Laravel From Scratch](https://laraveldaily.com/course/graphql-laravel?utm_source=github&utm_campaign=roadmap) <br>|
| NoSQL Solutions |:book: [MongoDB and Laravel Integration](https://www.mongodb.com/compatibility/mongodb-laravel-intergration) <br>:page_facing_up: [MongoDB + Laravel = Love — When to use NoSQL](https://faun.pub/when-to-use-nosql-getting-started-with-mongodb-in-laravel-f5376ceaf545) <br>|
| Eloquent/SQL Query Optimization |:capital_abcd: [Better Eloquent Performance](https://laraveldaily.com/course/eloquent-performance?utm_source=github&utm_campaign=roadmap) <br>:page_facing_up: [18 Tips to optimize laravel database queries](https://dudi.dev/optimize-laravel-database-queries/) <br>:page_facing_up: [Optimizing Laravel Part 2: Improving Query Performance with Database Indexing](https://deliciousbrains.com/optimizing-laravel-database-indexing-performance/) <br>:capital_abcd: [Eloquent Performance Patterns](https://eloquent-course.reinink.ca/) <br>|
| Scaling to Multiple Databases |:page_facing_up: [Scaling Laravel App with Multiple Databases](https://devdojo.com/bobbyiliev/scaling-laravel-app-with-multiple-databases) <br>:page_facing_up: [Multiple DB Connections in Laravel](https://fideloper.com/laravel-multiple-database-connections) <br>|
| **Working with High-Traffic Projects** ||
| Stability and Zero-Downtime Deployments |:book: [Laravel Deployer](https://github.com/deployphp/deployer) <br>:book: [Envoyer - Zero Downtime PHP Deployment](https://envoyer.io/) <br>|
| Performance Optimization and Caching |:capital_abcd: [Performant Laravel](https://serversforhackers.com/laravel-perf) <br>:page_facing_up: [The Ultimate Performance Checklist For Laravel Apps](https://laravel-news.com/performance-checklist) <br>:page_facing_up: [How to Optimize PHP Laravel Web Application for High Performance?](https://geekflare.com/laravel-optimization/) <br>|
| **Ensuring Code Quality** ||
| Writing Testable Code |:page_facing_up: [How to write testable code](https://dev.to/ddarrko/how-to-write-more-testable-code-oi7) <br>:page_facing_up: [Refactoring towards testability](https://madewithlove.com/blog/software-engineering/refactoring-untestable-code-towards-testability/) <br>|
| Continuous Integration and Continuous Delivery (CI/CD) |:page_facing_up: [How to create a CI/CD for a Laravel application using GitHub Actions](https://blog.logrocket.com/how-to-create-a-ci-cd-for-a-laravel-application-using-github-actions/) <br>:page_facing_up: [Configure Laravel 8 for CI/CD with Jenkins and GitHub — Part 1](https://faun.pub/configure-laravel-8-for-ci-cd-with-jenkins-and-github-part-1-58b9be304292) <br>:page_facing_up: [Build, Test, and Deploy Your Laravel Application With GitHub Actions](https://www.twilio.com/blog/build-test-deploy-laravel-application-github-actions) <br>|
