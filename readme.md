# Laravel Learning Path

This repository contains the **ordered** list of Laravel topics to learn, step-by-step, with related links.

If you want to add a topic, link, or any other suggestion, please open Issues or Pull Requests.

**Notice 1**: The same table below is also available as a database, so you would be able to transform it to any other format you want - PDF, chart, etc. See file [roadmap.sql](roadmap.sql)

**Notice 2**: This content was filled into an adminpanel generated with our [QuickAdminPanel](https://quickadminpanel.com) - here's a [video demo of that process on Youtube](https://www.youtube.com/watch?v=i2ElUDUDRms). By purchasing QuickAdminPanel, you support my free initiatives, like this Roadmap.

--- 

## Beginner Level
Create your very first simple Laravel project

| Topic | Learning Links |
| ----- | ----- |
| **Routing and Controllers: Basics** |  |
| Callback Functions and Route::view() |[Official Docs: Basic Routing](https://laravel.com/docs/8.x/routing#basic-routing) <br>[Official Docs: View Routes](https://laravel.com/docs/8.x/routing#view-routes) <br>|
| Routing to a Single Controller Method |[Official Docs: Basic Controllers with Routes](https://laravel.com/docs/8.x/controllers#basic-controllers) <br>|
| Route Parameters |[Official Docs: Route Parameters](https://laravel.com/docs/8.x/routing#route-parameters) <br>|
| Route Groups |[Official Docs: Route Groups](https://laravel.com/docs/8.x/routing#route-groups) <br>|
| **Blade Basics** |  |
| Displaying Variables in Blade |[Official Docs: Blade: Displaying Data](https://laravel.com/docs/8.x/blade#displaying-data) <br>|
| Blade If-Else and Loop Structures |[Official Docs: Blade: If-Statements](https://laravel.com/docs/8.x/blade#if-statements) <br>[Official Docs: Blade Loops](https://laravel.com/docs/8.x/blade#loops) <br>|
| Layout: @include, @extends, @section, @yield |[Official Docs: Blade: Layout Using Template Inheritance](https://laravel.com/docs/8.x/blade#layouts-using-template-inheritance) <br>|
| Blade Components |[Official Docs: Blade Components](https://laravel.com/docs/8.x/blade#components) <br>[Video: Laravel Blade Components: Two Examples - Laravel Breeze/UI](https://www.youtube.com/watch?v=HybWBINeXMw) <br>|
| **Auth Basics** |  |
| Starter Kits: Breeze (Tailwind) or Laravel UI (Bootstrap) |[Official Docs: Laravel Breeze Official Documentation](https://laravel.com/docs/8.x/starter-kits#laravel-breeze) <br>[Official Docs: Laravel UI: Official Github Page](https://github.com/laravel/ui) <br>|
| Default Auth Model and Access its Fields from Anywhere |[Official Docs: Retrieving the Authenticated User](https://laravel.com/docs/8.x/authentication#retrieving-the-authenticated-user) <br>|
| Check Auth in Controller / Blade |[Official Docs: Determining If The Current User Is Authenticated](https://laravel.com/docs/8.x/authentication#determining-if-the-current-user-is-authenticated) <br>[Official Docs: Blade: Authentication Directives](https://laravel.com/docs/8.x/blade#authentication-directives) <br>|
| Auth Middleware |[Official Docs: Protecting Routes](https://laravel.com/docs/8.x/authentication#protecting-routes) <br>|
| **Database Basics** |  |
| Database Migrations |[Official Docs: Database Migrations](https://laravel.com/docs/8.x/migrations) <br>|
| Basic Eloquent Model and MVC: Controller -> Model -> View |[Official Docs: Eloquent: Getting Started](https://laravel.com/docs/8.x/eloquent) <br>|
| Eloquent Relationships: belongsTo / hasMany / belongsToMany |[Official Docs: Eloquent Relationships: One-to-Many](https://laravel.com/docs/8.x/eloquent-relationships#one-to-many) <br>[Official Docs: Eloquent Relationships: BelongsTo](https://laravel.com/docs/8.x/eloquent-relationships#one-to-many-inverse) <br>[Official Docs: Eloquent Relationships: Many-to-Many](https://laravel.com/docs/8.x/eloquent-relationships#many-to-many) <br>|
| Eager Loading and N+1 Query Problem |[Official Docs: Relationships: Eager Loading](https://laravel.com/docs/8.x/eloquent-relationships#eager-loading) <br>|
| **Full Simple CRUD** |  |
| Route Resource and Resourceful Controllers |[Official Docs: Laravel Resource Controllers](https://laravel.com/docs/8.x/controllers#resource-controllers) <br>[Article: Simple Laravel CRUD with Resource Controllers [digitalocean.com]](https://www.digitalocean.com/community/tutorials/simple-laravel-crud-with-resource-controllers) <br>|
| Forms, Validation and Form Requests |[Official Docs: Laravel Validation](https://laravel.com/docs/8.x/validation) <br>|
| File Uploads and Storage Folder Basics |[Official Docs: Filesystem: File Uploads](https://laravel.com/docs/8.x/filesystem#file-uploads) <br>|
| Table Pagination |[Official Docs: Database Pagination](https://laravel.com/docs/8.x/pagination) <br>|


## Advanced Beginner Level
The goal of this level is to find the first job or freelance gig

| Topic | Learning Links |
| ----- | ----- |
| **Routing Advanced** |  |
| Route Naming |[Official Docs: Names Routes](https://laravel.com/docs/8.x/routing#named-routes) <br>|
| Route Model Binding |[Official Docs: Route Model Binding](https://laravel.com/docs/8.x/routing#route-model-binding) <br>|
| Route Redirect |[Official Docs: Redirect Routes](https://laravel.com/docs/8.x/routing#redirect-routes) <br>|
| **Middleware** |  |
| Create Custom Middleware Class |[Official Docs: Defining Middleware](https://laravel.com/docs/8.x/middleware#defining-middleware) <br>|
| **Database Advanced** |  |
| Database Seeders and Factories |[Official Docs: Database: Seeding](https://laravel.com/docs/8.x/seeding) <br>[Official Docs: Defining Model Factories](https://laravel.com/docs/8.x/database-testing#defining-model-factories) <br>|
| Eloquent Query Scopes |[Official Docs: Eloquent: Query Scopes](https://laravel.com/docs/8.x/eloquent#query-scopes) <br>|
| Polymorphic relationships |[Official Docs: Polymorphic Relationships](https://laravel.com/docs/8.x/eloquent-relationships#polymorphic-relationships) <br>|
| Eloquent Accessors and Mutators |[Official Docs: Accessors & Mutators](https://laravel.com/docs/8.x/eloquent-mutators#accessors-and-mutators) <br>|
| Eloquent Collections |[Official Docs: Eloquent Collections](https://laravel.com/docs/8.x/eloquent-collections) <br>[Official Docs: General Laravel Collections](https://laravel.com/docs/8.x/collections) <br>|
| Soft Deletes |[Official Docs: Soft Deleting](https://laravel.com/docs/8.x/eloquent#soft-deleting) <br>|
| **Auth Advanced** |  |
| Authorization: Roles/Permissions, Gates, Policies |[Official Docs: Authorization](https://laravel.com/docs/8.x/authorization) <br>[Video: Laravel Roles and Permissions: All CORE Things You Need To Know](https://www.youtube.com/watch?v=kZOgH3-0Bko) <br>|
| Authorization: Extra Packages - Spatie Permission, Bouncer, etc |[Video: Spatie Laravel Permission: Example Project Review](https://www.youtube.com/watch?v=NgToi0uiMNQ) <br>[Article: Two Best Laravel Packages to Manage Roles/Permissions](https://laravel-news.com/two-best-roles-permissions-packages) <br>[Official Docs: spatie/laravel-permission](https://github.com/spatie/laravel-permission) <br>[Official Docs: JosephSilber/bouncer](https://github.com/JosephSilber/bouncer) <br>|
| Authentication: Email Verification |[Official Docs: Email Verification](https://laravel.com/docs/8.x/verification) <br>|
| **File Uploads Advanced** |  |
| Drivers and Disks, Example of Amazon S3 |[Official Docs: File Storage](https://laravel.com/docs/8.x/filesystem) <br>[Video: Laravel: How to Upload Files to Amazon S3](https://www.youtube.com/watch?v=xZQM9q_QxMA) <br>|
| Extra Packages: Spatie Medialibrary, Intervention Image, etc |[Official Docs: spatie/laravel-medialibrary](https://github.com/spatie/laravel-medialibrary) <br>[Official Docs: intervention/image](https://github.com/Intervention/image) <br>|
| **API Basics** |  |
| API Routes and Controllers |[Official Docs: API Resource Routes](https://laravel.com/docs/8.x/controllers#api-resource-routes) <br>[Official Docs: Default Route Files](https://laravel.com/docs/8.x/routing#the-default-route-files) <br>|
| Working with API Clients: Postman or Alternatives |[Official Docs: Postman API Client](https://www.postman.com/product/api-client/) <br>|
| API Eloquent Resources |[Official Docs: Eloquent: API Resources](https://laravel.com/docs/8.x/eloquent-resources) <br>|
| API Auth with Sanctum |[Official Docs: Laravel Sanctum](https://laravel.com/docs/8.x/sanctum) <br>|
| API Error Handling and Status Codes |[Video: Laravel API 404 Error: Customize Exception Message](https://www.youtube.com/watch?v=SlBJrLnyoMk) <br>[Article: HTTP Status Codes](https://httpstatuses.com/) <br>|
| **Debugging Errors** |  |
| Log Files in Laravel |[Official Docs: Logging](https://laravel.com/docs/8.x/logging) <br>|
| Try-Catch and Laravel Exceptions |[Official Docs: Error Handling](https://laravel.com/docs/8.x/errors) <br>[Video: Exceptions in Laravel: Why/How to Use and Create Your Own](https://www.youtube.com/watch?v=RTTXZVIL6tw) <br>|
| Local Debugging Tools: Debugbar, Telescope, Ray |[Official Docs: barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) <br>[Official Docs: Laravel Telescope](https://laravel.com/docs/8.x/telescope) <br>[Official Docs: Spatie Ray (Premium Tool)](https://myray.app/) <br>[Video: Debug Eloquent Queries from API: Laravel Telescope](https://www.youtube.com/watch?v=SR3RzIfeozI) <br>[Video: Spatie Ray: Laravel Debugging with Pleasure](https://www.youtube.com/watch?v=n4pMxyAXeqY) <br>|
| Customizing Error Pages and Messages |[Official Docs: Custom HTTP Error Pages](https://laravel.com/docs/8.x/errors#custom-http-error-pages) <br>[Video: Laravel Error Pages: Change Text or Customize Layouts](https://www.youtube.com/watch?v=iMAFUi6Z57k) <br>|
| (optional) Third Party Bug Trackers: Bugsnag, Flare, Sentry, Rollbar |[Official Docs: Bugsnag Laravel](https://docs.bugsnag.com/platforms/php/laravel/) <br>[Official Docs: Flare Homepage](https://flareapp.io/) <br>[Official Docs: Sentry Laravel](https://docs.sentry.io/platforms/php/guides/laravel/) <br>[Official Docs: Rollbar Laravel](https://docs.rollbar.com/docs/laravel) <br>[Video: Bug Tracking in Laravel: Bugsnag vs Flare [Demo/Review]](https://www.youtube.com/watch?v=88UqUXhWwGA) <br>|
| **Sending Email** |  |
| Mailables and Mail Facade |[Official Docs: Mail & Mailables](https://laravel.com/docs/8.x/mail) <br>|
| Configure Drivers/Services: Mailgun, Mailtrap, etc |[Article: How to Send Email From Laravel, and Why We Need 3rd Party Providers For It](https://laraveldaily.com/how-to-send-email-from-laravel-and-why-we-need-3rd-party-providers-for-it/) <br>[Official Docs: Mail: Drivers Prerequisites](https://laravel.com/docs/8.x/mail#driver-prerequisites) <br>|
| Notifications System: Email, SMS, Slack, etc. |[Official Docs: Notifications](https://laravel.com/docs/8.x/notifications) <br>|
| **Automated Testing with PHPUnit** |  |
| "Smoke" Tests to Check if Pages are Loading |[Official Docs: Testing: Getting Started](https://laravel.com/docs/8.x/testing) <br>[Course: Laravel: PHPUnit Testing for Beginners](https://laraveldaily.teachable.com/p/laravel-phpunit-testing-for-beginners) <br>|
| Configure Testing Database and Test CRUD Operations |[Official Docs: Database Testing](https://laravel.com/docs/8.x/database-testing) <br>|
| **Deployment and Version Control** |  |
| Git Version Control |[Official Docs: Git](https://git-scm.com/) <br>[Video: Git in Laravel. Part 1 - Branches: Main, Develop and Feature](https://www.youtube.com/watch?v=AmScEC-_72I) <br>|
| Deployment on Live Servers |[Official Docs: Deployment](https://laravel.com/docs/8.x/deployment) <br>[Article: How to Deploy Laravel Projects to Live Server: The Ultimate Guide](https://laraveldaily.com/how-to-deploy-laravel-projects-to-live-server-the-ultimate-guide/) <br>[Article: What Server is Needed to Deploy Laravel Projects](https://laraveldaily.com/what-server-is-needed-to-deploy-laravel-projects/) <br>[Video: How we Deploy Laravel: Branches, Staging Servers, Forge and Envoyer](https://www.youtube.com/watch?v=8DVuVftFZcQ) <br>|


## (WORK IN PROGRESS) Mid Level


| Topic | Learning Links |
| ----- | ----- |
| **(optional) Starter Kits: Laravel Jetstream and Fortify** |  |
| **Events and Listeners** |  |
| **Routing Extra Features** |  |
| Route Caching ||
| Rate Limiting ||
| **Various Extra Features** |  |
| Invokable controllers ||
| **Blade Extra Features** |  |
| Custom Blade Directives ||
| **API Advanced** |  |
| **Front-end Basics: Vue.js or Similar Alternative** |  |
| **Jobs and Queues** |  |
| Laravel Horizon (optional, if you use Redis) |[Official Docs: Laravel Horizon](https://laravel.com/docs/8.x/horizon) <br>|
| **Payments** |  |


## (TO BE DONE LATER) Senior Level


| Topic | Learning Links |
| ----- | ----- |


