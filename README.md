<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于数字信号处理的有用 C++ 类集合</font></font></h2><a id="user-content-a-collection-of-useful-c-classes-for-digital-signal-processing" class="anchor" aria-label="永久链接：用于数字信号处理的有用 C++ 类的集合" href="#a-collection-of-useful-c-classes-for-digital-signal-processing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“数字信号处理技术受到严密保护，并被保密，因为它们对多媒体内容具有有价值的应用。无限脉冲响应（“IIR”）滤波的黑魔法一直处于保密状态，几乎没有公开的源代码。 ..到目前为止。”</font></font></p>
</blockquote>
<a href="https://github.com/downloads/vinniefalco/DSPFilters/DSPFiltersComplete.zip">
<img src="https://github.com/vinniefalco/vinniefalco.github.com/raw/master/images/DownloadNow.png" style="max-width: 100%;">
</a>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是什么？</font></font></h3><a id="user-content-what-is-this" class="anchor" aria-label="永久链接：这是什么？" href="#what-is-this"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该库以 Sophocles Orfanidis、Andreas Antoniou、Martin Holters 和 Udo Zolzer 等备受尊敬的杰出人物的工作为基础，利用 C++ 模板的强大功能来解决数字信号处理中的一个有用问题：实现任意阶和具有各种属性的规定规范，例如巴特沃斯、切比雪夫、椭圆和 Optimum-L (Legendre) 响应。</font><font style="vertical-align: inherit;">该库是根据 MIT 许可证提供的，因此与专有用途完全兼容。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类被设计为独立的可重用构建块。</font><font style="vertical-align: inherit;">使用部分或全部提供的功能，或通过编写插入到强大框架中的自己的对象来扩展功能。</font><font style="vertical-align: inherit;">只有您需要的代码才会链接到您的应用程序中。</font><font style="vertical-align: inherit;">以下是功能列表：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">专注于 IIR 滤波器而不是无聊的 FIR 滤波器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完整实现所有“RBJ Biquad”Cookbook 滤波器公式</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">巴特沃斯、切比雪夫、椭圆、贝塞尔、勒让德设计</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">低通、高通、带通、带阻变换</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大多数类型的低、高和带架滤波器实现</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">滤波器设置、极点/零点和双二阶系数的平滑插值，以实现无缝参数更改</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用极点和零点表示数字滤波器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Direct Form I、Direct Form II 或用户提供的类实现</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完全分解以最大限度地减少模板实例化</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“设计”层提供对过滤器的运行时自省</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于操作样本数据缓冲区的实用模板函数</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无需调用 malloc 或 new，非常适合嵌入式系统</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">没有外部依赖，只有标准 C++ 库！</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用这些过滤器很简单：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>// Create a Chebyshev type I Band Stop filter of order 3
// with state for processing 2 channels of audio.
Dsp::SimpleFilter &lt;Dsp::ChebyshevI::BandStop &lt;3&gt;, 2&gt; f;
f.setup (3,    // order
         44100,// sample rate
         4000, // center frequency
         880,  // band width
         1);   // ripple dB
f.process (numSamples, arrayOfChannels);
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// Create a Chebyshev type I Band Stop filter of order 3
// with state for processing 2 channels of audio.
Dsp::SimpleFilter <Dsp::ChebyshevI::BandStop <3>, 2> f;
f.setup (3,    // order
         44100,// sample rate
         4000, // center frequency
         880,  // band width
         1);   // ripple dB
f.process (numSamples, arrayOfChannels);" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">随附的演示程序通过使用单独许可的 Juce 应用程序框架（随附）在大多数流行平台上运行，练习该库的所有功能，包括以下功能：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动态界面使用过滤器自省功能创建自身</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实时应用所选过滤器的音频播放</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实时拉伸和幅度调制，无咔嗒声或爆音</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">显示幅度、相位响应和极点/零点位置的图表</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">音频应用程序的线程安全“最佳实践”</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是提供的 DSP Filters 演示应用程序，它演示了该库的功能并使用 Juce 应用程序框架在所有流行平台上运行：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/vinniefalco/DSPFilters/raw/gh-pages/images/DSPFiltersScreenshot.png"><img src="https://github.com/vinniefalco/DSPFilters/raw/gh-pages/images/DSPFiltersScreenshot.png" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您一直在互联网上徒劳地搜索一些用于实现高阶滤波器的源代码，那么就不用再寻找了，因为就是这样！</font><font style="vertical-align: inherit;">无论您是 C++ 或数字信号处理专业的学生、音频插件编写者，甚至是 VST 合成器编码员，“用于数字信号处理的有用 C++ 类集合”都可能适合您！</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网络上的 DSP 滤波器</font></font></h3><a id="user-content-dsp-filters-on-the-web" class="anchor" aria-label="永久链接：网络上的 DSP 滤波器" href="#dsp-filters-on-the-web"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DSP 滤波器官方论坛</font></font><br>
<a href="http://www.kvraudio.com/forum/viewtopic.php?t=249926" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.kvraudio.com/forum/viewtopic.php?t=249926</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DSP 和音频插件讨论论坛</font></font><br>
<a href="http://www.kvraudio.com/forum/viewforum.php?f=33" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.kvraudio.com/forum/viewforum.php?f=33</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Juce官方论坛</font></font><br>
<a href="http://www.rawmaterialsoftware.com/index.php" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.rawmaterialsoftware.com/index.php</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Juce官方网站</font></font><br>
<a href="http://www.rawmaterialsoftware.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.rawmaterialsoftware.com</font></font></a></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">条款和条件</font></font></h3><a id="user-content-terms-and-conditions" class="anchor" aria-label="永久链接：条款和条件" href="#terms-and-conditions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DSP 滤波器库和 DSP 演示应用程序版权所有 (c) 2009，作者：
 </font></font><a href="http://github.com/vinniefalco"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Vinnie Falco源代码根据</font></font></a><font style="vertical-align: inherit;"><a href="http://www.opensource.org/licenses/mit-license.php" rel="nofollow"><font style="vertical-align: inherit;">MIT 许可证</font></a></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
提供
</font><font style="vertical-align: inherit;">
Juce</font><a href="http://www.rawmaterialsoftware.com" rel="nofollow"><font style="vertical-align: inherit;">库由</font></a><a href="http://rawmaterialsoftware.com" rel="nofollow"><font style="vertical-align: inherit;">Raw Material Software</font></a><font style="vertical-align: inherit;">单独授权</font><font style="vertical-align: inherit;">。</font></font><a href="http://www.opensource.org/licenses/mit-license.php" rel="nofollow"><font style="vertical-align: inherit;"></font></a><br><font style="vertical-align: inherit;"></font><a href="http://www.rawmaterialsoftware.com" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="http://rawmaterialsoftware.com" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
</article></div>
