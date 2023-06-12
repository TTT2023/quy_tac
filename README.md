# quy_tac
quy tắc, 1 số cú pháp, tiện ích viết 

<a href=#><img src="contributions.svg"></a>



- **Variable configuration**

  ```
  APP_NAME=Laravel
  APP_ENV=production
  APP_KEY=base64:cXdsNTZkbWduMjNyOHhiZmJyNzltc2JtaXUwejFud3Q=
  APP_DEBUG=true APP_URL=http://localhost
  DB_CONNECTION=mysql
  DB_HOST=containers-us-west-129.railway.app
  DB_PORT=6776 DB_DATABASE=railway
  DB_USERNAME=root
  DB_PASSWORD=
  NIXPACKS_BUILD_CMD=composer install && php artisan key:generate && php artisan migrate && php artisan db:seed  && php artisan storage:link && php artisan passport:keys && php artisan optimize && php artisan config:clear && php artisan cache:clear && php artisan migrate --force && npm install bower && ./node_modules/bower/bin/bower install && npm run prod
  ```

