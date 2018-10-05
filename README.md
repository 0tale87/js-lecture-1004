# テクノロジー（藤原） 10/4課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください

```

```

## 例（下記の書き方をまねてください）

```
var str = "Hello!";
undefined
var num = 123
undefined
var flag = true;
undefined
var preList = ["北海道","青森","岩手","宮城","秋田"];
undefined
var p
undefined
var prefHash = {"kanto":"関東地方","chubu","中部地方","kinki","近畿地方","chugoku","中国地方","shikoku","四国地方"}
VM4400:1 Uncaught SyntaxError: Unexpected token ,
var prefHash = {"kanto":"関東地方","chubu","中部地方","kinki","近畿地方","chugoku","中国地方","shikoku","四国地方"};
VM4404:1 Uncaught SyntaxError: Unexpected token ,
var prefHash = {"kanto":"関東地方","chubu":"中部地方","kinki":"近畿地方","chugoku":"中国地方","shikoku":"四国地方"};
undefined
var prefList = ["北海道","青森","岩手","宮城","秋田"];
undefined
console.log(prefHash["kanto"]);
VM4523:1 関東地方
undefined
console.log(prefHash.kanto);
VM4588:1 関東地方
undefined
console.log(prefHash["kinki"]);
VM4610:1 近畿地方
undefined
console.log(prefHash.kinki);
VM4643:1 近畿地方
undefined
var prefHash1 = {"kanto":"関東地方","chubu":"中部地方"};
undefined
var prefHash2 = {kanto:"関東地方",chubu:"中部地方"};
undefined
var prefHash3 = {};
undefined
prefHash3["kanto"] = "関東地方"
"関東地方"
prefHash3["zhubu"] = "中部地方"
"中部地方"
prefHash3["chubu"] = "中部地方"
"中部地方"
var prefHash4 {};
VM5006:1 Uncaught SyntaxError: Unexpected token {
var prefHash4 {};
VM5008:1 Uncaught SyntaxError: Unexpected token {
var prefHash4 = {};
undefined
prefHash4.kanto
undefined
prefHash4.kanto = "関東地方";
"関東地方"
prefHash4.chubu = "中部地方";
"中部地方"
var str = "JavaScriptを始めよう！";
undefined
console.log(str.length);
VM5193:1 16
undefined
var date = new Date();
undefined
console.log(date.toLocaleString());
VM5291:1 2018/10/5 11:20:21
undefined
var str = navigator.platform + "\n" + navigator.userAgent + "\n"
undefined
var str = navigator.platform + "\n" + navigator.userAgent + "\n";
undefined

```
