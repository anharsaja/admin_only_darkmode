
# Admin Dashboard
## Laravel

Tampilan AdminDashboard only 


## Screenshots

![App Screenshot](./public/build/images/screenshot_1.png)
![App Screenshot](./public/build/images/screenshot_2.png)


## Run Locally

Clone the project

```bash
  git clone git@github.com:anharsaja/admin_only_darkmode.git
```

Go to the project directory

```bash
  cd admin_only_darkmode
```

Install dependencies
```bash
  composer update
```

Buat database dan kaitkan pada .ENV
```SQL
  php artisan migrate
```
```bash
    php artisan db:seed
```

Start the server

```bash
  php artisan serve
```

## Demo

http://localhost:8000


