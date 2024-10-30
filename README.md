<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="40039207" _msthash="421">Asterisk（R） 开源 PBX</h1><a id="user-content-the-asteriskr-open-source-pbx" class="anchor" aria-label="永久链接：Asterisk（R） 开源 PBX" href="#the-asteriskr-open-source-pbx" _mstaria-label="1137071" _msthash="422"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre lang="text" class="notranslate"><code>        By Mark Spencer &lt;markster@digium.com&gt; and the Asterisk.org developer community.
        Copyright (C) 2001-2021 Sangoma Technologies Corporation and other copyright holders.
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="        By Mark Spencer <markster@digium.com> and the Asterisk.org developer community.
        Copyright (C) 2001-2021 Sangoma Technologies Corporation and other copyright holders." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4299763" _msthash="423">安全</h2><a id="user-content-security" class="anchor" aria-label="永久链接： SECURITY" href="#security" _mstaria-label="315991" _msthash="424"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="295878791" _msthash="425">您必须阅读并完全理解
“安全信息”文档，然后再尝试配置和运行
一个 Asterisk 服务器。</p>
<p dir="auto" _msttexthash="111712393" _msthash="426">有关更多信息，请参阅<a href="https://docs.asterisk.org/Deployment/Important-Security-Considerations/" rel="nofollow" _istranslated="1">重要安全注意事项</a>。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="23640214" _msthash="427">什么是星号？</h2><a id="user-content-what-is-asterisk-" class="anchor" aria-label="永久链接： 什么是 ASTERISK ？" href="#what-is-asterisk-" _mstaria-label="501579" _msthash="428"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="2287026183" _msthash="429">Asterisk 是一个开源 PBX 和电话工具包。它是，在
sense，底部是 Internet 和电话通道之间的中间件，
以及 Internet 和电话应用程序。但是，Asterisk 支持
更多的电话接口，而不仅仅是 Internet 电话。星号还有一个
对传统 PSTN 电话的大量支持。</p>
<p dir="auto" _msttexthash="558205076" _msthash="430">有关项目本身的更多信息，请访问 Asterisk <a href="https://www.asterisk.org" rel="nofollow" _istranslated="1">主页</a>和官方<a href="https://docs.asterisk.org/" rel="nofollow" _istranslated="1">文档</a>。此外，您还会发现很多
由 Asterisk 社区在 <a href="http://www.voip-info.org/wiki-Asterisk" rel="nofollow" _istranslated="1">voip-info.org</a> 汇编的信息。</p>
<p dir="auto" _msttexthash="390329160" _msthash="431">O'Reilly 在 Creative Commons 下出版了一本关于 Asterisk 的书
许可证。它可以在书店买到
<a href="http://www.asteriskdocs.org" rel="nofollow" _istranslated="1">asteriskdocs.org</a> 网站。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="25282842" _msthash="432">支持的操作系统</h2><a id="user-content-supported-operating-systems" class="anchor" aria-label="永久链接： 支持的操作系统" href="#supported-operating-systems" _mstaria-label="884585" _msthash="433"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4796116" _msthash="434">Linux的</h3><a id="user-content-linux" class="anchor" aria-label="永久链接：Linux" href="#linux" _mstaria-label="278421" _msthash="435"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="424670636" _msthash="436">Asterisk Open Source PBX 主要在
GNU/Linux 操作系统，并且在每个主要的 GNU/Linux 上都受支持
分配。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4010201" _msthash="437">别人</h3><a id="user-content-others" class="anchor" aria-label="永久链接：其他" href="#others" _mstaria-label="307268" _msthash="438"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="272656553" _msthash="439">星号也被“移植”，据报道可以在其他
操作系统，包括 Sun Solaris、Apple 的 Mac OS X、Cygwin、
和 BSD 变体。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4603768" _msthash="440">开始</h2><a id="user-content-getting-started" class="anchor" aria-label="永久链接： 开始使用" href="#getting-started" _mstaria-label="471653" _msthash="441"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="522044042" _msthash="442">首先，确保您已获得支持的硬件（但请注意，您不需要
任何特殊硬件，甚至不是声卡）来安装和运行 Asterisk。</p>
<p dir="auto" _msttexthash="48178806" _msthash="443">支持的电话硬件包括：</p>
<ul dir="auto">
<li _msttexthash="66790776" _msthash="444"><a href="https://www.sangoma.com/" rel="nofollow" _istranslated="1">Sangoma</a> 的所有模拟和数字接口卡</li>
<li _msttexthash="9994127" _msthash="445">QuickNet Internet PhoneJack 和 LineJack</li>
<li _msttexthash="95591925" _msthash="446">ALSA、OSS 或 PortAudio 支持的任何全双工声卡</li>
<li _msttexthash="42385278" _msthash="447">Linux 上 mISDN 支持的任何 ISDN 卡</li>
<li _msttexthash="26948688" _msthash="448">Xorcom Astribank 渠道库</li>
<li _msttexthash="14825343" _msthash="449">VoiceTronix OpenLine 产品</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="24023220" _msthash="450">从早期版本升级</h3><a id="user-content-upgrading-from-an-earlier-version" class="anchor" aria-label="永久链接： 从早期版本升级" href="#upgrading-from-an-earlier-version" _mstaria-label="1031914" _msthash="451"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="895875669" _msthash="452">如果您从以前版本的 Asterisk 进行更新，请确保您
读取源目录中的 <a href="/asterisk/asterisk/blob/master/UPGRADE.txt" _istranslated="1">UPGRADE.txt</a> 文件。有一些文件
和配置选项，即使我们
尽一切可能保持向后兼容性。</p>
<p dir="auto" _msttexthash="661495887" _msthash="453">为了发现要使用的新功能，请检查配置
源代码分发的 <a href="/asterisk/asterisk/blob/master/configs" _istranslated="1">configs</a> 目录中的示例。对于
此版本 Asterisk 中的新功能列表，请参阅 <a href="/asterisk/asterisk/blob/master/CHANGES" _istranslated="1">CHANGES</a> 文件。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="8902465" _msthash="454">新安装</h3><a id="user-content-new-installations" class="anchor" aria-label="永久链接：新安装" href="#new-installations" _mstaria-label="539058" _msthash="455"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1553755177" _msthash="456">确保您的系统包含兼容的编译器和开发
图书馆。Asterisk 需要 GNU 编译器集合 （GCC） 版本
4.1 或更高版本，或者支持 C99 规范和某些
GCC 语言扩展。此外，您的系统需要具有 C
library headers available，以及 NCorses 的 headers 和 libraries。</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="385642231" _msthash="457">有许多模块具有额外的依赖项。要查看
正在查找库，请参阅 或 Run 以查看特定模块的依赖项。</font><code>./configure --help</code><code>make menuselect</code></p>
<p dir="auto" _msttexthash="267294898" _msthash="458">在许多发行版中，这些依赖项由名称
如 'glibc-devel'、'ncurses-devel'、'openssl-devel' 和 'zlib-devel'
或类似的。</p>
<p dir="auto" _msttexthash="48621209" _msthash="459">那么，让我们继续：</p>
<ol dir="auto">
<li _msttexthash="18624931" _msthash="460">阅读此文件。</li>
</ol>
<p dir="auto" _msttexthash="343328076" _msthash="461"><a href="/asterisk/asterisk/blob/master/doc" _istranslated="1">doc</a> 目录中的文档比这个多。您也可以
想要检查包含示例和参考的配置文件
guides 的 <a href="/asterisk/asterisk/blob/master/configs" _istranslated="1">configs</a> 目录中。</p>
<ol start="2" dir="auto">
<li><font _mstmutation="1" _msttexthash="3303755" _msthash="462">跑</font><code>./configure</code></li>
</ol>
<p dir="auto"><font _mstmutation="1" _msttexthash="2013411244" _msthash="463">执行 configure 脚本以猜测系统相关
编译期间使用的变量。如果脚本指示某些必需的
缺少组件，您可以运行以安装必要的组件。请注意，这将安装 Asterisk 每个功能的所有依赖项。运行脚本后，您将需要
以重新运行 。</font><code>./contrib/scripts/install_prereq install</code><code>./configure</code></p>
<ol start="3" dir="auto">
<li><font _mstmutation="1" _msttexthash="15070328" _msthash="464">运行 <em _mstmutation="1" _istranslated="1">[可选]</em></font><code>make menuselect</code></li>
</ol>
<p dir="auto" _msttexthash="201523933" _msthash="465">如果要选择要编译的模块，并且
检查各种可选模块的依赖项。</p>
<ol start="4" dir="auto">
<li><font _mstmutation="1" _msttexthash="3303755" _msthash="466">跑</font><code>make</code></li>
</ol>
<p dir="auto" _msttexthash="40005667" _msthash="467">假设构建成功完成：</p>
<ol start="5" dir="auto">
<li><font _mstmutation="1" _msttexthash="3303755" _msthash="468">跑</font><code>make install</code></li>
</ol>
<p dir="auto" _msttexthash="554462571" _msthash="469">如果这是您第一次使用 Asterisk，您可能希望安装
示例 PBX，带有演示扩展等。如果是这样，请运行：</p>
<ol start="6" dir="auto">
<li><font _mstmutation="1" _msttexthash="3303755" _msthash="470">跑</font><code>make samples</code></li>
</ol>
<p dir="auto" _msttexthash="115018176" _msthash="471">这样做将覆盖您已安装的所有现有配置文件。</p>
<ol start="7" dir="auto">
<li _msttexthash="254763158" _msthash="472">最后，您可以使用以下命令在前台模式（而不是守护进程）启动 Asterisk：</li>
</ol>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>        # asterisk -vvvc
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="        # asterisk -vvvc" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="1679370836" _msthash="473">您会看到一堆冗长的消息作为 Asterisk 从您的屏幕上飞过
initializes（这是 “very very verbose” 模式）。准备就绪后，如果
您指定了 “c”，那么您将获得一个命令行控制台，它看起来
喜欢这个：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>        *CLI&gt;
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="        *CLI>" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="5887295193" _msthash="474">您可以随时键入“core show help”以获取有关系统的帮助。寻求帮助
使用特定命令，键入 “core show help ”。若要使用 PBX 启动 PBX
你的声卡上，你可以输入 “console dial” 来拨打 PBX。然后你可以使用
“console answer”、“console hangup”和“console dial”来模拟操作
电话。请记住，如果您没有全双工声卡
（如果你做/不做，星号会在其冗长的消息中告诉你）
那么它不会正常工作（目前还不行）。</p>
<p dir="auto" _msttexthash="780007059" _msthash="475">Unix/Linux 命令提示符处的 “man asterisk” 将为您提供详细的信息
有关如何启动和停止 Asterisk 以及所有命令的信息
用于启动 Asterisk 的行选项。</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="309133552" _msthash="476">请随意查看 中的配置文件，您可以在其中
将找到许多有关您可以使用 Asterisk 做什么的信息。</font><code>/etc/asterisk</code></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="19451887" _msthash="477">关于配置文件</h3><a id="user-content-about-configuration-files" class="anchor" aria-label="永久链接：关于配置文件" href="#about-configuration-files" _mstaria-label="779051" _msthash="478"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="5687815198" _msthash="479">所有 Asterisk 配置文件都共享一种通用格式。注释是
以 ';' 分隔（当然，由于 '#' 是 DTMF 数字，可能出现在
很多地方）。配置文件分为多个部分，其名称
出现在 [] 中。每个部分通常包含两种类型的语句：
格式为 'variable = value' 的参数，以及 'object =' 形式的参数&gt;
parameters'的在内部，'=' 和 '=&gt;' 的用法完全相同，因此
它们仅用于帮助使配置文件更易于
理解，并且不会影响它的实际解析方式。</p>
<p dir="auto" _msttexthash="492509732" _msthash="480">'variable=value' 形式的条目将 中的某个参数的值设置为
星号。例如，在 <a href="/asterisk/asterisk/blob/master/configs/samples/chan_dahdi.conf.sample" _istranslated="1">chan_dahdi.conf</a> 中，可以指定：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>	switchtype=national
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="	switchtype=national" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="1144485329" _msthash="481">为了向 Asterisk 表明他们正在连接的交换机是
类型为 “national”。通常，该参数将应用于
实例化，这些实例化发生在其规范以下。例如，如果
配置文件读取：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>	switchtype = national
	channel =&gt; 1-4
	channel =&gt; 10-12
	switchtype = dms100
	channel =&gt; 25-47
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="	switchtype = national
	channel => 1-4
	channel => 10-12
	switchtype = dms100
	channel => 25-47" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="338289211" _msthash="482">“国家”开关类型将应用于频道 1 到
4 和通道 10 到 12，而“DMS100”开关类型
适用于通道 25 到 47。</p>
<p dir="auto" _msttexthash="697402407" _msthash="483">“object =&gt; parameters” 使用给定的
参数。例如，“channel =&gt; 25-47” 行为
卡的通道 25 到 47，获取设置
从上面指定的变量中。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="36113636" _msthash="484">关于时间的特别说明</h3><a id="user-content-special-note-on-time" class="anchor" aria-label="永久链接： SPECIAL NOTE ON TIME" href="#special-note-on-time" _mstaria-label="564070" _msthash="485"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="9351166929" _msthash="486">使用 SIP 电话的人应该知道 Asterisk 对
时间的大幅跳跃。使用 date（1） 手动更改系统时间
（或其他类似命令）可能会导致 SIP 注册和其他
内部流程失败。如果您的系统无法保持准确的时间
本身使用 <a href="http://www.ntp.org/" rel="nofollow" _istranslated="1">NTP</a> 来保持系统时钟
同步到 “real time”。NTP 旨在保持系统时钟
通过加快或减慢系统时钟来同步，直到它
同步到“实时”，而不是通过跳跃时间，并且
导致不连续性。大多数 Linux 发行版都包含预编译
NTP 的版本。当心一些时间同步方法，这些方法会获取
定期正确实时，然后手动设置系统
时钟。</p>
<p dir="auto" _msttexthash="1234295686" _msthash="487">由于夏令时引起的明显时间变化就是这样，
表观。在 Linux 系统中使用夏令时是
纯粹是用户界面问题，不会影响
Linux 内核或 Asterisk。Linux 内核上的系统时钟运行
在 UTC 上。UTC 不使用夏令时。</p>
<p dir="auto" _msttexthash="277553107" _msthash="488">另请注意，此问题与 TDM 的时钟是分开的
频道，并且已知至少会影响 SIP 注册。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="16755362" _msthash="489">文件描述符</h3><a id="user-content-file-descriptors" class="anchor" aria-label="永久链接：文件描述符" href="#file-descriptors" _mstaria-label="505180" _msthash="490"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="3117796708" _msthash="491">根据系统的大小和配置，
星号可能会占用大量文件描述符。在 UNIX 中，
文件描述符不仅仅用于磁盘上的文件。文件
描述符还用于处理网络通信
（例如 SIP、IAX2 或 H.323 呼叫）和硬件访问（例如模拟和
数字中继硬件）。Asterisk 访问 许多磁盘上的文件
从配置信息到语音邮件存储的所有内容。</p>
<p dir="auto" _msttexthash="2521348492" _msthash="492">大多数系统限制 Asterisk 可以
一次打开。这可以限制同时
系统可以处理的调用。例如，如果设置了 limit
在 1024（常见的默认值）时，星号可以处理大约 150
同时进行 SIP 呼叫。更改文件描述符的数量
请按照以下适用于您的系统的说明进行操作：</p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto" _msttexthash="24490414" _msthash="493">基于 PAM 的 LINUX 系统</h4><a id="user-content-pam-based-linux-system" class="anchor" aria-label="永久链接：基于 PAM 的 LINUX 系统" href="#pam-based-linux-system" _mstaria-label="672074" _msthash="494"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="502524555" _msthash="495">如果您的系统使用 PAM （Pluggable Authentication Modules） ，请编辑 。将以下几行添加到文件底部：</font><code>/etc/security/limits.conf</code></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre lang="text" class="notranslate"><code>root            soft    nofile          4096
root            hard    nofile          8196
asterisk        soft    nofile          4096
asterisk        hard    nofile          8196
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="root            soft    nofile          4096
root            hard    nofile          8196
asterisk        soft    nofile          4096
asterisk        hard    nofile          8196" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="233974689" _msthash="496">（根据口味调整数字）。您可能需要重新启动系统
这些更改将生效。</p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto" _msttexthash="17838743" _msthash="497">通用 UNIX 系统</h4><a id="user-content-generic-unix-system" class="anchor" aria-label="永久链接： 通用 UNIX 系统" href="#generic-unix-system" _mstaria-label="578201" _msthash="498"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="275048176" _msthash="499">如果没有专门适用于您的系统的指令
您可以尝试将命令添加到脚本中
这开始了 Asterisk。</font><code>ulimit -n 8192</code></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="10372479" _msthash="500">更多信息</h2><a id="user-content-more-information" class="anchor" aria-label="永久链接： 更多信息" href="#more-information" _mstaria-label="504049" _msthash="501"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="640243045" _msthash="502">有关各种功能的更多文档，请参阅 <a href="/asterisk/asterisk/blob/master/doc" _istranslated="1">doc</a> 目录。
同样，请阅读包含文档的所有配置示例
在 Configuration Options （配置选项） 上。</p>
<p dir="auto" _msttexthash="294661029" _msthash="503">最后，您可能希望访问<a href="https://www.asterisk.org/support" rel="nofollow" _istranslated="1">支持</a>网站并加入<a href="http://lists.digium.com/mailman/listinfo/asterisk-users" rel="nofollow" _istranslated="1">邮件
列出</a>，如果您有兴趣获取更多信息。</p>
<p dir="auto" _msttexthash="107878316" _msthash="504">欢迎来到不断壮大的全球 Asterisk 用户社区！</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>        Mark Spencer, and the Asterisk.org development community
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="        Mark Spencer, and the Asterisk.org development community" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<hr>
<p dir="auto" _msttexthash="54568657" _msthash="505">Asterisk 是 Sangoma Technologies Corporation 的商标</p>
</article></div>
