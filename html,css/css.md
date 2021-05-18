## CSS
2021.04.18

1. 基本構造
```
セレクタ{
    プロパティ : 変更;
}
```
```
例
h1{
    color : red;
}
```

2. コメント　※非表示
```
/*コメント*/
```
```
例
h1{
    /*文字の色を赤に指定*/
    color : red;
}
```

3. 文字の大きさを変える(プロパティ)
```
font-size : size px;
```
```
例
h1{
    font-size : 10px;
}
```

4. フォントの種類を指定する(プロパティ)
```
front-family : font;
/*フォント名にスペースがある場合は"　"で囲う*/
```

5. 背景色を変える(プロパティ)
```
background-color :color;
```

6. 横幅を変える(プロパティ)
```
width : size px;
```

7. 高さを変える(プロパティ)
```
height : size px;
```

8. タグに名前をつける
```
<li class = "calss name">テキスト１</li>

/*class名でCSSを指定する場合、class名にはドットを付ける。複数の要素に同じclassを付けることも可能*/
.class name{
    プロパティ：変更；
}
```

9. 変更をまとめる

```
.class {
    padding: 上　右　下　左
}
```

10. 要素を透明にする
```
1. 要素全体を透明にする
opacity: 
/*0.0(完全に透明)〜1.0(完全に不透明)*/

2. 指定した箇所だけ透明にする
class {
    background-color: rgba(84,190,238,0.5);
}
/*４つ目の値が小さいほど透明になる*/
```

11. 文字の間隔を指定する
```
letter-spacing:
```

12. インラインブロック要素
```
インラインブロック要素は、widthやheighが指定できる

/*インラインブロックに変更する*/
display:

displayプロパティは、block,inline-block,inlineを指定できる
```

13. 複数クラスの設定
```
<div class ="btn blue" ></div>
<div class ="btn red"></div>
/*クラスに半角スペース開ける*/

.btn {
    /*共通のCSS*/
}
.blue {
    color: blue;
.red {
    color: red;
}
```

14. カーソルが乗った時のCSSを指定する
```
div:hover {
    opacity: 1px;
}
/*カーソルが乗った状態を hoverという*/
```

15. 角を丸める
```
border-radius: px;
/*数字が大きいほど角が丸くなる*/
```

16. インライン要素、インラインブロック要素の配置を指定する
```
text-align: left;
text-align: center;
```

17. 要素を中央に寄せる
```
1. margin: 0 auto;
/*containerクラスのように、広い範囲を囲うようなブロック要素の場合使用*/

2.text-align: center;
/*テキストやボタンのようなインライン要素・インラインブロック要素の場合使用*/
```

18. アイコンを表示する
```
Font Awsomeを使用する

1.Font AwesomeのCSSファイルを読み込む
2.<span>タグにfaクラスとfa-アイコン名クラスを指定する
（Font Awesomeのサイトにアイコンごとのクラス名が載っている）
```
```
<head>
    <link = >/*Font Awsomeを読みこむ*/
</head>
<body>
    <span class= "fa fa-facebook">
    </span>
    <span class= "fa fa-teitter">
    </span>
```

19. アニメーションを付ける
```
div {
    transition: all 1s;
/*変化の対象、変化の時間*/
}

div:hover {
    backgrond-color: red;
}
```

20. 行間を指定する
```
line-height: px;
/*要素の高さと、line-heightの高さを一緒にすると、文字がちょうど中央に配置される（縦の中央寄せ）*/
```

21. < a > タグをクリックできる範囲
```
<a>タグはインライン要素なので、中身のテキストの部分しか大きさを持たないため、クリックできる範囲はテキストの部分のみ。
<a>タグをブロック要素にすると、クリックできる範囲が要素いっぱいに広がる
```
22. 文字の太さを指定する
```
font-weight: normal
/*　normalまたはbold(太字)　*/
/* <h1> ~ <h6>の初期状態はbold */
```

23. 相対的な大きさの指定
```
width: 50%;
/* pxではなく%で指定すると、親要素に対してどのくらいの高さや幅をもつか指定できる*/
```

24. 要素同士を重ねる
```
div {
position: absolute;
top: px;
left px;
}
/*サイトの左上基準で、left,topで調整する*/

/*基準位置を変更したいとき、以下を指定するとその要素の左上部分が基準になる*/

position: relative;
```

25. ボックスに影を付ける
```
box-shadow: 10px 10px #000000;
/* 水平方向、垂直方向、色*/
```

26. マウスのカーソルが要素に乗った時のカーソルの形を変える
```
cursor: 
/*text,pointer,defaultがある*/
/*<a> タグは初期状態でpointerが設定してある*/
```

27. 要素がクリックされている間だけCSSを適用する
```
div:active {   
    CSS
}
```
28. CSSを打ち消す
```
プロパティ: none;
```

29. 位置の変更
```
position: relative;
top: px
left: px
```

30. ボタンを凹ませる
```
・影をなくす
・影の文だけ位置を下げる
```

30. 画面上に要素を固定する
```
position: fixed;
/*位置はtop,left,right,bottomを使って指定する*/
```

31. 要素の重なりの順序を指定する
```
z-index
/*整数値で指定し、値が大きいほど上に表示される。positionポロパティと併用する必要あり*/
```

32. 


