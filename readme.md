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
	<li>所有HTML文件應具有與 <strong>app/index.html</strong>類似的初始內容;;</li>
	<li><strong>Template Basic Images Start</strong> comment in app/index.html - all your custom template basic images (og:image for social networking, favicons for a variety of devices);模板基本圖像在app / index.html中開始評論 - 所有您的自定義模板基本圖像（og：社交網絡圖像，各種設備的圖標）;</li>
	<li><strong>Custom Browsers Color Start</strong> comment in app/index.html: set the color of the browser head on a variety of devices;自定義瀏覽器顏色在app / index.html中開始註釋：設置瀏覽器頭部在各種設備上的顏色;</li>
	<li><strong>Custom HTML</strong> comment in app/index.html - all your custom HTML;</li>
	<li>For installing new jQuery library, just run the command "<strong>bower i plugin-name</strong>" in the terminal. Libraries are automatically placed in the folder <strong>app/libs</strong>. Bower must be installed in the system (npm i -g bower). Then place all jQuery libraries paths in the <strong>'libs'</strong> task (gulpfile.js);</li>
	<li>All custom JS located in <strong>app/js/common.js</strong>;</li>
	<li>All Sass vars placed in <strong>app/sass/_vars.sass</strong>;</li>
	<li>All Bootstrap media queries placed in <strong>app/sass/_media.sass</strong>;</li>
	<li>All jQuery libraries CSS styles placed in <strong>app/sass/_libs.sass</strong>;</li>
	<li>Rename <strong>ht.access</strong> to <strong>.htaccess</strong> before place it in your web server. This file contain rules for files caching on web server.</li>
</ol>
