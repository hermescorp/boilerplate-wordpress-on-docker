# boilerplate-wordpress-on-docker

A boilerplate for development of WordPress on Docker

# Usage

`.env`$B%U%!%$%k$r:n@.$7!"(B`THEME_SLUG`$B$rJQ99(B

```
$ cp .env{.example,}
```

$B$3$N%j%]%8%H%j$r(B `upstream` $B$H$7$F(B `clone`

```
$ git clone -o upstream git@github.com:hermescorp/boilerplate-wordpress-on-docker.git PROJECT_ROOT_DIRECTORY
```

$B3:Ev%G%#%l%/%H%j$K0\F0$7!"%S%k%I(B

```
$ cd PROJECT_ROOT_DIRECTORY
$ docker-compose build --no-cache 
```

docker$B$r5/F0(B

```
$ docker-compose up -d
```

$B%V%i%&%6$K$FF0:n3NG'(B
$B"(=i2s5/F0;~$O!"%$%s%9%H!<%k2hLL$+$i;O$^$k!#%S%k%ID>8e$@$H!"$7$P$i$/(B404$B$K$J$k$N$G!"BT$C$F$+$i%"%/%;%9!#(B

```
$ open http://localhost:8080 # .env$B$K$F%G%U%)%k%H$G(B8080$B%]!<%H;XDj!#JQ992DG=!#(B
```

# Setup existing site
TBD
