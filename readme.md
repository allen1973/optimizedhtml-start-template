<h1>OptimizedHTML - Start HTML Template</h1>


<p>
	<img src="https://raw.githubusercontent.com/agragregra/optimizedhtml-start-template/master/app/img/preview.jpg" alt="Start HTML Template">
</p>

<p>Author: <a href="http://webdesign-master.ru" target="_blank">WebDesign Master</a> | <a href="http://webdesign-master.ru/blog/tools/2016-08-19-optimizedhtml.html" target="_blank">Manual in Russian</a></p>

<p>優化HTML是全面的，針對Google PageSpeed啟動HTML5模板，使用Bootstrap（僅網格），Gulp，Sass，Browsersync，Autoprefixer，Clean-CSS，Uglify，Imagemin，Vinyl-FTP和Bower（libs路徑）支持進行了優化。該模板包含一個具有Web服務器緩存規則的.htaccess文件。</p>

<p>OptimizedHTML開始模板使用Web開發的最佳實踐，並針對Google PageSpeed進行了優化。</p>

<p>跨瀏覽器兼容性：IE9 +。</p>

<P>該模板使用具有<strong>Sass</strong>語法和項目結構的Sass，其目錄<strong>app/</strong>生產文件夾<strong>dist/</strong>中包含源代碼，其中包含具有優化的HTML，CSS，JS和圖像的準備項目。</p>

<h2>如何使用OptimizedHTML</h2>

<ol>
	<li><a href="https://github.com/agragregra/optimizedhtml-start-template/archive/master.zip">下載</a> <strong>optimizedhtml-start-template</strong> from GitHub;</li>
	<li>安裝: <strong>npm i</strong>;</li>
	<li>執行: <strong>gulp</strong>.</li>
</ol>

<h2>Gulp任務:</h2>

<ul>
	<li><strong>gulp</strong>: 運行默認gulp任務（sass，js，watch，browserSync）進行Web開發</li>
	<li><strong>build</strong>: 構建項目到dist文件夾(cleanup, image optimize, removing unnecessary files);</li>
	<li><strong>deploy</strong>: 通過<strong>FTP</strong>從<strong>dist</strong> 文件夾在服務器上部署項目;</li>
	<li><strong>rsync</strong>: 通過RSYNC從<strong>dist</strong> 文件夾在服務器上部署項目;</li>
	<li><strong>clearcache</strong>: 清除所有gulp緩存。</li>
</ul>



<h2>Rules for working with the starting HTML template</h2>

<ol>
	<li><font><font>所有HTML文件應具有與</font></font><strong><font><font>app / index.html</font></font></strong><font><font>類似的初始內容</font><font>;</font></font></li>
	<li><strong><font><font>模板基本圖像</font></font></strong><font><font>在app / index.html中</font><strong><font>開始</font></strong><font>評論 - 所有您的自定義模板基本圖像（og：社交網絡圖像，各種設備的圖標）;</font></font></li>
	<li><strong><font><font>自定義瀏覽器顏色</font></font></strong><font><font>在app / index.html中</font><strong><font>開始</font></strong><font>註釋：設置瀏覽器頭部在各種設備上的顏色;</font></font></li>
	<li><strong><font></font></strong><font><font>app / index.html中的</font><strong><font>自定義HTML</font></strong><font>註釋 - 所有您的自定義HTML;</font></font></li>
	<li><font><font>要安裝新的jQuery庫，只需</font><font>在終端中</font><font>運行命令“ </font></font><strong><font><font>bower i plugin-name</font></font></strong><font><font> ”即可。</font><font>庫自動放在文件夾</font></font><strong><font><font>app / libs中</font></font></strong><font><font>。</font><font>Bower必須安裝在系統中（npm i-g bower）。</font><font>然後將所有jQuery庫路徑放在</font></font><strong><font><font>'libs'</font></font></strong><font><font>任務（gulpfile.js）中;</font></font></li>
	<li><font><font>所有定制JS位於</font></font><strong><font><font>app / js / common.js</font></font></strong><font><font> ;</font></font></li>
	<li><font><font>所有Sass vars都放在</font></font><strong><font><font>app / sass / _vars.sass中</font></font></strong><font><font> ;</font></font></li>
	<li><font><font>所有Bootstrap媒體查詢放在</font></font><strong><font><font>app / sass / _media.sass中</font></font></strong><font><font> ;</font></font></li>
	<li><font><font>所有jQuery庫CSS樣式放在</font></font><strong><font><font>app / sass / _libs.sass中</font></font></strong><font><font> ;</font></font></li>
	<li><font><font>將</font></font><strong><font><font>ht.access</font></font></strong><font><font>重命名</font><font>為</font></font><strong><font><font>.htaccess，</font></font></strong><font><font>然後將其放在Web服務器中。</font><font>此文件包含在Web服務器上緩存文件的規則。</font></font></li>
</ol>
