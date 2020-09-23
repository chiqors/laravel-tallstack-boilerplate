<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel TallStack

A front-end preset for Laravel to scaffold an application using the [TALL stack](https://tallstack.dev), jumpstarting your application's development.

If you're not familiar with the name, it's an acronym that describes the main technologies involved in the stack:
- [Tailwind CSS](https://tailwindcss.com)
- [Alpine.js](https://github.com/alpinejs/alpine)
- [Laravel](https://laravel.com)
- [Livewire](https://laravel-livewire.com)

Some notable features of this package include:
- Views extending a default layout
- Front-end assets like Tailwind CSS and Alpine.js compiled with Laravel Mix
- Tailwind-powered pagination views
- The [Tailwind UI](https://tailwindui.com) and Tailwind's [Custom Forms](https://github.com/tailwindcss/custom-forms) extensions available out-of-the-box

> **Note**: If you're looking for an application boilerplate that supports the TALL stack, you should check out [Laravel Jetstream](https://github.com/laravel/jetstream). It comes with authentication scaffolding, account management, teams support.

## Installation

This preset is intended to be installed into a fresh Laravel application. Follow [Laravel's installation instructions](https://laravel.com/docs/8.x/installation) to ensure you have a working environment before continuing.

### Installation (without auth)

Then simply run the following commands:
```bash
git clone https://github.com/chiqors/laravel-tallstack-boilerplate.git
composer install
npm install
npm run dev
```

### Installation

Some notable features of the authentication scaffolding include:
- Powered by Livewire components and single action controllers
- Bundled with pre-written tests

All routes, components, controllers and tests are published to your application. The idea behind this is that you have full control over every aspect of the scaffolding in your own app, removing the need to dig around in the vendor folder to figure out how things are working.

## CSS purging

Tailwind uses PurgeCSS to remove any unused classes from your production CSS builds. You can modify or remove this behaviour in the `purge` section of your `tailwind.config.js` file. For more information, please see the [Tailwind documentation](https://tailwindcss.com/docs/controlling-file-size/).

## Removing the package

If you don't want to keep this package installed once you've installed the preset, you can safely remove it. Unlike the default Laravel presets, this one publishes all the auth logic to your project's `/app` directory, so it's fully redundant.

## Credits

- [Dan Harrin](https://github.com/DanHarrin)
- [Liam Hammett](https://github.com/imliam)
- [Ryan Chandler](https://github.com/ryangjchandler)
- [Tailwind UI](https://tailwindui.com) for the default authentication and pagination views
- [All Contributors](../../contributors)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
