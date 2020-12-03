# Live Chat with Laravel 7 + Livewire + Pusher
_It is a Real Time Chat with Push notifications (pusher), it is an example Application for the demonstration of the operation of Laravel 7 with Livewire and Pusher._

## Content

_The following tools have been used for this project: _
* [Laravel] (https://laravel.com/) - The most used web framework currently, and my favorite !.
* [Livewire] (https://laravel-livewire.com/) - If you don't know what it is, with this project you will see it in a ** Practical ** way.
* [Pusher] (https://pusher.com/) - Sending Push Notifications on the Web (easy integration with Laravel)

### Livewire
It is used for your demonstration of capabilities. It is a complement that, from my point of view, is here to stay. With [Livewire] (https://laravel-livewire.com/) you can, in a super easy and fast way, create VUE | React | Angular but without leaving the ** Laravel ** line.

Can you drive

* Events
* Actions
* and much more

** Without the need for you to learn or have to use other languages ​​outside of PHP with Laravel ** (and a little bit of JS)

### Pusher
_The free Pusher service with Laravel is used to send Push._

_ [Pusher] (https://pusher.com/) is free to send up to 200,000 notifications per day per channel_

With [Pusher] (https://pusher.com/) you can transform your web application with Laravel into a "LIVE" application, generating "Push" notifications in real time that favor the dynamics of your website. ** Your customers will thank you **.

## Captures

![ScreenShot](https://raw.githubusercontent.com/emanuelnogueiras/laravel-chat/master/2020-03-16%2015_42_57-Window.png)


## Demonstration Video
_Here I leave you a video of the operation and some explanations of this project_

[![Watch the video](https://raw.githubusercontent.com/emanuelnogueiras/laravel-chat/publico/captura_video.png)](https://www.youtube.com/watch?v=bvAPf8z_bDk)

## How to install and demonstration ?
After clone or download this repository, next step is install all dependency required by laravel and laravel-mix.

```shell
# install composer-dependency
$ composer install
# install npm package
$ npm install
# build dev 
$ npm run dev
```

Before we start web server make sure we already generate app key, configure `.env` file and do migration.

```shell
# create copy of .env
$ cp .env.example .env
# create laravel key
$ php artisan key:generate
# laravel migrate
$ php artisan migrate
```
In .env don't forget for update
```shell script
BROADCAST_DRIVER=pusher

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_APP_CLUSTER=ap1
``` 
