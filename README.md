<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://maven-badges.herokuapp.com/maven-central/io.github.scouter-project/scouter-parent" rel="nofollow"><img src="https://camo.githubusercontent.com/4aa9cfa762433fc3d3fa07e1dea9db450b4c7a88026b6dcc288a29d819a3ceb2/68747470733a2f2f6d6176656e2d6261646765732e6865726f6b756170702e636f6d2f6d6176656e2d63656e7472616c2f696f2e6769746875622e73636f757465722d70726f6a6563742f73636f757465722d706172656e742f62616467652e7376673f743d31" alt="梅文中心" data-canonical-src="https://maven-badges.herokuapp.com/maven-central/io.github.scouter-project/scouter-parent/badge.svg?t=1" style="max-width: 100%;"></a>
<a href="https://github.com/scouter-project/scouter/issues"><img src="https://camo.githubusercontent.com/8531ea80bc5e0ac96a01c1f2e18f168ca543ffd837522065bcf93f238774d4b8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636f6e747269627574696f6e732d77656c636f6d652d627269676874677265656e2e7376673f7374796c653d666c6174" alt="欢迎贡献" data-canonical-src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/scouter-project/scouter/blob/master/scouter.document/img/main/scouter-logo-w200.png"><img src="/scouter-project/scouter/raw/master/scouter.document/img/main/scouter-logo-w200.png" alt="侦察员" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="/scouter-project/scouter/blob/master/README.md"><img src="https://camo.githubusercontent.com/d6026e7318c088fbb79f3bdbfcb5980d5c8a0c60efd8d723887578608b4b758d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c616e67756167652d456e676c6973682d6f72616e67652e737667" alt="英语" data-canonical-src="https://img.shields.io/badge/language-English-orange.svg" style="max-width: 100%;"></a> <a href="/scouter-project/scouter/blob/master/README_kr.md"><img src="https://camo.githubusercontent.com/a26035bb1d06fa63974cabd6fe28ae002b59b3c8eded331fa63827389f460531/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c616e67756167652d4b6f7265616e2d626c75652e737667" alt="韩国人" data-canonical-src="https://img.shields.io/badge/language-Korean-blue.svg" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源软件的应用程序性能监控。</font></font></h2><a id="user-content-application-performance-monitoring-for-open-source-sws" class="anchor" aria-label="永久链接：开源软件的应用程序性能监控。" href="#application-performance-monitoring-for-open-source-sws"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SCOUTER 是一个开源 APM，类似于 new relic 和 appdynamics。 （APM 表示应用程序性能监控或应用程序性能管理。）</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控目标（来自侦察代理）</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java Agent ：Web 应用程序（在 Tomcat、JBoss、Resin ...）、独立 java 应用程序</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主机代理：Linux、Windows、Unix</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控目标（来自 Telegraf 支持）自 @2.0.0 起</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Redis、nginX、apache httpd、haproxy、Kafka、MySQL、MongoDB、RabbitMQ、ElasticSearch、Kube、Mesos ...</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控目标（来自 Zipkin-Scouter 存储）自 @2.5.0 起</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何 zipkin 工具（C#、Go、Python、Javascript、PHP...）都可以显示在 XLog（散点图）图表中。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/scouter-project/zipkin-scouter"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zipkin-scouter-storage</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://zipkin.io/pages/extensions_choices.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zipkin 仪器。</font></font></a></li>
</ul>
</li>
</ul>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/scouter-project/scouter/blob/master/scouter.document/img/main/dashboard-sample-1.png"><img src="/scouter-project/scouter/raw/master/scouter.document/img/main/dashboard-sample-1.png" alt="屏幕" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户使用系统上的应用程序服务，服务使用系统上的资源。您应该了解此上下文，以便有效地管理系统性能。 SCOUTER 可以帮助您。</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">侦察兵表演</font></font></strong>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关用户的指标：活跃用户、最近使用的用户、今日访客</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关服务的指标：活动服务、TPS、响应时间、应用程序配置文件（方法配置文件、sql 配置文件、外部调用配置文件...）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关资源的指标：CPU、内存、网络和堆使用情况、连接池等。</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一目了然（点击观看视频）</font></font></h2><a id="user-content-at-a-glanceclick-to-watch-the-video" class="anchor" aria-label="永久链接：概览（点击观看视频）" href="#at-a-glanceclick-to-watch-the-video"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><animated-image data-catalyst=""><a href="https://youtu.be/iuArTzsD7Ws" rel="nofollow" data-target="animated-image.originalLink"><img src="/scouter-project/scouter/raw/master/scouter.document/img/main/scouter-movie.gif" alt="演示图" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://youtu.be/iuArTzsD7Ws" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Demo gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/scouter-project/scouter/raw/master/scouter.document/img/main/scouter-movie.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="480" height="270"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Demo gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Demo gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Demo gif in new window" class="AnimatedImagePlayer-button" href="https://youtu.be/iuArTzsD7Ws" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件</font></font></h2><a id="user-content-documents" class="anchor" aria-label="永久链接：文档" href="#documents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="/scouter-project/scouter/blob/master/scouter.document/index.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档首页</font></font></a></li>
<li><a href="/scouter-project/scouter/blob/master/scouter.document/main/Quick-Start.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速入门指南（演示系统快速安装）</font></font></a></li>
<li><a href="/scouter-project/scouter/blob/master/scouter.document/main/Setup.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></a></li>
<li><a href="/scouter-project/scouter/blob/master/scouter.document/main/Live-Demo.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现场演示</font></font></a></li>
<li><a href="/scouter-project/scouter/blob/master/scouter.document/client/Reading-XLog.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何分析XLog视图</font></font></a></li>
<li><a href="/scouter-project/scouter/blob/master/scouter.document/main/Alert-Plugin-Guide.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可定制的警报 - 警报插件指南</font></font></a></li>
<li><a href="/scouter-project/scouter/blob/master/scouter.document/main/Telegraf-Server.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Telegraf 服务器功能</font></font></a></li>
<li><a href="/scouter-project/scouter/blob/master/scouter.document/client/How-To-Use-Client.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端屏幕帮助</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></h2><a id="user-content-download" class="anchor" aria-label="永久链接： 下载" href="#download"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/scouter-project/scouter/releases/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最新发布</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模块</font></font></h2><a id="user-content-modules" class="anchor" aria-label="永久链接：模块" href="#modules"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">官方模块：</font></font></h3><a id="user-content-official-modules" class="anchor" aria-label="永久链接：官方模块：" href="#official-modules"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Agent</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：收集性能信息并发送给服务器</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java代理（JVM代理）</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：收集JVM和Web应用程序服务器（例如Tomcat）的配置文件和性能指标...</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主机代理（操作系统代理）</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：收集 Linux、Windows 和 OSX 的性能指标...</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MariaDB 代理</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：[待公布]</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务器（收集器）</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：保存来自 scouter 代理或 telegraf 的性能指标。数据被传输到 scouter 客户端。</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端（Viewer）</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：基于RCP的客户端程序。 （不支持 OSX Big Sur。）</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web API（自 @1.8.0 起）</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：通过 HTTP 协议获取计数器、XLog、配置文件和其他性能指标的 scouter Web API。</font></font></p>
<ul dir="auto">
<li><a href="/scouter-project/scouter/blob/master/scouter.document/tech/Web-API-Guide.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网络 API 指南</font></font></a></li>
</ul>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Weaver（自@2.17.0起）</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：提供在Java应用程序的代码级别直接控制Scouter XLog和Profiles的能力。</font></font></p>
<ul dir="auto">
<li><a href="/scouter-project/scouter/blob/master/scouter.document/weaver/Weaver-Guide.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">侦察兵韦弗指南</font></font></a></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3rd 方 UI</font></font></h3><a id="user-content-3rd-party-uis" class="anchor" aria-label="永久链接：第 3 方 UI" href="#3rd-party-uis"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter paper</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : </font></font><a href="https://scouter-contrib.github.io/scouter-paper/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter paper 主页</font></font></a>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">展示</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://www.youtube.com/watch?v=NjJ0dGhdIbU" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter paper 概述 (youtube)</font></font></a><br>
<a href="https://www.youtube.com/watch?v=NjJ0dGhdIbU" rel="nofollow"><img src="https://camo.githubusercontent.com/9ccafb251e4b5a7a5ee2c7b8541542289a7dedeece4a6194df3f968a688f947c/68747470733a2f2f73636f757465722d636f6e747269622e6769746875622e696f2f73636f757465722d70617065722f696d672f696d6731322e706e67" alt="斯考特帕特" data-canonical-src="https://scouter-contrib.github.io/scouter-paper/img/img12.png" style="max-width: 100%;"></a></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">插件</font></font></h3><a id="user-content-plugins" class="anchor" aria-label="永久链接：插件" href="#plugins"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务器插件</font></font></strong></p>
<ul dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">样本</font></font></strong></p>
<ul dir="auto">
<li><strong><a href="https://github.com/scouter-project/scouter-plugin-server-null"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter-plugin-server-null</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：示例插件打印收集的数据</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报</font></font></strong></p>
<ul dir="auto">
<li><strong><a href="https://github.com/scouter-contrib/scouter-plugin-server-alert-email"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter-plugin-server-email</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：来自 Scouter 的电子邮件警报</font></font></li>
<li><strong><a href="https://github.com/scouter-contrib/scouter-plugin-server-alert-telegram"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter-plugin-server-telegram</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：将警报从 Scouter 传输到 telegram</font></font></li>
<li><strong><a href="https://github.com/scouter-contrib/scouter-plugin-server-alert-slack"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter-plugin-server-slack</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：将警报从 Scouter 传输到 slack</font></font></li>
<li><strong><a href="https://github.com/scouter-contrib/scouter-plugin-server-alert-line"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter-plugin-server-line</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：将警报从 Scouter 传输到线路</font></font></li>
<li><strong><a href="https://github.com/scouter-contrib/scouter-plugin-server-alert-dingtalk"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter-plugin-server-dingtalk</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : 将警报从 Scouter 转移到 dingtalk</font></font></li>
<li><strong><a href="https://github.com/scouter-contrib/scouter-plugin-server-alert-teams"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter-plugin-server-teams</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：将警报从 Scouter 传输到 Microsoft Teams</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">柜台</font></font></strong></p>
<ul dir="auto">
<li><strong><a href="https://github.com/scouter-contrib/scouter-plugin-server-influxdb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter-plugin-server-influxdb</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：将性能数据从Scouter传输到influxDB（时间序列DB）</font></font></li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代理插件</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">待定</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第三方代理</font></font></h3><a id="user-content-3rd-party-agent" class="anchor" aria-label="永久链接：第 3 方代理" href="#3rd-party-agent"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">脉冲型代理</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://github.com/scouter-contrib/scouter-pulse"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter-pulse-library</font></font></a>
<ul dir="auto">
<li><strong><a href="https://github.com/nices96/scouter-pulse-aws-monitor"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">aws-monitor</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：从 AWS 中的 cloudwatch 收集 EC2、RDS、ELB 的性能指标。</font></font></li>
</ul>
</li>
</ul>
<br>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Facebook</font></font></h2><a id="user-content-facebook" class="anchor" aria-label="永久链接：脸书" href="#facebook"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://www.facebook.com/groups/scouterapm/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scouter APM：Facebook Scouter 用户组</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何贡献</font></font></h2><a id="user-content-how-to-contribute" class="anchor" aria-label="永久链接：如何贡献" href="#how-to-contribute"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：仅允许</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发分支</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的拉取请求。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅下面的开发指南。
</font></font><ul dir="auto">
<li><a href="/scouter-project/scouter/blob/master/scouter.document/tech/Developer-Guide.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">侦察兵开发者指南</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，您必须为您的第一个拉取请求</font><font style="vertical-align: inherit;">完成 CLA </font></font><a href="http://goo.gl/forms/xSmYs8qM9J" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></a><font style="vertical-align: inherit;"></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问答</font></font></h2><a id="user-content-qa" class="anchor" aria-label="永久链接：问答" href="#qa"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://groups.google.com/forum/#!forum/scouter-project" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">谷歌网上论坛</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">博客和帖子</font></font></h2><a id="user-content-blogging--posts" class="anchor" aria-label="永久链接：博客和帖子" href="#blogging--posts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=https%3A%2F%2Fgunsdevlog.blogspot.kr%2F2017%2F07%2Fscouter-apm-1.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scouter 系列 #1 - 安装</font></font></a></li>
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=https%3A%2F%2Fgunsdevlog.blogspot.kr%2F2017%2F07%2Fscouter-apm-2-12.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scouter系列#2 - 基础监控(1/2)</font></font></a></li>
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=https%3A%2F%2Fgunsdevlog.blogspot.kr%2F2017%2F07%2Fscouter-apm-basic-monitoring-2.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scouter系列#2.1 - 基础监控(2/2)</font></font></a></li>
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=http%3A%2F%2Fgunsdevlog.blogspot.kr%2F2018%2F05%2Fscouter-apm-xlog-howto.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scouter 系列 #3 - 主动服务和 XLog</font></font></a></li>
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=http%3A%2F%2Fgunsdevlog.blogspot.kr%2F2018%2F05%2Fscouter-apm-active-service-xlog.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scouter 系列 #4 - XLog 详细信息</font></font></a></li>
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=http%3A%2F%2Fgunsdevlog.blogspot.kr%2F2018%2F05%2Fscouter-customizable-alert.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scouter 系列#5 - 可定制的警报</font></font></a></li>
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=http%3A%2F%2Fkingbbode.tistory.com%2F12" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 Scouter APM 应用于我的服务：作者：Kingbbode</font></font></a></li>
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=http%3A%2F%2Fblog.naver.com%2FPostView.nhn%3FblogId%3Dtmondev%26logNo%3D220870505665" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scouter 的有效监控：TMON</font></font></a></li>
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=http%3A%2F%2Fwww.popit.kr%2Fscouter-open-source-apm-config%2F" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源性能监控、Scouter 配置：由 SUN 提供</font></font></a></li>
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=https%3A%2F%2Fgunleeblog.wordpress.com%2F2016%2F04%2F01%2Fopen-source-apm-scouter-influxdb-grafana-%25EC%2597%25B0%25EB%258F%2599-step-by-step%2F" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scouter、InfluxDB、Grafana</font></font></a></li>
<li><a href="https://translate.google.co.kr/translate?hl=ko&amp;sl=ko&amp;tl=en&amp;u=https%3A%2F%2Fgunleeblog.wordpress.com%2F2016%2F09%2F07%2Fscouter-pulse%25EB%25A5%25BC-%25EC%259D%25B4%25EC%259A%25A9%25ED%2595%2598%25EC%2597%25AC-%25EB%2582%2598%25EB%25A7%258C%25EC%259D%2598-agent-%25EB%25A7%258C%25EB%2593%25A4%25EA%25B8%25B0%2F" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过 scouter pulse 构建我自己的代理</font></font></a></li>
<li><a href="https://gunsdevlog.blogspot.kr/2018/04/scouter-web-ui-paper.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scouter paper UI快速安装</font></font></a></li>
</ul>
<br>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据 Apache 许可证 2.0 版获得许可
</font></font><br></p>
</article></div>
