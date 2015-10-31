# nodejs-scraping
Try scraping by node.js

# Usage
## get_syosetu_top.js
```
$ node app/get_syosetu_top.js
```

## get_syosetu_with_logged_in.js
```
$ export SYOSETU_ID="your user id"
$ export SYOSETU_PW="your password"
$ node app/get_syosetu_with_logged_in.js
```

## get_syosetu_recommend.js
```
$ node app/get_syosetu_recommend.js
```

## get_syosetu_novel_top.js
```
$ node app/get_syosetu_novel_top.js
```

## store_syosetu_top.js
```
$ npm i sequelize-cli -g
$ #sequelize migration:create
$ #sequelize init
$ sequelize db:migrate
$ node app/store_syosetu_top.js
```

