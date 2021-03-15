# mindmap
{% simplemindmap %}
```markdown
* simplemindmap
    * config book.json
        * plugins
            * others
            * simple-mind-map
        * pluginsConfig
            * others
            * simple-mind-map
                * type ![](https://i.imgur.com/00bdDAR.png)
                * preset
                * linkShape
                * autoFit
                * style
    * custom file.md
        * markdown
            * type
            * preset
            * linkShape
            * autoFit
            * style
        * txtmap
        * json
        * mindmup
```
{% endsimplemindmap %}


## 目前使用plugin

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
