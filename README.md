# Orange Box

A feature filled Laravel Starter application

## Packages

Required packages please visit the package repositories for install info

- Jarvis [documentation / info](https://github.com/shawnsandy/jarvis)
- DashAuth [documentation / info](https://github.com/shawnsandy/jarvis)  
- ImgFly [documentation / info](https://github.com/shawnsandy/jarvis)  
- Firewall [documentation / info](https://github.com/shawnsandy/jarvis) 
- Tracker [documentation / info](https://github.com/shawnsandy/jarvis)
- Bouncer [documentation / info](https://github.com/shawnsandy/jarvis)
- Backstory [documentation / info](https://github.com/shawnsandy/jarvis)
- Laravel Collective HTML [documentation / info](https://github.com/shawnsandy/jarvis)

## Install

- Clone the repository https://github.com/shawnsandy/obs.git

``` bash
git clone https://github.com/shawnsandy/obs.git
```
- Install composer

``` bash
composer install
```

- Complete setup : copies the env and generate the `APP_KEY`

```
composer setup
```

- Edit your `.env` database settings

- Run the migrations `php artisan migrate`


## Quickstart

__Config__

Add the following to your `.env` and edit accordingly

- Validation Key is used for Jarvis setup
- SUPERDAMIN_EMAIL for DashAuth

``` env

VALIDATION_KEY=1234567890_mykey

SUPER_ADMIN_EMAIL=shawnsandy04@gmail.com

```
