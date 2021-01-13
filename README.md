# Feed

## 介绍

本repo是一个RSS的内容更新repo，使用github action实现新消息的更新。

每小时拉取[RSS列表](./list.txt)中的RSS源，并将内容更新在每页上。

历史存档在[这里](./ARCHIVED.md)

### TODO

- [ ] 将RSSHUB迁移到repo上，直接在更新时构建RSSHUB镜像然后本地读取对应端口信息
- [ ] 实现最README页直接展示今天新更新的信息
- [ ] 重新设计sqlite3数据库中字段信息，包括但不限于文章更新时间、拉取时间，文章标题，文章正文内容等
- [ ] 优化更新和对比效率
- [ ] 做好所有rss源适配

## 今日更新

# 2021-1-14

### [Python 中的面向接口编程](http://crossoverjie.top/2021/01/14/basic/python-oop/)

 <p><img alt="" src="https://tva1.sinaimg.cn/large/008eGmZEly1gmmkyd7lu6j31c00u0gx9.jpg" /></p>
<h1 id="前言"><a class="headerlink" href="https://crossoverjie.top/atom.xml#前言" title="前言"></a>前言</h1><p><code>”面向接口编程“</code>写 <code>Java</code> 的朋友耳朵已经可以听出干茧了吧，当然这个思想在 <code>Java</code> 中非常重要，甚至几乎所有的编程语言都需要，毕竟程序具有良好的扩展性、维护性谁都不能拒绝。</p>
<a id="more"></a>
<p>最近无意间看到了我刚开始写 <code>Python</code> 时的部分代码，当时实现的需求有个很明显的特点：</p>
<ul>
<li>不同对象具有公共的行为能力，但具体每个对象的实现方式又各不相同。</li>
</ul>
<p>说人话就是商户需要接入平台，接入的步骤相同，但具体实现不同。</p>
<p>作为一个”资深“ <code>Javaer</code>，需求还没看完我就洋洋洒洒的把各个实现类写好了：</p>
<p><img alt="" src="https://tva1.sinaimg.cn/large/008eGmZEly1gmmkyu72kgj30ho0bodgn.jpg" /></p>
<p>当然最终也顺利实现需求，甚至把组里一个没写过 <code>Java</code> 的大哥唬的一愣一愣的，直呼牛逼。</p>
<p><img alt="" src="https://tva1.sinaimg.cn/large/008eGmZEly1gmmkz0fp9mj301c01c742.jpg" /></p>
<p>不过事后也给我吐槽：</p>
<ul>
<li>你这设计是不错，但是感觉好复杂，跟代码时要找到真正的业务逻辑（实现类）得绕几圈。</li>
</ul>
<p>截止目前 <code>Python</code> 写多了，我总算是能总结他的感受：就是不够 <code>Pythonic</code>。</p>
<p>虽说 <code>Python</code> 没有类似 <code>Java</code> 这样的 <code>Interface</code> 特性，但作为面向对象的高级语言也是支持继承的；</p>
<p>在这里我们也可以利用继承的特性来实现面向接口编程：</p>
<figure class="highlight python"><table><tr><td class="gutter"><pre><div class="line">1</div><div class="line">2</div><div class="line">3</div><div class="line">4</div><div class="line">5</div><div class="line">6</div><div class="line">7</div><div class="line">8</div><div class="line">9</div><div class="line">10</div><div class="line">11</div><div class="line">12</div><div class="line">13</div><div class="line">14</div><div class="line">15</div><div class="line">16</div><div class="line">17</div><div class="line">18</div><div class="line">19</div><div class="line">20</div><div class="line">21</div><div class="line">22</div></pre></td><td class="code"><pre><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">Car</span>:</span></div><div class="line">    <span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(self)</span>:</span></div><div class="line">        <span class="keyword">pass</span></div><div class="line"></div><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">Benz</span><span class="params">(Car)</span>:</span></div><div class="line">    <span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(self)</span>:</span></div><div class="line">        print(<span class="string">"benz run"</span>)</div><div class="line"></div><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">BMW</span><span class="params">(Car)</span>:</span></div><div class="line"></div><div class="line">    <span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(self)</span>:</span></div><div class="line">        print(<span class="string">"bwm run"</span>)</div><div class="line"></div><div class="line"><span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(car)</span>:</span></div><div class="line">    car.run()</div><div class="line"></div><div class="line"><span class="keyword">if</span> __name__ == <span class="string">"__main__"</span>:</div><div class="line">    benz = Benz()</div><div class="line">    bmw = BMW()</div><div class="line"></div><div class="line">    run(benz)</div><div class="line">    run(bmw)</div></pre></td></tr></table></figure>
<p>代码非常简单，在 <code>Python</code> 中也没有类似于 <code>Java</code> 中的 <code>extends</code> 关键字，只需要在类声明末尾用括号包含基类即可。</p>
<p>这样在每个子类中就能单独实现业务逻辑，方便扩展和维护。</p>
<h1 id="类型检查"><a class="headerlink" href="https://crossoverjie.top/atom.xml#类型检查" title="类型检查"></a>类型检查</h1><p>由于 <code>Python</code> 作为一个动态类型语言，无法做到 <code>Java</code> 那样在编译期间校验一个类是否完全实现了某个接口的所有方法。</p>
<p>为此 <code>Python</code> 提供了解决办法，那就是 <code>abc(Abstract Base Classes)</code> ，当我们将基类用 <code>abc</code> 声明时就能近似做到：</p>
<figure class="highlight python"><table><tr><td class="gutter"><pre><div class="line">1</div><div class="line">2</div><div class="line">3</div><div class="line">4</div><div class="line">5</div><div class="line">6</div><div class="line">7</div><div class="line">8</div><div class="line">9</div><div class="line">10</div><div class="line">11</div><div class="line">12</div><div class="line">13</div><div class="line">14</div><div class="line">15</div><div class="line">16</div><div class="line">17</div><div class="line">18</div><div class="line">19</div><div class="line">20</div><div class="line">21</div><div class="line">22</div></pre></td><td class="code"><pre><div class="line"><span class="keyword">import</span> abc</div><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">Car</span><span class="params">(abc.ABC)</span>:</span></div><div class="line"><span class="meta">    @abc.abstractmethod</span></div><div class="line">    <span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(self)</span>:</span></div><div class="line">        <span class="keyword">pass</span></div><div class="line"></div><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">Benz</span><span class="params">(Car)</span>:</span></div><div class="line">    <span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(self)</span>:</span></div><div class="line">        print(<span class="string">"benz run"</span>)</div><div class="line"></div><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">BMW</span><span class="params">(Car)</span>:</span></div><div class="line">    <span class="keyword">pass</span></div><div class="line"></div><div class="line"><span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(car)</span>:</span></div><div class="line">    car.run()</div><div class="line"></div><div class="line"><span class="keyword">if</span> __name__ == <span class="string">"__main__"</span>:</div><div class="line">    benz = Benz()</div><div class="line">    bmw = BMW()</div><div class="line"></div><div class="line">    run(benz)</div><div class="line">    run(bmw)</div></pre></td></tr></table></figure>
<p>一旦有类没有实现方法时，运行期间便会抛出异常：</p>
<figure class="highlight python"><table><tr><td class="gutter"><pre><div class="line">1</div><div class="line">2</div></pre></td><td class="code"><pre><div class="line">bmw = BMW()</div><div class="line">TypeError: Can<span class="string">'t instantiate abstract class BMW with abstract methods run</span></div></pre></td></tr></table></figure>
<p>虽然无法做到在运行之前（毕竟不需要编译）进行校验，但有总比没有好。</p>
<h1 id="鸭子类型"><a class="headerlink" href="https://crossoverjie.top/atom.xml#鸭子类型" title="鸭子类型"></a>鸭子类型</h1><p>以上两种方式看似已经毕竟优雅的实现面向接口编程了，但实际上也不够 <code>Pythonic</code>。</p>
<p>在继续之前我们先聊聊<code>接口</code>的本质到底是什么？</p>
<p>在 <code>Java</code> 这类静态语言中面向接口编程是比较麻烦的，也就是我们常说的子类向父类转型，因此需要编写额外的代码。</p>
<p>带来的好处也是显而易见，只需要父类便可运行。</p>
<p>但我们也不必过于执着于接口，它本身只是一个协议、规范，并不特指 <code>Java</code> 中的 <code>Interface</code>，甚至有些语言压根没有这个关键字。</p>
<p>动态语言的特性也不需要强制校验是否实现了方法。</p>
<p>在 <code>Python</code> 中我们可以利用鸭子类型来优雅的实现面向接口编程。</p>
<p>在这之前先了解下鸭子类型，借用维基百科的说法：</p>
<ul>
<li>“当看到一只鸟走起来像鸭子、游泳起来像鸭子、叫起来也像鸭子，那么这只鸟就可以被称为鸭子。”</li>
</ul>
<p>我用大白话翻译下就是：</p>
<p>即便两个完全不想干的类，如果他们都实现了相同的方法，那就可以把他们当做同一类型的类来使用。</p>
<p>举个简单例子：</p>
<figure class="highlight python"><table><tr><td class="gutter"><pre><div class="line">1</div><div class="line">2</div><div class="line">3</div><div class="line">4</div><div class="line">5</div><div class="line">6</div><div class="line">7</div><div class="line">8</div><div class="line">9</div><div class="line">10</div><div class="line">11</div><div class="line">12</div><div class="line">13</div><div class="line">14</div><div class="line">15</div><div class="line">16</div></pre></td><td class="code"><pre><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">Order</span>:</span></div><div class="line">    <span class="function"><span class="keyword">def</span> <span class="title">create</span><span class="params">(self)</span>:</span></div><div class="line">        <span class="keyword">pass</span></div><div class="line"></div><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">User</span>:</span></div><div class="line">    <span class="function"><span class="keyword">def</span> <span class="title">create</span><span class="params">(self)</span>:</span></div><div class="line">        <span class="keyword">pass</span></div><div class="line"></div><div class="line"><span class="function"><span class="keyword">def</span> <span class="title">create</span><span class="params">(obj)</span>:</span></div><div class="line">    obj.create()</div><div class="line"></div><div class="line"><span class="keyword">if</span> __name__ == <span class="string">"__main__"</span>:</div><div class="line">    order = Order()</div><div class="line">    user = User()</div><div class="line">    create(order)</div><div class="line">    create(user)</div></pre></td></tr></table></figure>
<p>这里的 <code>order</code> 和 <code>user</code> 本身完全没有关系，只是他们都有相同方法，又得益于动态语言没法校验类型的特点，所以完全可以在运行的时候认为他们是同一种类型。</p>
<p>因此基于鸭子类型，之前的代码我们可以稍作简化：</p>
<figure class="highlight python"><table><tr><td class="gutter"><pre><div class="line">1</div><div class="line">2</div><div class="line">3</div><div class="line">4</div><div class="line">5</div><div class="line">6</div><div class="line">7</div><div class="line">8</div><div class="line">9</div><div class="line">10</div><div class="line">11</div><div class="line">12</div><div class="line">13</div><div class="line">14</div><div class="line">15</div><div class="line">16</div><div class="line">17</div><div class="line">18</div><div class="line">19</div><div class="line">20</div><div class="line">21</div></pre></td><td class="code"><pre><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">Car</span>:</span></div><div class="line">    <span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(self)</span>:</span></div><div class="line">        <span class="keyword">pass</span></div><div class="line"></div><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">Benz</span>:</span></div><div class="line">    <span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(self)</span>:</span></div><div class="line">        print(<span class="string">"benz run"</span>)</div><div class="line"></div><div class="line"><span class="class"><span class="keyword">class</span> <span class="title">BMW</span>:</span></div><div class="line">    <span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(self)</span>:</span></div><div class="line">        print(<span class="string">"bwm run"</span>)</div><div class="line"></div><div class="line"><span class="function"><span class="keyword">def</span> <span class="title">run</span><span class="params">(car)</span>:</span></div><div class="line">    car.run()</div><div class="line"></div><div class="line"><span class="keyword">if</span> __name__ == <span class="string">"__main__"</span>:</div><div class="line">    benz = Benz()</div><div class="line">    bmw = BMW()</div><div class="line"></div><div class="line">    run(benz)</div><div class="line">    run(bmw)</div></pre></td></tr></table></figure>
<p>因为在鸭子类型中我们在意的是它的行为，而不是他们的类型；所以完全可以不用继承便可以实现面向接口编程。</p>
<h1 id="总结"><a class="headerlink" href="https://crossoverjie.top/atom.xml#总结" title="总结"></a>总结</h1><p>我觉得平时没有接触过动态类型语言的朋友，在了解完这些之后会发现新大陆，就像是 <code>Python</code> 老手第一次使用 <code>Java</code> 时；虽然觉得语法啰嗦，但也会羡慕它的类型检查、参数验证这类特点。</p>
<p>动静语言之争这里不做讨论了，各有各的好，鞋好不好穿只有自己知道。</p>
<p>随便提一下其实不止动态语言具备鸭子类型，有些静态语言也能玩这个骚操作，感兴趣下次再介绍。</p>

### [2020年高校毕业生求职研究报告](http://mi.talkingdata.com/report-detail.html?id=990)

### error read: http://www.bigdatainterview.com/feed/

### [Cluedo](https://datagenetics.com/blog/january42021/index.html)

### [如果要给这轮牛市起个名字，我觉得是“改革牛”](http://www.jintiankansha.me/t/5nxgOccdbJ)

### [四螺旋DNA结构你听说过没有](http://jandan.net/p/108339)

### [关于结婚的话题：彩礼，婚房，和爱情](http://jandan.net/p/108345)

### [CIA关于UFO的完整档案已被解密](http://jandan.net/p/108344)

### [海中霸凌事件：会殴打鱼类的章鱼](http://jandan.net/p/108343)

### [输给了一阵狂风的欧洲最强战舰](http://jandan.net/p/108340)

### [通过编写一个简单的游戏学习 C 语言](https://linux.cn/article-13013-1.html?utm_source=rss&utm_medium=rss)

### [从 Linux 命令行进行打印](https://linux.cn/article-13012-1.html?utm_source=rss&utm_medium=rss)

### [【Rust日报】2021-01-13 -- Open Source Security, Inc.宣布为Rust的GCC前端提供资金](https://rustcc.cn/article?id=58a22139-4cdb-4141-a069-650b4fdc816a)

### [【Discovering and exploring mmap using Go】网页链接 使用Go发现和探索mmap。 网路冷眼技术分享 #科技暖心季# [图片]](https://weibo.com/1715118170/JD3eLqt4M)

### [【Department of Defense and Department of Commerce Explore 5G Challenge to Develop Open 5G Systems 】网页链接 美国🇺🇸国防部和商务部探索5G挑战以开...](https://weibo.com/1715118170/JD32e2tVw)

### [#绿洲摄影#中国.成都.武侯祠.红墙夹道 醉美红墙绿竹 绿洲 [图片]](https://weibo.com/1715118170/JD2ZHF5kF)

### [#绿洲摄影#腊梅花开 在南京明孝陵古墙的深红色背景下，金色的腊梅花盛开，呈现出一幅标志性的冬季画卷。 绿洲 [图片][图片][图片][图片]](https://weibo.com/1715118170/JD2SQvF35)

### [【What Silicon Valley gets about engineers that traditional companies do not】网页链接 硅谷对工程师的了解是传统公司所不具备的。网路冷眼技术分享 #科技...](https://weibo.com/1715118170/JD2QfaoOf)

### [【Understanding Image Contrast Algorithms】网页链接 了解图像对比度算法。 网路冷眼技术分享 #科技暖心季# [图片][图片][图片][图片][图片][图片][图片][图片...](https://weibo.com/1715118170/JD2DS2sdj)

### error read: http://www.waerfa.com/feed

### error read: http://www.bigdatainterview.com/feed/