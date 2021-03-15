# mindmap
{% simplemindmap style={"height":"500px"} %}
```markdown
* 利用靜態網頁產生心智圖
    * 目的
      * 想做紀錄整理
      * 可以線上看 
    * 產生靜態網頁工具
        * gitbook
            * simplemindmap 
            * [mindmaps](https://github.com/aleen42/gitbook-mindmaps)
            * 缺點
               * 僅支援文字,markdown語法都不支援
               * 要編譯會花很久時間
        * mddoc
          * 沒找到可以用的plugin  
        * hugo
          * 沒找到可以用的plugin
          * 中文搜尋需要支援
    * 用markdown產生lib
        * [Mark-Mind](https://github.com/MarkMindLtd/Mark-Mind/blob/main/README%20-%20zh.md)
          * 套裝軟體
          * 可以匯出markdown文件
        * [markmap](https://github.com/gera2ld/markmap)
            * markdown轉成心智圖
            * 大都支援markdown原有語法,[demo](https://markmap.js.org/repl/)
            * [vscode套件](https://marketplace.visualstudio.com/items?itemName=gera2ld.markmap-vscode)

```
{% endsimplemindmap %}


## gitbook目前使用plugin

- 目前發現與心智圖套件有衝突,以下不同共用
  - "splitter"

```
 "plugins": [
        "simple-mind-map",
        "-lunr",
        "-search",
        "-highlight",
        "-livereload",
        "search-plus@^1.0.3",
        "github@^2.0.0",
        "github-buttons@2.1.0",
        "edit-link@^2.0.2",
        "prism@^2.1.0",
        "prism-themes@^0.0.2",
        "advanced-emoji@^0.2.1",
        "anchors@^0.7.1",
        "include-codeblock@^3.0.2",
        "tbfed-pagefooter@^0.0.1",
        "favicon@^0.0.2",
        "todo@^0.1.3",
        "code"
        
    ],
    "pluginsConfig": {
        "theme-default": {
            "showLevel": true
        },
        "prism": {
            "css": [
                "prism-themes/themes/prism-base16-ateliersulphurpool.light.css"
            ]
        },
        "github": {
            "url": "https://csongs.io/gitbook-sample/"
        },
        "github-buttons": {
            "repo": "csongs/gitbook-sample",
            "types": [
                "star"
            ],
            "size": "small"
        },
        "include-codeblock": {
            "template": "ace",
            "unindent": true,
            "edit": true
        },
        "simple-page-toc": {
            "maxDepth": 3,
            "skipFirstH1": true
        },
        "edit-link": {
            "base": "https://github.com/csongs/gitbook-sample/edit/master",
            "label": "edit page"
        },
        "favicon": {
            "shortcut": "favicon.ico",
            "bookmark": "favicon.ico"
        },
         "simple-mind-map": {
            "type": "markdown",
            "preset": "colorful"
        }
    }
```
