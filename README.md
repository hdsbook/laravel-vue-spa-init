# Laravel Vue spa init project

請依序運行以下指令以啟動網站：

```shell
touch database/spa.sqlite
composer update
npm install
php artisan migrate
php artisan serve
```

參考資料：https://blog.johnsonlu.org/building-a-vue-spa-with-laravel/


<!--
部署步驟：
1. composer require laravel/ui
2. php artisan ui vue
3. npm install vue-router --save-dev
4. init spa setting
 -->