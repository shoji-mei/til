# document.getElementById()

- getElementById()の()内　→　HTMLにおけるid要素

## 文字列の代入

``` document.getElementById('box').textContent = 'こんにちは！'; ```

- HTMLページ内からid="box"の要素を探し、中身のテキストに文字列「こんにちは」を入れる。  
document.getElementByIdメソッドで取得したHTMLの要素はオブジェクトとして扱うことが可能  


## 時刻の表示

``` document.getElementById('box').textContent = new Date().toLocaleString(); ```

- `new Date().toLocaleString(); `  
  - 現在時刻を取得する命令  
  - 右辺が現在時刻に置き換えられ、左辺に代入される
  
  
## 文字同士の結合
  
  ``` document.getElementById('box').textContent = 'abc' + 'def'; ```
  
  
## 数値の計算
  
  ``` document.getElementById('box').textContent = 1 + 2; ```
