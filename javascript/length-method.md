## length()で文字列の長さを取得する
2021.04.18

es6
<br><br>

- 文字列の入った変数に.lengthをつける
```
const string = 'sample';
console.log(string.length);
// 5と出力される
```
<br>

- 日本語を入力しても文字列の長さが出力される

```
const string = 'サンプル';
console.log(string.length);
// 4と出力される
```
<br>

- 空白もカウントされる
```
const string = 'sample sample';
console.log(string.length);
// 空白もカウントされ、13と出力される
```
<br>

- 空白を削除して文字列の長さをカウントしたい時
```
const string = 'sample sample';
console.log(string.trim().length);
// 12と出力される
```

[参考記事]
https://uxmilk.jp/14057

