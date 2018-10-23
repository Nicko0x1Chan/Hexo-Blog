---


---

<hr>
<h2 id="title-hello-worldtags--hello-world--1comment-false">title: Hello World<br>
tags:<br>
- HELLO WORLD<br>
- 1<br>
comment: false</h2>
<p>Welcome to <a href="https://hexo.io/">Hexo</a>! This is your very first post. Check <a href="https://hexo.io/docs/">documentation</a> for more info. If you get any problems when using Hexo, you can find the answer in <a href="https://hexo.io/docs/troubleshooting.html">troubleshooting</a> or you can ask me on <a href="https://github.com/hexojs/hexo/issues">GitHub</a>.</p>
<h2 id="quick-start">Quick Start</h2>
<h3 id="create-a-new-post">Create a new post</h3>
<pre class=" language-bash"><code class="prism  language-bash">$ hexo new <span class="token string">"My New Post"</span>
</code></pre>
<p>More info: <a href="https://hexo.io/docs/writing.html">Writing</a></p>
<h3 id="run-server">Run server</h3>
<pre class=" language-bash"><code class="prism  language-bash">$ hexo server
</code></pre>
<p>More info: <a href="https://hexo.io/docs/server.html">Server</a></p>
<h3 id="generate-static-files">Generate static files</h3>
<pre class=" language-bash"><code class="prism  language-bash">$ hexo generate
</code></pre>
<p>More info: <a href="https://hexo.io/docs/generating.html">Generating</a></p>
<h3 id="deploy-to-remote-sites">Deploy to remote sites</h3>
<pre class=" language-bash"><code class="prism  language-bash">$ hexo deploy
</code></pre>
<p>More info: <a href="https://hexo.io/docs/deployment.html">Deployment</a></p>
<p><a href="https://www.zybuluo.com/mdeditor" title="作业部落旗下 Cmd 在线 Markdown 编辑阅读器">『Cmd 技术渲染的沙箱页面，点击此处编写自己的文档』</a></p>
<h2 id="cmd-markdown-简明语法手册">Cmd Markdown 简明语法手册</h2>
<p>标签： Cmd-Markdown</p>
<hr>
<h3 id="斜体和粗体">1. 斜体和粗体</h3>
<p>使用 * 和 ** 表示斜体和粗体。</p>
<p>示例：</p>
<p>这是 <em>斜体</em>，这是 <strong>粗体</strong>。</p>
<h3 id="分级标题">2. 分级标题</h3>
<p>使用 === 表示一级标题，使用 — 表示二级标题。</p>
<p>示例：</p>
<pre><code>这是一个一级标题
============================

这是一个二级标题
--------------------------------------------------

### 这是一个三级标题
</code></pre>
<p>你也可以选择在行首加井号表示不同级别的标题 (H1-H6)，例如：# H1, ## H2, ### H3，#### H4。</p>
<h3 id="外链接">3. 外链接</h3>
<p>使用 [描述](链接地址) 为文字增加外链接。</p>
<p>示例：</p>
<p>这是去往 <a href="http://ghosertblog.github.com">本人博客</a> 的链接。</p>
<h3 id="无序列表">4. 无序列表</h3>
<p>使用 *，+，- 表示无序列表。</p>
<p>示例：</p>
<ul>
<li>无序列表项 一</li>
<li>无序列表项 二</li>
<li>无序列表项 三</li>
</ul>
<h3 id="有序列表">5. 有序列表</h3>
<p>使用数字和点表示有序列表。</p>
<p>示例：</p>
<ol>
<li>有序列表项 一</li>
<li>有序列表项 二</li>
<li>有序列表项 三</li>
</ol>
<h3 id="文字引用">6. 文字引用</h3>
<p>使用 &gt; 表示文字引用。</p>
<p>示例：</p>
<blockquote>
<p>野火烧不尽，春风吹又生。</p>
</blockquote>
<h3 id="行内代码块">7. 行内代码块</h3>
<p>使用 `代码` 表示行内代码块。</p>
<p>示例：</p>
<p>让我们聊聊 <code>html</code>。</p>
<h3 id="代码块">8.  代码块</h3>
<p>使用 四个缩进空格 表示代码块。</p>
<p>示例：</p>
<pre><code>这是一个代码块，此行左侧有四个不可见的空格。
</code></pre>
<h3 id="插入图像">9.  插入图像</h3>
<p>使用 ![描述](图片链接地址) 插入图像。</p>
<p>示例：</p>
<p><img src="https://www.zybuluo.com/static/img/my_head.jpg" alt="我的头像"></p>
<h2 id="cmd-markdown-高阶语法手册">Cmd Markdown 高阶语法手册</h2>
<h3 id="内容目录">1. 内容目录</h3>
<p>在段落中填写 <code>[TOC]</code> 以显示全文内容的目录结构。</p>
<p>[TOC]</p>
<h3 id="标签分类">2. 标签分类</h3>
<p>在编辑区任意行的列首位置输入以下代码给文稿标签：</p>
<p>标签： 数学 英语 Markdown</p>
<p>或者</p>
<p>Tags： 数学 英语 Markdown</p>
<h3 id="删除线">3. 删除线</h3>
<p>使用 ~~ 表示删除线。</p>
<p><s>这是一段错误的文本。</s></p>
<h3 id="注脚">4. 注脚</h3>
<p>使用 [^keyword] 表示注脚。</p>
<p>这是一个注脚<sup class="footnote-ref"><a href="#fn1" id="fnref1">1</a></sup>的样例。</p>
<p>这是第二个注脚<sup class="footnote-ref"><a href="#fn2" id="fnref2">2</a></sup>的样例。</p>
<h3 id="latex-公式">5. LaTeX 公式</h3>
<p>$ 表示行内公式：</p>
<p>质能守恒方程可以用一个很简洁的方程式 <span class="katex--inline"><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>E</mi><mo>=</mo><mi>m</mi><msup><mi>c</mi><mn>2</mn></msup></mrow><annotation encoding="application/x-tex">E=mc^2</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.68333em; vertical-align: 0em;"></span><span class="mord mathit" style="margin-right: 0.05764em;">E</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 0.814108em; vertical-align: 0em;"></span><span class="mord mathit">m</span><span class="mord"><span class="mord mathit">c</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height: 0.814108em;"><span class="" style="top: -3.063em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span></span></span></span></span></span></span></span></span> 来表达。</p>
<p>$$ 表示整行公式：</p>
<p><span class="katex--display"><span class="katex-display"><span class="katex"><span class="katex-mathml"><math><semantics><mrow><munderover><mo>∑</mo><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></munderover><msub><mi>a</mi><mi>i</mi></msub><mo>=</mo><mn>0</mn></mrow><annotation encoding="application/x-tex">\sum_{i=1}^n a_i=0</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 2.92907em; vertical-align: -1.27767em;"></span><span class="mop op-limits"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 1.6514em;"><span class="" style="top: -1.87233em; margin-left: 0em;"><span class="pstrut" style="height: 3.05em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathit mtight">i</span><span class="mrel mtight">=</span><span class="mord mtight">1</span></span></span></span><span class="" style="top: -3.05001em;"><span class="pstrut" style="height: 3.05em;"></span><span class=""><span class="mop op-symbol large-op">∑</span></span></span><span class="" style="top: -4.30001em; margin-left: 0em;"><span class="pstrut" style="height: 3.05em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathit mtight">n</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 1.27767em;"><span class=""></span></span></span></span></span><span class="mspace" style="margin-right: 0.166667em;"></span><span class="mord"><span class="mord mathit">a</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.311664em;"><span class="" style="top: -2.55em; margin-left: 0em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathit mtight">i</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.15em;"><span class=""></span></span></span></span></span></span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 0.64444em; vertical-align: 0em;"></span><span class="mord">0</span></span></span></span></span></span></p>
<p><span class="katex--display"><span class="katex-display"><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>f</mi><mo>(</mo><msub><mi>x</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>x</mi><mi>x</mi></msub><mo separator="true">,</mo><mo>…</mo><mo separator="true">,</mo><msub><mi>x</mi><mi>n</mi></msub><mo>)</mo><mo>=</mo><msubsup><mi>x</mi><mn>1</mn><mn>2</mn></msubsup><mo>+</mo><msubsup><mi>x</mi><mn>2</mn><mn>2</mn></msubsup><mo>+</mo><mo>⋯</mo><mo>+</mo><msubsup><mi>x</mi><mi>n</mi><mn>2</mn></msubsup></mrow><annotation encoding="application/x-tex">f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 </annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord mathit" style="margin-right: 0.10764em;">f</span><span class="mopen">(</span><span class="mord"><span class="mord mathit">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.301108em;"><span class="" style="top: -2.55em; margin-left: 0em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.15em;"><span class=""></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right: 0.166667em;"></span><span class="mord"><span class="mord mathit">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.151392em;"><span class="" style="top: -2.55em; margin-left: 0em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathit mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.15em;"><span class=""></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right: 0.166667em;"></span><span class="minner">…</span><span class="mspace" style="margin-right: 0.166667em;"></span><span class="mpunct">,</span><span class="mspace" style="margin-right: 0.166667em;"></span><span class="mord"><span class="mord mathit">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.151392em;"><span class="" style="top: -2.55em; margin-left: 0em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathit mtight">n</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.15em;"><span class=""></span></span></span></span></span></span><span class="mclose">)</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 1.11111em; vertical-align: -0.247em;"></span><span class="mord"><span class="mord mathit">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.864108em;"><span class="" style="top: -2.453em; margin-left: 0em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span><span class="" style="top: -3.113em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.247em;"><span class=""></span></span></span></span></span></span><span class="mspace" style="margin-right: 0.222222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right: 0.222222em;"></span></span><span class="base"><span class="strut" style="height: 1.11111em; vertical-align: -0.247em;"></span><span class="mord"><span class="mord mathit">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.864108em;"><span class="" style="top: -2.453em; margin-left: 0em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span><span class="" style="top: -3.113em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.247em;"><span class=""></span></span></span></span></span></span><span class="mspace" style="margin-right: 0.222222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right: 0.222222em;"></span></span><span class="base"><span class="strut" style="height: 0.66666em; vertical-align: -0.08333em;"></span><span class="minner">⋯</span><span class="mspace" style="margin-right: 0.222222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right: 0.222222em;"></span></span><span class="base"><span class="strut" style="height: 1.11111em; vertical-align: -0.247em;"></span><span class="mord"><span class="mord mathit">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.864108em;"><span class="" style="top: -2.453em; margin-left: 0em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathit mtight">n</span></span></span><span class="" style="top: -3.113em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.247em;"><span class=""></span></span></span></span></span></span></span></span></span></span></span></p>
<p><span class="katex--display"><span class="katex-display"><span class="katex"><span class="katex-mathml"><math><semantics><mrow><munderover><mo>∑</mo><mrow><mi>k</mi><mo>=</mo><mn>0</mn></mrow><mrow><mi>j</mi><mo>−</mo><mn>1</mn></mrow></munderover><mrow><msub><mover accent="true"><mi>γ</mi><mo stretchy="true">^</mo></mover><mrow><mi>k</mi><mi>j</mi></mrow></msub><msub><mi>z</mi><mi>k</mi></msub></mrow></mrow><annotation encoding="application/x-tex">\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 3.16089em; vertical-align: -1.30211em;"></span><span class="mop op-limits"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 1.85878em;"><span class="" style="top: -1.84789em; margin-left: 0em;"><span class="pstrut" style="height: 3.05em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathit mtight" style="margin-right: 0.03148em;">k</span><span class="mrel mtight">=</span><span class="mord mtight">0</span></span></span></span><span class="" style="top: -3.05em;"><span class="pstrut" style="height: 3.05em;"></span><span class=""><span class="mop op-symbol large-op">∑</span></span></span><span class="" style="top: -4.34711em; margin-left: 0em;"><span class="pstrut" style="height: 3.05em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathit mtight" style="margin-right: 0.05724em;">j</span><span class="mbin mtight">−</span><span class="mord mtight">1</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 1.30211em;"><span class=""></span></span></span></span></span><span class="mspace" style="margin-right: 0.166667em;"></span><span class="mord"><span class="mord"><span class="mord accent"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.67056em;"><span class="" style="top: -3em;"><span class="pstrut" style="height: 3em;"></span><span class="mord"><span class="mord mathit" style="margin-right: 0.05556em;">γ</span></span></span><span class="svg-align" style="top: -3.43056em;"><span class="pstrut" style="height: 3em;"></span><span class="" style="height: 0.24em;"><svg width="100%" height="0.24em" viewBox="0 0 1062 239" preserveAspectRatio="none"><path d="M529 0h5l519 115c5 1 9 5 9 10 0 1-1 2-1 3l-4 22
c-1 5-5 9-11 9h-2L532 67 19 159h-2c-5 0-9-4-11-9l-5-22c-1-6 2-12 8-13z"></path></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.19444em;"><span class=""></span></span></span></span></span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.336108em;"><span class="" style="top: -2.55em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathit mtight" style="margin-right: 0.03148em;">k</span><span class="mord mathit mtight" style="margin-right: 0.05724em;">j</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.286108em;"><span class=""></span></span></span></span></span></span><span class="mord"><span class="mord mathit" style="margin-right: 0.04398em;">z</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.336108em;"><span class="" style="top: -2.55em; margin-left: -0.04398em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathit mtight" style="margin-right: 0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.15em;"><span class=""></span></span></span></span></span></span></span></span></span></span></span></span></p>
<p>访问 <a href="http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference">MathJax</a> 参考更多使用方法。</p>
<h3 id="加强的代码块">6. 加强的代码块</h3>
<p>支持四十一种编程语言的语法高亮的显示，行号显示。</p>
<p>非代码示例：</p>
<pre><code>$ sudo apt-get install vim-gnome
</code></pre>
<p>Python 示例：</p>
<pre class=" language-python"><code class="prism  language-python">@requires_authorization
<span class="token keyword">def</span> <span class="token function">somefunc</span><span class="token punctuation">(</span>param1<span class="token operator">=</span><span class="token string">''</span><span class="token punctuation">,</span> param2<span class="token operator">=</span><span class="token number">0</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token triple-quoted-string string">'''A docstring'''</span>
    <span class="token keyword">if</span> param1 <span class="token operator">&gt;</span> param2<span class="token punctuation">:</span> <span class="token comment"># interesting</span>
        <span class="token keyword">print</span> <span class="token string">'Greater'</span>
    <span class="token keyword">return</span> <span class="token punctuation">(</span>param2 <span class="token operator">-</span> param1 <span class="token operator">+</span> <span class="token number">1</span><span class="token punctuation">)</span> <span class="token operator">or</span> <span class="token boolean">None</span>

<span class="token keyword">class</span> <span class="token class-name">SomeClass</span><span class="token punctuation">:</span>
    <span class="token keyword">pass</span>

<span class="token operator">&gt;&gt;</span><span class="token operator">&gt;</span> message <span class="token operator">=</span> <span class="token triple-quoted-string string">'''interpreter
... prompt'''</span>
</code></pre>
<p>JavaScript 示例：</p>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">/**
* nth element in the fibonacci series.
* @param n &gt;= 0
* @return the nth element, &gt;= 0.
*/</span>
<span class="token keyword">function</span> <span class="token function">fib</span><span class="token punctuation">(</span>n<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">var</span> a <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">,</span> b <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span>
  <span class="token keyword">var</span> tmp<span class="token punctuation">;</span>
  <span class="token keyword">while</span> <span class="token punctuation">(</span><span class="token operator">--</span>n <span class="token operator">&gt;=</span> <span class="token number">0</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    tmp <span class="token operator">=</span> a<span class="token punctuation">;</span>
    a <span class="token operator">+=</span> b<span class="token punctuation">;</span>
    b <span class="token operator">=</span> tmp<span class="token punctuation">;</span>
  <span class="token punctuation">}</span>
  <span class="token keyword">return</span> a<span class="token punctuation">;</span>
<span class="token punctuation">}</span>

document<span class="token punctuation">.</span><span class="token function">write</span><span class="token punctuation">(</span><span class="token function">fib</span><span class="token punctuation">(</span><span class="token number">10</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<h3 id="流程图">7. 流程图</h3>
<h4 id="示例">示例</h4>
<pre class=" language-flow"><code class="prism  language-flow">st<span class="token operator">=&gt;</span>start<span class="token punctuation">:</span> Start<span class="token punctuation">:</span><span class="token operator">&gt;</span>https<span class="token punctuation">:</span><span class="token operator">/</span><span class="token operator">/</span>www<span class="token punctuation">.</span>zybuluo<span class="token punctuation">.</span>com
io<span class="token operator">=&gt;</span>inputoutput<span class="token punctuation">:</span> verification
op<span class="token operator">=&gt;</span>operation<span class="token punctuation">:</span> Your Operation
cond<span class="token operator">=&gt;</span>condition<span class="token punctuation">:</span> Yes or No<span class="token operator">?</span>
sub<span class="token operator">=&gt;</span>subroutine<span class="token punctuation">:</span> Your Subroutine
e<span class="token operator">=&gt;</span>end

st<span class="token operator">-</span><span class="token operator">&gt;</span>io<span class="token operator">-</span><span class="token operator">&gt;</span>op<span class="token operator">-</span><span class="token operator">&gt;</span>cond
<span class="token function">cond</span><span class="token punctuation">(</span>yes<span class="token punctuation">)</span><span class="token operator">-</span><span class="token operator">&gt;</span>e
<span class="token function">cond</span><span class="token punctuation">(</span>no<span class="token punctuation">)</span><span class="token operator">-</span><span class="token operator">&gt;</span>sub<span class="token operator">-</span><span class="token operator">&gt;</span>io
</code></pre>
<h4 id="更多语法参考：流程图语法参考">更多语法参考：<a href="http://adrai.github.io/flowchart.js/">流程图语法参考</a></h4>
<h3 id="序列图">8. 序列图</h3>
<h4 id="示例-1">示例 1</h4>
<pre class=" language-sequence"><code class="prism  language-sequence">Alice-&gt;Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob--&gt;Alice: I am good thanks!
</code></pre>
<h4 id="示例-2">示例 2</h4>
<pre class=" language-sequence"><code class="prism  language-sequence">sequenceDiagram
Title: Here is a title
A-&gt;B: Normal line
B--&gt;C: Dashed line
C-&gt;&gt;D: Open arrow
D--&gt;&gt;A: Dashed open arrow
</code></pre>
<h4 id="更多语法参考：序列图语法参考">更多语法参考：<a href="http://bramp.github.io/js-sequence-diagrams/">序列图语法参考</a></h4>
<h3 id="甘特图">9. 甘特图</h3>
<p>甘特图内在思想简单。基本是一条线条图，横轴表示时间，纵轴表示活动（项目），线条表示在整个期间上计划和实际的活动完成情况。它直观地表明任务计划在什么时候进行，及实际进展与计划要求的对比。</p>
<div class="mermaid"><svg xmlns="http://www.w3.org/2000/svg" id="mermaid-svg-6xilInFX5NMGY5ax" height="100%" viewBox="0 0 500 484"><g></g><g class="grid" transform="translate(75, 434)" fill="none" font-size="10" font-family="sans-serif" text-anchor="middle"><path class="domain" stroke="#000" d="M0.5,-399V0.5H350.5V-399"></path><g class="tick" opacity="1" transform="translate(22.5,0)"><line stroke="#000" y2="-399"></line><text fill="#000" y="3" dy="1em" stroke="none" font-size="10" style="text-anchor: middle;">2014-01-07</text></g><g class="tick" opacity="1" transform="translate(66.5,0)"><line stroke="#000" y2="-399"></line><text fill="#000" y="3" dy="1em" stroke="none" font-size="10" style="text-anchor: middle;">2014-01-09</text></g><g class="tick" opacity="1" transform="translate(109.5,0)"><line stroke="#000" y2="-399"></line><text fill="#000" y="3" dy="1em" stroke="none" font-size="10" style="text-anchor: middle;">2014-01-11</text></g><g class="tick" opacity="1" transform="translate(153.5,0)"><line stroke="#000" y2="-399"></line><text fill="#000" y="3" dy="1em" stroke="none" font-size="10" style="text-anchor: middle;">2014-01-13</text></g><g class="tick" opacity="1" transform="translate(197.5,0)"><line stroke="#000" y2="-399"></line><text fill="#000" y="3" dy="1em" stroke="none" font-size="10" style="text-anchor: middle;">2014-01-15</text></g><g class="tick" opacity="1" transform="translate(241.5,0)"><line stroke="#000" y2="-399"></line><text fill="#000" y="3" dy="1em" stroke="none" font-size="10" style="text-anchor: middle;">2014-01-17</text></g><g class="tick" opacity="1" transform="translate(284.5,0)"><line stroke="#000" y2="-399"></line><text fill="#000" y="3" dy="1em" stroke="none" font-size="10" style="text-anchor: middle;">2014-01-19</text></g><g class="tick" opacity="1" transform="translate(328.5,0)"><line stroke="#000" y2="-399"></line><text fill="#000" y="3" dy="1em" stroke="none" font-size="10" style="text-anchor: middle;">2014-01-21</text></g></g><g><rect x="0" y="48" width="462.5" height="24" class="section section0"></rect><rect x="0" y="72" width="462.5" height="24" class="section section0"></rect><rect x="0" y="96" width="462.5" height="24" class="section section0"></rect><rect x="0" y="120" width="462.5" height="24" class="section section0"></rect><rect x="0" y="144" width="462.5" height="24" class="section section1"></rect><rect x="0" y="168" width="462.5" height="24" class="section section1"></rect><rect x="0" y="192" width="462.5" height="24" class="section section1"></rect><rect x="0" y="216" width="462.5" height="24" class="section section1"></rect><rect x="0" y="240" width="462.5" height="24" class="section section1"></rect><rect x="0" y="264" width="462.5" height="24" class="section section1"></rect><rect x="0" y="288" width="462.5" height="24" class="section section2"></rect><rect x="0" y="312" width="462.5" height="24" class="section section2"></rect><rect x="0" y="336" width="462.5" height="24" class="section section2"></rect><rect x="0" y="360" width="462.5" height="24" class="section section3"></rect><rect x="0" y="384" width="462.5" height="24" class="section section3"></rect><rect x="0" y="408" width="462.5" height="24" class="section section3"></rect></g><g><rect rx="3" ry="3" x="75" y="50" width="44" height="20" class="task  done0"></rect><rect rx="3" ry="3" x="141" y="74" width="65" height="20" class="task  active0"></rect><rect rx="3" ry="3" x="206" y="98" width="110" height="20" class="task  task0"></rect><rect rx="3" ry="3" x="316" y="122" width="109" height="20" class="task  task0"></rect><rect rx="3" ry="3" x="75" y="146" width="22" height="20" class="task  doneCrit1"></rect><rect rx="3" ry="3" x="119" y="170" width="44" height="20" class="task  doneCrit1"></rect><rect rx="3" ry="3" x="163" y="194" width="65" height="20" class="task  activeCrit1"></rect><rect rx="3" ry="3" x="228" y="218" width="110" height="20" class="task  crit1"></rect><rect rx="3" ry="3" x="338" y="242" width="43" height="20" class="task  task1"></rect><rect rx="3" ry="3" x="381" y="266" width="22" height="20" class="task  task1"></rect><rect rx="3" ry="3" x="119" y="290" width="65" height="20" class="task  active2"></rect><rect rx="3" ry="3" x="184" y="314" width="19" height="20" class="task  task2"></rect><rect rx="3" ry="3" x="184" y="338" width="44" height="20" class="task  task2"></rect><rect rx="3" ry="3" x="228" y="362" width="66" height="20" class="task  task3"></rect><rect rx="3" ry="3" x="294" y="386" width="18" height="20" class="task  task3"></rect><rect rx="3" ry="3" x="312" y="410" width="44" height="20" class="task  task3"></rect><text font-size="11" x="124" y="63.5" text-height="20" class="taskTextOutsideRight taskTextOutside0  doneText0">Completed task            </text><text font-size="11" x="173.5" y="87.5" text-height="20" class="taskText taskText0 activeText0">Active task               </text><text font-size="11" x="261" y="111.5" text-height="20" class="taskText taskText0 ">Future task               </text><text font-size="11" x="370.5" y="135.5" text-height="20" class="taskText taskText0 ">Future task2              </text><text font-size="11" x="102" y="159.5" text-height="20" class="taskTextOutsideRight taskTextOutside1  doneCritText1">Completed task in the critical line </text><text font-size="11" x="168" y="183.5" text-height="20" class="taskTextOutsideRight taskTextOutside1  doneCritText1">Implement parser and jison          </text><text font-size="11" x="233" y="207.5" text-height="20" class="taskTextOutsideRight taskTextOutside1 activeCritText1 critText1">Create tests for parser             </text><text font-size="11" x="343" y="231.5" text-height="20" class="taskTextOutsideRight taskTextOutside1  critText1">Future task in critical line        </text><text font-size="11" x="333" y="255.5" text-height="20" class="taskTextOutsideLeft taskTextOutside1 ">Create tests for renderer           </text><text font-size="11" x="376" y="279.5" text-height="20" class="taskTextOutsideLeft taskTextOutside1 ">Add to mermaid                      </text><text font-size="11" x="189" y="303.5" text-height="20" class="taskTextOutsideRight taskTextOutside2 activeText2">Describe gantt syntax               </text><text font-size="11" x="208" y="327.5" text-height="20" class="taskTextOutsideRight taskTextOutside2 ">Add gantt diagram to demo page      </text><text font-size="11" x="233" y="351.5" text-height="20" class="taskTextOutsideRight taskTextOutside2 ">Add another diagram to demo page    </text><text font-size="11" x="299" y="375.5" text-height="20" class="taskTextOutsideRight taskTextOutside3 ">Describe gantt syntax               </text><text font-size="11" x="289" y="399.5" text-height="20" class="taskTextOutsideLeft taskTextOutside3 ">Add gantt diagram to demo page      </text><text font-size="11" x="307" y="423.5" text-height="20" class="taskTextOutsideLeft taskTextOutside3 ">Add another diagram to demo page    </text></g><g><text x="10" y="98" class="sectionTitle sectionTitle0">A section</text><text x="10" y="218" class="sectionTitle sectionTitle1">Critical tasks</text><text x="10" y="326" class="sectionTitle sectionTitle2">Documentation</text><text x="10" y="398" class="sectionTitle sectionTitle3">Last section</text></g><g class="today"><line x1="38393" x2="38393" y1="25" y2="459" class="today"></line></g><text x="250" y="25" class="titleText">Adding GANTT diagram functionality to mermaid</text></svg></div>
<h4 id="更多语法参考：甘特图语法参考">更多语法参考：<a href="https://knsv.github.io/mermaid/#gant-diagrams">甘特图语法参考</a></h4>
<h3 id="mermaid-流程图">10. Mermaid 流程图</h3>
<div class="mermaid"><svg xmlns="http://www.w3.org/2000/svg" id="mermaid-svg-H13AbF52k8xZ1JJs" width="100%" style="max-width: 661.8390655517578px;" viewBox="0 0 661.8390655517578 158"><g transform="translate(-12, -12)"><g class="output"><g class="clusters"></g><g class="edgePaths"><g class="edgePath" style="opacity: 1;"><path class="path" d="M112.546875,91L168.0234375,91L223.5,91" marker-end="url(#arrowhead135)" style="fill:none"></path><defs><marker id="arrowhead135" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g><g class="edgePath" style="opacity: 1;"><path class="path" d="M327.03125,91L352.03125,91L377.5312515258789,91.5" marker-end="url(#arrowhead136)" style="fill:none"></path><defs><marker id="arrowhead136" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g><g class="edgePath" style="opacity: 1;"><path class="path" d="M472.74443837551274,72.62412434963373L531.1359405517578,43L571.5656280517578,43" marker-end="url(#arrowhead137)" style="fill:none"></path><defs><marker id="arrowhead137" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g><g class="edgePath" style="opacity: 1;"><path class="path" d="M472.7444363335729,110.37587464054812L531.1359405517578,139L571.1515655517578,139" marker-end="url(#arrowhead138)" style="fill:none"></path><defs><marker id="arrowhead138" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g></g><g class="edgeLabels"><g class="edgeLabel" transform="translate(168.0234375,91)" style="opacity: 1;"><g transform="translate(-30.4765625,-13)" class="label"><foreignObject width="60.953125" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span class="edgeLabel">Link text</span></div></foreignObject></g></g><g class="edgeLabel" transform="" style="opacity: 1;"><g transform="translate(0,0)" class="label"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel" transform="translate(531.1359405517578,43)" style="opacity: 1;"><g transform="translate(-15.015625,-13)" class="label"><foreignObject width="30.03125" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span class="edgeLabel">One</span></div></foreignObject></g></g><g class="edgeLabel" transform="translate(531.1359405517578,139)" style="opacity: 1;"><g transform="translate(-14.7890625,-13)" class="label"><foreignObject width="29.578125" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span class="edgeLabel">Two</span></div></foreignObject></g></g></g><g class="nodes"><g class="node" id="A" transform="translate(66.2734375,91)" style="opacity: 1;"><rect rx="0" ry="0" x="-46.2734375" y="-23" width="92.546875" height="46"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-36.2734375,-13)"><foreignObject width="72.546875" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Hard edge</div></foreignObject></g></g></g><g class="node" id="B" transform="translate(275.265625,91)" style="opacity: 1;"><rect rx="5" ry="5" x="-51.765625" y="-23" width="103.53125" height="46"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-41.765625,-13)"><foreignObject width="83.53125" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Round edge</div></foreignObject></g></g></g><g class="node" id="C" transform="translate(434.0757827758789,91)" style="opacity: 1;"><polygon points="57.04453125,0 114.0890625,-57.04453125 57.04453125,-114.0890625 0,-57.04453125" rx="5" ry="5" transform="translate(-57.04453125,57.04453125)"></polygon><g class="label" transform="translate(0,0)"><g transform="translate(-30.3828125,-13)"><foreignObject width="60.765625" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Decision</div></foreignObject></g></g></g><g class="node" id="D" transform="translate(618.4953155517578,43)" style="opacity: 1;"><rect rx="0" ry="0" x="-46.9296875" y="-23" width="93.859375" height="46"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-36.9296875,-13)"><foreignObject width="73.859375" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Result one</div></foreignObject></g></g></g><g class="node" id="E" transform="translate(618.4953155517578,139)" style="opacity: 1;"><rect rx="0" ry="0" x="-47.34375" y="-23" width="94.6875" height="46"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-37.34375,-13)"><foreignObject width="74.6875" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Result two</div></foreignObject></g></g></g></g></g></g></svg></div>
<h4 id="更多语法参考：mermaid-流程图语法参考">更多语法参考：<a href="https://knsv.github.io/mermaid/#flowcharts-basic-syntax">Mermaid 流程图语法参考</a></h4>
<h3 id="mermaid-序列图">11. Mermaid 序列图</h3>
<div class="mermaid"><svg xmlns="http://www.w3.org/2000/svg" id="mermaid-svg-XcpuhXTQi0qtKY2t" height="100%" width="100%" style="max-width:450px;" viewBox="-50 -10 450 231"><g></g><g><line id="actor11" x1="75" y1="5" x2="75" y2="220" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="0" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="75" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle;"><tspan x="75" dy="0">Alice</tspan></text></g><g><line id="actor12" x1="275" y1="5" x2="275" y2="220" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="200" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="275" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle;"><tspan x="275" dy="0">John</tspan></text></g><defs><marker id="arrowhead" refX="5" refY="2" markerWidth="6" markerHeight="4" orient="auto"><path d="M 0,0 V 4 L6,2 Z"></path></marker></defs><defs><marker id="crosshead" markerWidth="15" markerHeight="8" orient="auto" refX="16" refY="4"><path fill="black" stroke="#000000" stroke-width="1px" d="M 9,2 V 6 L16,4 Z" style="stroke-dasharray: 0, 0;"></path><path fill="none" stroke="#000000" stroke-width="1px" d="M 0,1 L 6,7 M 6,1 L 0,7" style="stroke-dasharray: 0, 0;"></path></marker></defs><g><text x="175" y="93" class="messageText" style="text-anchor: middle;">Hello John, how are you?</text><line x1="75" y1="100" x2="275" y2="100" class="messageLine0" stroke-width="2" stroke="black" style="fill: none;"></line></g><g><text x="175" y="128" class="messageText" style="text-anchor: middle;">Great!</text><line x1="275" y1="135" x2="75" y2="135" class="messageLine1" stroke-width="2" stroke="black" style="stroke-dasharray: 3, 3; fill: none;"></line></g><g><rect x="0" y="155" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="75" y="187.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle;"><tspan x="75" dy="0">Alice</tspan></text></g><g><rect x="200" y="155" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="275" y="187.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle;"><tspan x="275" dy="0">John</tspan></text></g></svg></div>
<h4 id="更多语法参考：mermaid-序列图语法参考">更多语法参考：<a href="https://knsv.github.io/mermaid/#sequence-diagrams">Mermaid 序列图语法参考</a></h4>
<h3 id="表格支持">12. 表格支持</h3>

<table>
<thead>
<tr>
<th>项目</th>
<th align="right">价格</th>
<th align="center">数量</th>
</tr>
</thead>
<tbody>
<tr>
<td>计算机</td>
<td align="right">$1600</td>
<td align="center">5</td>
</tr>
<tr>
<td>手机</td>
<td align="right">$12</td>
<td align="center">12</td>
</tr>
<tr>
<td>管线</td>
<td align="right">$1</td>
<td align="center">234</td>
</tr>
</tbody>
</table><h3 id="定义型列表">13. 定义型列表</h3>
<dl>
<dt>名词 1</dt>
<dd>
<p>定义 1（左侧有一个可见的冒号和四个不可见的空格）</p>
</dd>
<dt>代码块 2</dt>
<dd>
<p>这是代码块的定义（左侧有一个可见的冒号和四个不可见的空格）</p>
<pre><code>  代码块（左侧有八个不可见的空格）
</code></pre>
</dd>
</dl>
<h3 id="html-标签">14. Html 标签</h3>
<p>本站支持在 Markdown 语法中嵌套 Html 标签，譬如，你可以用 Html 写一个纵跨两行的表格：</p>
<pre class=" language-html"><code class="prism  language-html">    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>table</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>tr</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>th</span> <span class="token attr-name">rowspan</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>2<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>值班人员<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>th</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>th</span><span class="token punctuation">&gt;</span></span>星期一<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>th</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>th</span><span class="token punctuation">&gt;</span></span>星期二<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>th</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>th</span><span class="token punctuation">&gt;</span></span>星期三<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>th</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>tr</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>tr</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>td</span><span class="token punctuation">&gt;</span></span>李强<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>td</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>td</span><span class="token punctuation">&gt;</span></span>张明<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>td</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>td</span><span class="token punctuation">&gt;</span></span>王平<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>td</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>tr</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>table</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<table>
    <tbody><tr>
        <th rowspan="2">值班人员</th>
        <th>星期一</th>
        <th>星期二</th>
        <th>星期三</th>
    </tr>
    <tr>
        <td>李强</td>
        <td>张明</td>
        <td>王平</td>
    </tr>
</tbody></table>
<h3 id="内嵌图标">15. 内嵌图标</h3>
<p>本站的图标系统对外开放，在文档中输入</p>
<pre><code>&lt;i class="icon-weibo"&gt;&lt;/i&gt;
</code></pre>
<p>即显示微博的图标： <i class="icon-weibo"></i></p>
<p><i class="fas fa-address-book"></i></p>
<p>替换 上述 <code>i 标签</code> 内的 <code>icon-weibo</code> 以显示不同的图标，例如：</p>
<pre><code>&lt;i class="icon-renren"&gt;&lt;/i&gt;
</code></pre>
<p>即显示人人的图标： <i class="icon-renren icon-2x"></i></p>
<p>更多的图标和玩法可以参看 <a href="http://fortawesome.github.io/Font-Awesome/3.2.1/icons/">font-awesome</a> 官方网站。</p>
<h3 id="待办事宜-todo-列表">16. 待办事宜 Todo 列表</h3>
<p>使用带有 [ ] 或 [x] （未完成或已完成）项的列表语法撰写一个待办事宜列表，并且支持子列表嵌套以及混用Markdown语法，例如：</p>
<pre class=" language-markdown"><code class="prism  language-markdown"><span class="token list punctuation">-</span> [ ] <span class="token bold"><span class="token punctuation">**</span>Cmd Markdown 开发<span class="token punctuation">**</span></span>
<span class="token code keyword" spellcheck="false">    - [ ] 改进 Cmd 渲染算法，使用局部渲染技术提高渲染效率</span>
<span class="token code keyword" spellcheck="false">    - [ ] 支持以 PDF 格式导出文稿</span>
<span class="token code keyword" spellcheck="false">    - [x] 新增Todo列表功能 [语法参考](https://github.com/blog/1375-task-lists-in-gfm-issues-pulls-comments)</span>
<span class="token code keyword" spellcheck="false">    - [x] 改进 LaTex 功能</span>
<span class="token code keyword" spellcheck="false">        - [x] 修复 LaTex 公式渲染问题</span>
<span class="token code keyword" spellcheck="false">        - [x] 新增 LaTex 公式编号功能 [语法参考](http://docs.mathjax.org/en/latest/tex.html#tex-eq-numbers)</span>
<span class="token list punctuation">-</span> [ ] <span class="token bold"><span class="token punctuation">**</span>七月旅行准备<span class="token punctuation">**</span></span>
<span class="token code keyword" spellcheck="false">    - [ ] 准备邮轮上需要携带的物品</span>
<span class="token code keyword" spellcheck="false">    - [ ] 浏览日本免税店的物品</span>
<span class="token code keyword" spellcheck="false">    - [x] 购买蓝宝石公主号七月一日的船票</span>
</code></pre>
<p>对应显示如下待办事宜 Todo 列表：</p>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> <strong>Cmd Markdown 开发</strong>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> 改进 Cmd 渲染算法，使用局部渲染技术提高渲染效率</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> 支持以 PDF 格式导出文稿</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> 新增Todo列表功能 <a href="https://github.com/blog/1375-task-lists-in-gfm-issues-pulls-comments">语法参考</a></li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> 改进 LaTex 功能
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> 修复 LaTex 公式渲染问题</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> 新增 LaTex 公式编号功能 <a href="http://docs.mathjax.org/en/latest/tex.html#tex-eq-numbers">语法参考</a></li>
</ul>
</li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> <strong>七月旅行准备</strong>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> 准备邮轮上需要携带的物品</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> 浏览日本免税店的物品</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> 购买蓝宝石公主号七月一日的船票</li>
</ul>
</li>
</ul>
<hr class="footnotes-sep">
<section class="footnotes">
<ol class="footnotes-list">
<li id="fn1" class="footnote-item"><p>这是一个 <em>注脚</em> 的 <strong>文本</strong>。 <a href="#fnref1" class="footnote-backref">↩︎</a></p>
</li>
<li id="fn2" class="footnote-item"><p>这是另一个 <em>注脚</em> 的 <strong>文本</strong>。 <a href="#fnref2" class="footnote-backref">↩︎</a></p>
</li>
</ol>
</section>

