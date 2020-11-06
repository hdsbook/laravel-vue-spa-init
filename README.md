# Laravel Vue SPA 初始空白專案

依序運行以下指令即可啟動網站：

```shell
touch database/spa.sqlite
composer update
npm install
npm run dev
php artisan migrate
php artisan serve
```

## 相依套件、引入方式備註(不需執行)

- laravel/ui
  - `composer require laravel/ui`
- vue
  - `php artisan ui vue`
- vue-router
  - `npm install vue-router --save-dev`

## 參考資料：

https://blog.johnsonlu.org/building-a-vue-spa-with-laravel/


<!--
部署步驟：
1. composer require laravel/ui
2. php artisan ui vue
3. npm install vue-router --save-dev
4. init spa setting
 -->