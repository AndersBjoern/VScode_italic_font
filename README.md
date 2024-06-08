# Apps
```
Python 3.9.0 Test Suite (64-bit)                                                 3.9.150.0
Blender                                                                          2.90.1
Python 3.9.0 Core Interpreter (64-bit)                                           3.9.150.0
Office 16 Click-to-Run Extensibility Component                                   16.0.13628.20274
MySQL Installer - Community                                                      1.4.34.0
Microsoft Visual C++ 2013 x86 Minimum Runtime - 12.0.40660                       12.0.40660
Backup and Sync from Google                                                      3.54.3529.0458
MongoDB 4.4.1 2008R2Plus SSL (64 bit)                                            4.4.1
Microsoft Visual Studio Setup Configuration                                      2.7.3111.17308
Python Launcher                                                                  3.9.7217.0
Java 8 Update 271                                                                8.0.2710.9
ExpressVPN                                                                       7.7.12.4
Adobe Acrobat Reader DC - Dansk                                                  21.001.20140
Node.js                                                                          12.18.4
Illustrator, InDesign, Photoshop, XD
Figma / Sketch
Android Studio
Arduino
Blender
Docker
Elgiganten Cloud
**McAfee**
Git
GitKrakren
Chrome
Logitech
Teams
Minecraft
OneNote
*Opera GX*
Skype
Spotify
Unity
VLC
WinRar
Zoom
Postman
Spotify
Typora
Firma

https://github.com/Flow-Launcher/Flow.Launcher
https://support.microsoft.com/en-us/windows/clipboard-in-windows-c436501e-985d-1c8d-97ea-fe46ddf338c6
https://apps.microsoft.com/store/detail/quicklook/9NV4BS3L1H4S?hl=en-us&gl=US
https://everything.en.softonic.com/

```
# VScodeSetup
```
code --list-extensions | % { "code --install-extension $_" }
```
```
code --install-extension CoenraadS.bracket-pair-colorizer-2
code --install-extension dbaeumer.vscode-eslint
code --install-extension ecmel.vscode-html-css
code --install-extension Equinusocio.vsc-community-material-theme
code --install-extension Equinusocio.vsc-material-theme        
code --install-extension equinusocio.vsc-material-theme-icons  
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-rename-tag
code --install-extension GitHub.vscode-pull-request-github
code --install-extension humao.rest-client
code --install-extension Huuums.vscode-fast-folder-structure
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-dotnettools.csharp
code --install-extension ms-python.python
code --install-extension ms-toolsai.jupyter
code --install-extension ms-vscode-remote.remote-wsl
code --install-extension oderwat.indent-rainbow
code --install-extension PKief.material-icon-theme
code --install-extension pranaygp.vscode-css-peek
code --install-extension ritwickdey.live-sass
code --install-extension ritwickdey.LiveServer
code --install-extension syler.sass-indented
code --install-extension WallabyJs.quokka-vscode
code --install-extension aaron-bond.better-comments
```




#### In VScode:

```
ctrl + shift + p
search: snippets -> javascript.json
```

#### Copy, paste:

```js
{
// javascript
"Console Log": {
	"prefix": "cl",
	"body": "console.log($1);",
	"description": "Console log"
},
"consoleAssert": {
	"prefix": "cl.assert",
	"body": "console.assert(${1:expression}, ${2:object});",
	"description": "If the specified expression is false, the message is written to the console along with a stack trace"
},
"consoleClear": {
	"prefix": "cl.clear",
	"body": "console.clear();",
	"description": "Clears the console"
},
"consoleCount": {
	"prefix": "cl.count",
	"body": "console.count(${1:label});",
	"description": "Writes the the number of times that count() has been invoked at the same line and with the same label"
},
"consoleDir": {
	"prefix": "cl.dir",
	"body": "console.dir(${1:object});",
	"description": "Prints a JavaScript representation of the specified object"
},
"consoleTrace": {
	"prefix": "cl.trace",
	"body": "console.trace(${1:object});",
	"description": "Prints a stack trace from the point where the method was called"
},
"consoleWarn": {
	"prefix": "cl.warn",
	"body": "console.warn(${1:object});",
	"description": "Displays a message in the console but also displays a yellow warning icon along with the logged message"
},
"consoleTable": {
	"prefix": "cl.table",
	"body": "console.table(${1:object});",
	"description": "Displays tabular data as a table."
},
"consoleTime": {
	"prefix": "cl.time",
	"body": "console.time(${1:object});",
	"description": "Sets starting point for execution time measurement"
},
"consoleTimeEnd": {
	"prefix": "cl.timeEnd",
	"body": "console.timeEnd(${1:object});",
	"description": "Sets end point for execution time measurement"
},
"alert": {
	"prefix": "alert",
	"body": [
    	"alert('${1:msg}');"
	],
	"description": "Code snippet for 'alert'"
},
"confirm": {
	"prefix": "confirm",
	"body": [
    	"confirm('${1:msg}');"
	],
	"description": "Code snippet for 'confirm'"
},
"prompt": {
	"prefix": "prompt",
	"body": [
    	"prompt('${1:msg}');"
	],
	"description": "Code snippet for 'prompt'"
},
"Const arrow function": {
	"prefix": "carrow",
	"body": [
	"const ${1:functionName} = ($2) => {",
	"    $3",
	"}"
	],
	"description": "Const arrow function"
},
"anonymousFunction": {
	"prefix": "(())",
	"body": "(${1:params}) => {\n\t${2}\n}",
	"description": "Creates an anonymous function in ES6 syntax"
},
"forEach": {
	"prefix": "forEach",
	"body": "${1:array}.forEach(${2:currentItem} => {\n\t${0}\n});",
	"description": "Creates a forEach statement in ES6 syntax"
},
"Map funciton": {
	"prefix": ".mapfunction",
	"body": [
	"map( ",
	"    function(x){ ",
	"        $1",
	"    }",
	");"
	],
	"description": "Map funciton"
},
"Array Method": {
	"prefix": ".arrmth",
	"body": [
	".${1|forEach,map,filter,find,every,some|}((${2:item}) => {",
	"    $3",
	"})"
	],
	"description": "Array Method"
},
"getElementById": {
	"prefix": "document.getId",
	"body": [
    	"document.getElementById('${2:id}');"
	],
	"description": "Code snippet for \"getElementById\""
},
"getElementsByClassName": {
	"prefix": "document.getClass",
	"body": [
    	"document.getElementsByClassName('${2:class}');"
	],
	"description": "Code snippet for \"getElementsByClassName\""
},
"querySelectorAll": {
	"prefix": "document.getAll",
	"body": [
	"document.querySelectorAll('${2:selector}');"
	],
	"description": "Code snippet for \"querySelectorAll\""
},
"setInterval": {
	"prefix": "setInterval",
	"body": [
	"setInterval(() => {",
	"\t${0:// body}",
	"}, ${1:1000});"
	],
	"description": "Code snippet for 'setInterval'"
},
"setTimeout": {
	"prefix": "setTimeout",
	"body": [
	"setTimeout(() =>{",
	"\t${0:// body}",
	"}, ${1:1000});"
	],
	"description": "Code snippet for 'setTimeout'"
},
"Class Template": {
	"prefix": "class_template",
	"body": [
	"class ${1:myClass} {",
	"    constructor(${2:parameter}) {",
	"        this.${2:parameter} = ${2:parameter}; // || evt_standardværdi",
	"        this._myArray = []; // array of objects",
	"    }",
	"",
	"    ${3:functionName1} (object){",
	"        this._myArray.push( object );",
	"    }",
	"",
	"    ${4:functionName2} (sumThis){",
	"        let total = sumThis;",
	"        for (let i of this._myArray){",
	"            total += i.${6:functionName3}();",
	"        }",
	"    return total;",
	"}",
	"",
	"    toString(){",
	"        return this.${2:parameter}+' something (\\n' + this._myArray + ')';",
	"    }",
	"}",
	"",
	"class ${5:newClass}{",
	"    ${6:functionName3}(){",
	"        return 1;",
	"    }",
	"}",
	"",
	"class ${7:subClass1} extends ${5:newClass}{",
	"    constructor(${2:parameter}) {",
	"        super(${2:parameter});",
	"        this.${2:parameter} = ${2:parameter}; // || evt_standardværdi",
	"    }",
	"",
	"    ${6:functionName3}(){",
	"        return 5;",
	"    }",
	"}",
	"class ${8:subClass2} extends ${5:newClass}{",
	"    ${6:functionName3}(){",
	"        return 5;",
	"    }",
	"}",
	],
	"description": "Class Template"
},
"Switch Template": {
	"prefix": "switch_template",
	"body": [
	"switch(${1|'string',int,bool|}){",
	"    case $2:",
	"        break;",
	"    case $3:",
	"        break;",
	"    default:",
	"        // not found",
	"        break;",
	"}"
	],
	"description": "Switch Template"
},
// jQuery
"jQuery ajax call": {
	"prefix": "$.ajax_template",
	"body": [
	"$.ajax({",
	"    type: \"${1|POST,GET|}\",",
	"    url: \"${2|http://localhost:3000/_path,script.js|}\",",
	"    dataType: \"${3|datatype_expected_from_server,json,text,html,script|}\",",
	"    data: ${4|data_to_be_sent_to_server,{objectKey:value},'string',[array]|}",
	"}).done( ( data,status,xhr ) =>{",
	"    let parsedData = JSON.parse(data);",
	"    console.${5|log,table|}(parsedData);",
	"}).fail( ( jqXhr, textStatus, errorMessage )=>{",
	"    alert(errorMessage);",
	"});"
	],
	"description": "jQuery ajax call"
},
"jQuery table template": {
	"prefix": "table_from_object_template",
	"body": [
	"let parsedData = JSON.parse(data);",
	"let html= `",
	"    <table id=\"${1:id_for_table}\">",
	"        <tr>",
	"            <th>Id</th>",
	"            <th>name</th>",
	"            <th>description</th>",
	"        </tr>`;",
	"for (const key in parsedData) {",
	"    html += `",
	"    <tr>",
	"        <td>${parsedData[key].${2:id}}</td>",
	"            <td>${parsedData[key].${3:name}}</td>",
	"            <td>${parsedData[key].${4:description}}</td>",
	"        </tr>`",
	"}",
	"",
	"html += '</table>'",
	"$('#${5:output}').html( html );"
	],
	"description": "jQuery table template"
},
"jQuery unordered list template": {
	"prefix": "list_from_object_template",
	"body": [
	"let parsedData = JSON.parse(data);",
	"",
	"let html;",
	"for (const key in parsedData) {",
	"    html += `",
	"        <ul id=\"${key}\">",
	"            <li>${parsedData[key].${1:id}}</li>",
	"            <li>${parsedData[key].${2:name}}</li>",
	"            <li>${parsedData[key].${3:description}}</li>",
	"        </ul>`;",
	"}",
	"$('#${4:output}').html( html );"
	],
	"description": "jQuery unordered list template"
},
"jQuery funktion template": {
	"prefix": "$('')_jQuery_template",
	"body": [
	"$('${1|#,.|}').${2|on('click'_()=>{});,addClass('.');,each((index)=>{});,filter('.');,animate({left: '250px' _ height: ''});,css('background-color' _ 'blue');|};"
	],
	"description": "jQuery funktion template"
},
"Value from input field post to Ajax": {
	"prefix": ".val_submit_ajax_template",
	"body": [
	"$('#${1:buttonId}').on( \"click\", function(){",
	"    let ${2:inputId}= $('#${2:inputId}').val();",
	"    let ${2:inputId} = $('#${2:inputId}').val();",
	"    let ${2:inputId}= $('#${2:inputId}').val();",
	"",
	"    $.ajax({",
	"        type: \"POST\",",
	"        url: \"http://localhost:3000/addcake\",",
	"        data: {name: ${2:inputId}, description: ${2:inputId}, something: ${2:inputId}}",
	"    }).done( ( data,status,xhr ) =>{",
	"        console.log(data);",
	"    }).fail( ( jqXhr, textStatus, errorMessage )=>{",
	"        alert(errorMessage);",
	"    });",
	"});"
	],
	"description": "Value from input field post to Ajax"
},
// node / express
"import": {
	"prefix": "import",
	"body": "import ${2:moduleName} from '${1:module}';$0",
	"description": "Imports entire module statement in ES6 syntax"
},
"importNoModuleName": {
	"prefix": "importModule",
	"body": "import '${1:module}';$0",
	"description": "Imports entire module in ES6 syntax without module name"
},
"requireToConst": {
	"prefix": "require",
	"body": "const ${1:packageName} = require('${1:package}');$0",
	"description": "Require a package to const"
},
"express app get template": {
	"prefix": "app.get/post/delete",
	"body": [
	"app.${1|get,post,delete|}('/${2:index}', (req, res)=>{",
	"    let response;",
	"    res.set('Content-Type', '${4|application/json,text/html,text/plain,image/png|}');",
	"    res.send( response );",
	"});"
	],
	"description": "express app get template"
},
"Response status": {
	"prefix": "res.status",
	"body": [
	"res.sendStatus(${1|200_ok,403_forbidden,404_not_found,500_server_error|});"
	],
	"description": "Response status"
},
"Response set content type": {
	"prefix": "res.set",
	"body": [
	"res.set('Content-Type', '${1|application/json,text/html,text/plain,image/png|}');"
	],
	"description": "Response set content type"
},
"FileSystem writefile": {
	"prefix": "fs.writefile_template",
	"body": [
	"fs.writeFileSync(__dirname + '/${1:filename}.txt', '${2:text_to_insert}\\n'); "
	],
	"description": "FileSystem writefile"
},
"FileSystem appendfile": {
	"prefix": "fs.append_to_file_template",
	"body": [
	"fs.appendFileSync(__dirname + '/${1:filename}.txt', '${2:text_to_insert}\\n'); "
	],
	"description": "FileSystem appendfile"
},
// express - MySQL
"Express select from database": {
	"prefix": "sql_get/express_select",
	"body": [
	"let response;",
	"con.query('SELECT ${1:kolonne(r)_eller_*} FROM ${2:tabel_navn}', (err, result, fields)=>{",
	"    if (err){",
	"        response = err;",
	"    } else {",
	"        response = result;",
	"    }",
	"    console.log(result);",
	"",
	"    res.set('Content-Type', '${3|application/json,text/html,image/png|}');",
	"    res.send( response );",
	"});"
	],
	"description": "Express select from database"
},
"Express insert into database": {
	"prefix": "sql_post/express_insert",
	"body": [
	"let response;",
	"let operation = `INSERT INTO ${1:table_name} values ",
	"    ('${req.body.${2:id}}', '${req.body.${3:name}}', '${req.body.${4:description}}'');`;",
	"con.query(operation, (err, result, fields)=>{",
	"    if (err){",
	"        response = err;",
	"    } else {",
	"        response = result;",
	"    }",
	"    console.log(result);",
	"    res.setHeader('Content-Type', 'application/json');",
	"    res.send( response );",
	"});"
	],
	"description": "Express insert into database"
},
// yuml
"yuml template": {
	"prefix": "yuml_template",
	"body": [
	"// setup",
	"[${1:ClassName}]",
	"[${2:newClass}]^[${3:subClass1}]",
	"[${2:newClass}]^[${4:subClass2}]",
	"",
	"// funktioner",
	"[${1:ClassName}|name:String;_myArray:array|",
	"${5:funktionNavn1} (int) : return int|pushArray2 (${2:newClass}) : return _MyArray]",
	"",
	"// funktioner _ 2",
	"[${2:newClass}|${6:funktionNavn3} (int) : int]",
	"",
	"// funktioner _ 3",
	"[${3:subClass1}|${6:funktionNavn3} (int) : int]",
	"[${4:subClass2}|${6:funktionNavn3} (int) : int]",
	],
	"description": "yuml template"
},
// sql
"SQL joins": {
	"prefix": "sql_join",
	"body": [
	"SELECT *",
	"FROM ${1:tabel 1} AS t_1",
	"WHERE t_1.${2:tabel kolonne} = '' # dette er valgfrit",
	"# INNER: kun dem med match vises",
	"# LEFT: alle fra venstre tabel vises, og dem fra højre som matcher",
	"# RIGHT: modsat - alle fra højre vises og match fra venstre",
	"# FULL: resultater fra begge vises - hvis intet match skrives 'null'",
	"${3|INNER,LEFT,RIGHT,OUTER|} JOIN ${4:tabel 2} AS t_2",
	"ON t_1.${5:tabel id} = t_2.${5:tabel 2 id};"
	],
	"description": "SQL joins"
},
"SQL insert": {
	"prefix": "sql_insert_query",
	"body": [
	"insert ${1:tabel_navn} values(${2|\"\",NULL,1|},${3|\"\",NULL,1|});",
	"select * from ${1:tabel_navn};"
	],
	"description": "SQL insert"
},
"SQL variables": {
	"prefix": "sql_variable",
	"body": [
	"SELECT @${1:variabel_navn} := ${2:den_kolonne_du_vil_have_returneret} FROM ${3:tabel} WHERE ${4:den_kolonne_du_vil_søge_i}=${5|'navn',3|};"
	],
	"description": "SQL variables"
}
}
```


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
                "entity.name.type.class", 
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
