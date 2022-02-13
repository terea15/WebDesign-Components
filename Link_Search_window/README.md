## ProjectTitle：Link_Search_window<br>
ページ内アンカーを対象としたインクリメンタルサーチ機能

### 更新履歴
- 20220213：<br>
GitHub精査時に、インクリメンタルサーチとしての機能を果たしていないことが発覚。<br>
詳細：検索バーにキーワード入力後、検索結果が出力されない<br>
原因：以下コードでページ内アンカーを取得できていないと予想<br>
```javascript
//ページ内にあるアンカーを全て拾う(IE非対応)
var fruits = $("a").map(function(i,e){return {href: e.href, text: e.text}})
```
対応：現在対応中(20210213～)

## 使用言語
- html
- css
- javaScript

## 使用ライブラリ
- jQuery

## ディレクトリ階層図
```
Link_Search_window/
　├ html/
　│　└ index.html
　├ css/
　│　└ style.css
　├ js/
　│　└ main.js
　│　└ jquery.min.js
　└ README.md
```

## キャプチャ
※準備中
