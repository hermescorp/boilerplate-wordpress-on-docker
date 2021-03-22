# boilerplate-wordpress-on-docker

A boilerplate for development of WordPress on Docker

# Usage

`.env`ファイルを作成し、`THEME_SLUG`を変更

```bash
$ cp .env{.example,}
```

このリポジトリを `upstream` として `clone`

```bash
$ git clone -o upstream git@github.com:hermescorp/boilerplate-wordpress-on-docker.git PROJECT_ROOT_DIRECTORY
```

該当ディレクトリに移動し、ビルド

```bash
$ cd PROJECT_ROOT_DIRECTORY
$ docker-compose build --no-cache 
```

dockerを起動

```bash
$ docker-compose up -d
```

ブラウザにて動作確認
※初回起動時は、インストール画面から始まる。ビルド直後だと、しばらく404になるので、待ってからアクセス。

```bash
$ open http://localhost:8080 # .envにてデフォルトで8080ポート指定。変更可能。
```

# Setup existing site
TBD
