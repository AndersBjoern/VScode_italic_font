# VScode italic font (*FiraFlott*)

### Installation Guide

1. Download TTF-Folder
2. Install **BOTH** TTF-Font-Files on your PC
3. Enable Italics in your Editor of Choice (also enable Font-Ligatures)

### VScode specific

```
ctrl + shift + p
search: settings.json
```

**Copy, paste**

```
"editor.fontFamily": "'FiraFlott',Consolas, 'curier New', monospace",
    "editor.fontLigatures": true,
    "editor.fontSize": 16,
    "editor.fontWeight":"300",
    "editor.tokenColorCustomizations": {
        "textMateRules": [
        {
            "scope": [
                //following will be in italics 
                "constant", //String, Number, Boolean…, this, super
                "entity.name.type.class", //class names
                "storage.modifier", //static keyword
                "storage.type.class.js", //class keyword
                "keyword", //import, export, return…
            ],
            "settings": {
                "fontStyle": "italic"
            }
        },
        {
            "scope": [
                //following will be excluded from italics
                "comment",
                "invalid",
                "keyword.operator",
                "constant.numeric.css",
                "keyword.other.unit.px.css",
                "constant.numeric.decimal.js",
                "constant.numeric.json"
            ],
            "settings": {
                "fontStyle": ""
            }
        }]
    }
```
