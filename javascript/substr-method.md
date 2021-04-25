## substr()で文字列を切り出す
2021.04.18

es6

- substrの基本構文
```
const sample = 文字列
sample.substr(開始位置,文字数)
```
```
const fruites = 'イチゴバナナメロン';
const resulte = fruites.substr(6,3);
console.log(resulte);
//メロン　：文字列の６文字目から数えて３文字分の範囲を切り出す
```

- substringの基本構文
```
const sample = 文字列
sample.substring(開始位置,終了位置);
```
```
const fruites ='イチゴバナナメロン';
const result = fruites.substring(3,6);
console.log(result);
// バナナ　：文字列の３文字目から６文字目までを抽出する
```

[参考記事]

substrで文字列を切り出す方法
https://www.sejuku.net/blog/50543

substringで文字列を切り出す方法
https://www.sejuku.net/blog/25730
