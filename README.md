# s14119132 陳佩儀
 至sistes新增資夾移至sublime   sublime新增檔案index.html
內容打.html按Tab鍵 `<html lang="utf-8">`
打link按Tab
至css bootstrap下載把3個資料夾(css.fonts.js)拉到剛新增的資料夾
在至link那行後面打"css./bootstrap.css"
在中間打`<h1>`.`<p>`.`<h2>`.`<p>`.`<button>`.`<button>`.`<h3>`.`<p>`
在下面的`<body>`上面打 `<script src="js/bootstrap.js">`
到bootstrap網站按getting start右邊Basic template
複製 `<!--JQuery(necessary for Bootstrap's......)>`和下面的 `<script src="......>`
在上面的body下面打 `<div>`
把後面的 `</div>`拉到中間打的下面
上面的 `<div>`內打"class=container"
置中.class="container-fluid"佔滿頁面
*皆要有 `</div>`結尾.有幾個 `<div>`結尾就有幾個
class="col-md-分欄位加至 `<h1>`上行
* `<img src="圖片網址" style=style"width:100%>`
*class="row" (可加可不加)  加間隔 在分欄位後打col-md-offset-1(左右各縮1)
*class="row text-center"置中
改字體:
另開一個css(New File)打mail.css在ctrl+s儲存
打body{font-family="......";在分欄位那行裡打features
凸顯字在內文 `<P class="lead">`圖示
 `<i class="......">` `</i>`
複製 `<title>`下面那行.把後面的bootstrap改成mail
改圖大小顏色:
在mail.css打featupes.glyphicon font-size:32px;color:red;
做頁腳:
 `<footer class='container-fluid">`到main.css打footer{
頁腳化分四欄對齊 `<h4>`Links `</h4>`
連結 `<ul class="list-unstyled">`
     `<li>` `<a href="網址">home</a></li>`
     `<li>news</li>`
     `</ul>`
`</div>`
改按鈕:
`<button type="button" class="btn btn-lg(xs.sm.lg大小)  btn-顏色>`  
顏色:default白色.primary藍色.danger紅色.success綠色.info淺藍.warning黃色
navbar-brand靠左.放大
`<a class="navbar-brand" href="/">`......`</a>`
`<div class=navbar navbar-default navbar-static-top">`固定.無圓角
`<div class=navbar navbar-default navbar-fixed-top">`無固定.無圓角
若用fixed不蓋到:到main.css打{body padding-top:70px
JavaScript導覽列
在`<ul class="nav.....navbar-collapse">`應用在手機上將導覽列收起
`<button type="button">`Toggle navigation`</button>`
=`<span class="sr-only">`......`</span>`
`<button type='button' class='navbar-toggle'  date-toggle='collapse  date-target='.navbar-collapse'>`  
`</button>`   會連結至
`<ul class='nav navbar-nav navbar-right collapse navbar-collapse'>`
`<div class="navbar-header">`在小畫面中滿版
