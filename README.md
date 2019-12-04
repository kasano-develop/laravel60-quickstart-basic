
# If you wanna run...
- [host] docker-compose up -d --build
- [host] docker-compose exec app ash
- [app(/work)] composer install
- [app(/work)] cp .env.example .env
- [app(/work)] php artisan key:generate
- [app(/work)] php artisan migrate


# References

- laravel on docker
  - https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4
  - https://qiita.com/ucan-lab/items/36f6e89abad26a68f69a

- first setting
  - https://mokabuu.com/it/php/%E3%80%90php%E3%80%91laravel%E3%81%A7-vendor%E4%BB%A5%E4%B8%8B%E3%81%AE%E3%83%87%E3%82%A3%E3%83%AC%E3%82%AF%E3%83%88%E3%83%AA%E3%81%8C%E8%A6%8B%E3%81%A4%E3%81%8B%E3%82%89%E3%81%AA%E3%81%84%E6%99%82
  - https://www.kabanoki.net/2524/
  - https://traveler0401.com/laravel-shoki-500-error/

