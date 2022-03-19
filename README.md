<img width="200px" src="https://github.com/SoraY677/docker_x_wordpress/blob/main/Doc/image/horizontal-logo-monochromatic-white%20.png?raw=true">

<img width="200px" src="https://github.com/SoraY677/docker_x_wordpress/blob/main/Doc/image/WordPress-logotype-standard.png?raw=true">

# 目的

- Docker × WordPressの練習・知見としての記録

# コマンド

## 起動

```bash
# 起動
docker-compose up -d

# 設定ファイルのコピー
docker cp ./setting/var/www/html/wp-includes/functions.php docker_x_wordpress-wordpress-1:/var/www/html/wp-includes/functions.php

```

## 再起動

```bash
docker-compose reset
```
# 知見

[github wiki](https://github.com/SoraY677/docker_x_wordpress/wiki)

