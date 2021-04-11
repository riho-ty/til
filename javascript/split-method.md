## Split Method
2021.04.04

es6<br>

文字列を区切る時にsplit methodを使用する。<br><br>

基本構文

```
var str = '文字列';
str.split(区切り文字・正規表現, 分割数);
```
<br><br>

例文①<br>
```
var str = 'user-1,user-2,user-3';

//「, (カンマ)」で区切って分割する
var result = str.split(',');

//
console.log( result );
```
実行結果

```
["user-1", "user-2", "user-3"]
```
<br>
例文②

```
var lists = 'リンゴ,バナナ,メロン,イチゴ,スイカ';

var result = lists.split(',', 3);

console.log( result );
```
実行結果
```
["リンゴ", "バナナ", "メロン"]
```
<br><br><br>

[参考記事_1](https://codenote.net/javascript/3475.html)<br>改行コード \r\n \r \n を半角スペースに置換する正規表現とスニペット
<br>
[参考記事_2](https://www.sejuku.net/blog/27672)
<br>split()で文字列の分割＆正規表現の活用法まとめ！
