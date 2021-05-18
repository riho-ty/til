## slice() method

2021.05.16

es6

<br>
slice()メソッドは、配列内の指定範囲の要素を新しい配列として取り出します。

```
[構文]
 配列名.slice(開始位置, 終了位置)

第一引数
開始位置

第ニ引数
終了位置

戻り値
元の配列の一部が新しい配列として返る
```

sample 1
```
<script>
var ary = new Array("いちご", "にんじん", "さんだる", "よっと", "ごましお");

var sliced = ary.slice(1, 3);	
//1番目から3番目のひとつ前までを、新しい配列として取り出す

document.write(sliced);
</script>

//にんじん,さんだる

```

[参考記事]
http://www.htmq.com/js/array_slice.shtml