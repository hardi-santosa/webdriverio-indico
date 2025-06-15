# webdriverio-indico
What is this repository for?
This is repo use for selection SQA on indico

how to setup webdriverio

1. go to folder repo and init
```sh
$ cd webdriverio-indico
$ npm init -y # atau yarn init -y
```
2. install wdio
```sh
$ npm install --save-dev @wdio/cli
npx wdio config
```
Selama proses konfigurasi npx wdio config, Anda akan ditanya beberapa pertanyaan. Berikut adalah respons yang direkomendasikan untuk aplikasi Android:

Where do you want to run your tests? On my local machine

Which framework do you want to use? Pilih Mocha (atau Jasmine/Cucumber sesuai preferensi Anda).

Do you want to use a compiler? No (untuk setup dasar JavaScript).

Where are your tests located? ./test/specs/**/*.js (default)

Which reporter do you want to use? spec (default, bagus untuk awal)

Do you want to add a service to your test setup? Pilih appium.

What is the base url of your application? http://localhost (default)

Ini akan membuat file wdio.conf.js di root proyek Anda dan menginstal dependensi yang diperlukan.


