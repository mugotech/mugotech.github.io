# MUGOTECH WEB SOLUTIONS
MugoTech - Website.

## Table of Contents

- [Features](#features)
- [System Requirements](#system-requirements)
- [Links](#links)
- [Installation](#installation)
- [Software Used](#software-used)
- [Bugs and Feedback](#bugs-and-feedback)

## Features
- Website for MugoTech

## System Requirements
- PHP > 7.2
- PHP Extensions: PDO, cURL, Bcmath, Mcrypt, XML, GD
- Node.js > 6.0
- Composer > 1.0.0
- Laravel > 6.x
- MySql > 14.0
- Apache > 2.4

## Software Used
- Laravel
- Bootstrap
- NodeJs
- CSS

## Links

**[Staging Site](http://vakara.africa)**

**[Developer FB Page](https://facebook.com/mugotech)**


## Installation

Clone repository

`$ git clone git@bitbucket.org:teammugotech/mugotech.git`

Change into the working directory

`$ cd mugotech`

Copy `.env.example` to `.env` and modify according to your environment

`$ cp .env.example .env`

Install composer dependencies

`$ composer install --prefer-dist`

Install node dependencies

`$ npm install`

Change folder permissions

`$ sudo chown -R www-data:www-data storage && sudo chown -R www-data:www-data vendor && sudo chown -R www-data:www-data public && sudo chown -R www-data:www-data node_modules && sudo chown -R www-data:www-data bootstrap/cache && sudo chmod -R 775 storage bootstrap/cache && sudo chmod -R 775 storage public`

An application key can be generated with the command

`$ php artisan key:generate`

Run these commands to create the tables within the defined database and populate seed data

`$ php artisan migrate --seed`


## Bugs and Feedback

For bugs, questions and discussions please email me at [juniormachaka@gmail.com](mailto:juniormachaka@gmail.com).
