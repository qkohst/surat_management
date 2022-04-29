<div id="top"></div>

# Mail Management System

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about">About The Project</a>
         <ul>
        <li><a href="#features">Features</a></li>
      </ul>
    </li>
    <li>
      <a href="#installation">Installation</a>
    </li> 
    <li>
      <a href="#screenshoot">Screenshoot</a>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<p id="about">
This system is built with the laravel framework and MySQL database using a template from the admin LTE.
</p>

<h4 id="features">
    The features of this system globally include:
</h4>
<ul>
    <li>
       Multi user (Admin, Officer).
    </li>
    <li>
       Manage incoming and outgoing mail data.
    </li>
    <li>
       Upload incoming and outgoing mail files
    </li>
    <li>
       Manage mail Classification
    </li>
    <li>
       Print the agenda for incoming and outgoing letters
    </li>
    <li>
       View the gallery of incoming and outgoing mail files.
    </li>
</ul>

## Installation 
To run the application on your computer, please follow the following command : 

1. Clone the repo
   ```sh
   $ git clone https://github.com/qkohst/surat_management.git
   ```
2. Change directory in project which already clone
   ```sh
   $ cd surat_management
   ```
3. Install Composer packages
   ```sh
   $ composer install
   ```
4. Create database on your computer
5. Create a copy of your .env file 
   ```sh
   $ cp .env.example .env
   ```
6. In the .env file, add database information to allow Laravel to connect to the database
   ```sh
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE={database-name}
   DB_USERNAME={username-database}
   DB_PASSWORD={password-database}
   ```
7. Generate an app encryption key
   ```sh
   $ php artisan key:generate
   ```
8. Import ``manajemen_surat.sql``
9. Running project
    ```sh
    $ php artisan serve
    ```
<p align="right">(<a href="#top">back to top</a>)</p>

<div id="screenshoot"></div>

## Screenshoot 

![0](https://user-images.githubusercontent.com/57386598/94008594-75851380-fdcd-11ea-9c4b-8106a94a81c1.png)

![1](https://user-images.githubusercontent.com/57386598/94008605-79b13100-fdcd-11ea-983f-6e89342e3f16.png)

![2](https://user-images.githubusercontent.com/57386598/94008611-7d44b800-fdcd-11ea-9301-b40ad82f967d.png)

![3](https://user-images.githubusercontent.com/57386598/94008619-80d83f00-fdcd-11ea-8292-0778a54fd2d2.png)

![4](https://user-images.githubusercontent.com/57386598/94008629-83d32f80-fdcd-11ea-909f-fe1b7c89b1f6.png)

![5](https://user-images.githubusercontent.com/57386598/94008645-8a61a700-fdcd-11ea-8ce7-e52e8ce2e5cf.png)

![6](https://user-images.githubusercontent.com/57386598/94008655-8e8dc480-fdcd-11ea-855e-b525dc141c39.png)

<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of any modern web application framework, making it a breeze to get started learning the framework.

If you're not in the mood to read, [Laracasts](https://laracasts.com) contains over 1100 video tutorials on a range of topics including Laravel, modern PHP, unit testing, JavaScript, and more. Boost the skill level of yourself and your entire team by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for helping fund on-going Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell):

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[British Software Development](https://www.britishsoftware.co)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- [UserInsights](https://userinsights.com)
- [Fragrantica](https://www.fragrantica.com)
- [SOFTonSOFA](https://softonsofa.com/)
- [User10](https://user10.com)
- [Soumettre.fr](https://soumettre.fr/)
- [CodeBrisk](https://codebrisk.com)
- [1Forge](https://1forge.com)
- [TECPRESSO](https://tecpresso.co.jp/)
- [Runtime Converter](http://runtimeconverter.com/)
- [WebL'Agence](https://weblagence.com/)
- [Invoice Ninja](https://www.invoiceninja.com)
- [iMi digital](https://www.imi-digital.de/)
- [Earthlink](https://www.earthlink.ro/)
- [Steadfast Collective](https://steadfastcollective.com/)

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
