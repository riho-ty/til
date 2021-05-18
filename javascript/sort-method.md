## sort関数

2021.05.16

es6

1. 昇順（小さい順）ソート
```
const sample = [1,2,3,4];

sample.sort((a, b) => {
  return a - b;
});

// 戻り値が正（a-bの差が正）のとき、aをbの後ろに並べ替え
// 戻り値が負（a-bの差が負）のとき、aをbの前に並べ替え
// const sample = [1,2,3,4];
```

[参考記事]jsのsort関数
https://qiita.com/ymk83/items/3d53e0965a278b5cfd4d

<br>


2. 降順（大きい順）ソート
```
sample.sort((a, b) => {
  return b - a;
});

//const sample = [4,3,2,1];
```


3. 二次元配列のソート(降順)
```
array.sort((a, b) => {
        return b[0] - a[0];
});
//要素の０番目でソート
```
```
//サンプル

array.sort((a, b) => {
        return b[0] - a[0];
});
// index０でソート

array.sort((a,b) =>{
    if(a[0] === b[0]) {
        return b[1] - a[1];
    }
});
// index０が同じであれば、index１でソート

for(let i = 0; i < array.length; i++){
  console.log(array[i].join(' '));
}
```
[参考記事1]二次元配列のソート
https://qiita.com/ryomaDsakamoto/items/eae134f6d8af36519560

[参考記事2]複数条件でのソートをするサンプル
https://kojimanotech.com/2020/05/04/217/