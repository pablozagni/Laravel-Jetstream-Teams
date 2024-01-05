<h1>Laravel Jetstream Teams APP</h1>
<p>This APP is a basic startup for a Laravel Jetstream with Team management. User has t o verify email. When the user registers, it creates it's own team.</p>
<h2>Steps to create it</h2>
<ul>
    <li>composer create-project laravel/laravel example</li>
    <li>cd example</li>
    <li>composer require laravel/jetstream</li>
    <li>php artisan jetstream:install livewire --teams</li>
    <li>php artisan migrate</li>
</ul>

<h2>You should...</h2>
<ul>
    <li>composer install</li>
    <li>npm install</li>
    <li>php artisan migrate</li>
    <li>create .env</li>
    <li>php artisan config:cache</li>
    <li>npm run dev</li>
    <li>Enter the APP, register, verify email.</li>
    <li>Ready</li>
</ul>

<h2>Commit 1 - Standard views</h2>
<ul>
    <li>.env example</li>
    <li>PagesController created.</li>
    <li>All views has x-app-layout as parent, so all views has menu visible.</li>
    <li>Sample guest routes: Home / Contact.</li>
    <li>Registered AND VERIFIED user can access Dashboard an Team configuration.</li>
    <li></li>
</ul>
<p></p>
<p>Code by Pablo Zagni - <a href="https://www.z-system.com.ar">www.z-system.com.ar</a></p>