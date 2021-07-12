# Gitbook theme for BingoPaaS Docs

![Image](https://github.com/tonyyls/gitbook-plugin-theme-fexa/blob/master/preview.png)

## Usage

Add the theme to your book's configuration `book.json` or `book.js`:

```js
{
    "plugins": [
        "theme-beauty"
    ],
    "variables": {
        "themeFexa":{
            "nav":[
                {
                    "url":"http://...",
                    "target":"_blank",
                    "name": "简易教程"
                }
            ]
        },
    },
    "pluginsConfig": {
        "theme-beauty":{
            "search-placeholder":"输入关键字搜索", //搜索框提示信息
            "logo":"./logo.png", //logo地址
            "favicon": "./favicon.ico" //ico地址
        }
    }
},
```

Install by command:

``` bash
gitbook install
```


Enjoy!