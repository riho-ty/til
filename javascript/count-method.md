## 特定の文字の数をカウントする方法

2021.05.12

es6

```
①ループで一文字ずつ数える

const str = "abc cat bat that dog aa";
let count = 0;  // 文字数を格納

const strSearch = 'a';  // 探す文字

for (let i = 0; i < str.length; i++){
    if (str[i] == strSearch){
        count ++;
    }
}

console.log(count);  // 6
```

```
②matchメソッドを使う

const paragraph = 'The quick brown fox jumps over the lazy dog. It barked.';

const regex = /[A-Z]/g;

const found = paragraph.match(regex);

console.log(found);
// expected output: Array ["T", "I"]
```




[参考記事]JavaScript: 特定の文字の数をカウントする方法
https://step-learn.com/article/javascript/127-string-count.html


