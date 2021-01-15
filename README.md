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

# 2021-1-15

### error read: http://www.jintiankansha.me/rss/GEYDCOBUPRRWGMDBGFSDIZTGMM2GCZRVMQZGGNRQHBRTQZLEME4TQYLFGJRDKZBTGI2TSZJUGM======

### [社保卡何时全国统一？人社部回应来了](https://m.21jingji.com/article/20210114/herald/f7adc120208595ee589f45f7633407fc.html)

### [nacos 出现严重安全漏洞，特殊 UA 可以绕过所有鉴权，有用了的小伙伴注意了……](https://www.v2ex.com/t/744865)

### [首次发现非光合细菌中的生物钟](http://jandan.net/p/108331)

### [知道什么是抗营养素吗](http://jandan.net/p/108346)

### [一美男子血液中长出“致幻蘑菇”](http://jandan.net/p/108349)

### [火车千足虫每8年就会席卷日本山区](http://jandan.net/p/108342)

### [Virtual Machine Startup Shells Closes the Digital Divide One Cloud Computer at a Time](https://www.linuxjournal.com/content/virtual-machine-startup-shells-closes-digital-divide-one-cloud-computer-time)

### [【OpenSocial Specification】网页链接 开放社会规范。 [图片]](https://weibo.com/1715118170/JDcEYxBOG)

### [【Lulu – Mac open-source firewall that aims to block unknown outgoing connections】网页链接 Lulu – Mac开源防火墙，旨在阻止未知的传出连接。网路冷眼技...](https://weibo.com/1715118170/JDcsIBGDu)

### [#绿洲摄影#中国.云南.大理.洱海.小普陀 绿洲 [图片]](https://weibo.com/1715118170/JDcmqeVFH)

### [【Superintelligence cannot be contained: Lessons from Computability Theory】网页链接 论 文《不能包含超级智能：可计算性理论的教训》。 [图片]](https://weibo.com/1715118170/JDcgVf5qk)

### [【A cool Drag-and-Drop implementation for Svelte】网页链接 Svelte的一个很酷的拖放实现。 网路冷眼技术分享 #科技暖心季# [图片]](https://weibo.com/1715118170/JDc4myjSV)

### [Recognizing Pose Similarity in Images and Videos](http://feedproxy.google.com/~r/blogspot/gJZg/~3/3l_KQibU2Bw/recognizing-pose-similarity-in-images.html)

 <span class="byline-author">Posted by Jennifer J. Sun, Student Researcher and Ting Liu, Senior Software Engineer, Google Research</span> <p>Everyday actions, such as jogging, reading a book, pouring water, or playing sports, can be viewed as a sequence of <a href="https://en.wikipedia.org/wiki/Pose_(computer_vision)">poses</a>, consisting of the position and orientation of a person’s body. An understanding of poses from images and videos is a crucial step for enabling a range of applications, including <a href="https://ai.googleblog.com/2019/03/real-time-ar-self-expression-with.html">augmented reality</a> display, <a href="https://blog.google/technology/ai/move-mirror-you-move-and-80000-images-move-you/">full-body gesture control</a>, and <a href="https://ai.googleblog.com/2020/06/repnet-counting-repetitions-in-videos.html">physical exercise quantification</a>. However, a 3-dimensional pose captured in two dimensions in images and videos appears different depending on  the viewpoint of the camera. The ability to recognize similarity in 3D pose using only 2D information will help vision systems better understand the world. </p><p>In “<a href="https://arxiv.org/abs/1912.01001">View-Invariant Probabilistic Embedding for Human Pose</a>” (Pr-VIPE), a spotlight paper at <a href="https://eccv2020.eu/">ECCV 2020</a>, we present a new algorithm for human pose perception that recognizes similarity in human body poses across different camera views by mapping <a href="https://cocodataset.org/#keypoints-2020">2D body pose keypoints</a> to a view-invariant embedding space. This ability enables tasks, such as pose retrieval, action recognition, action video synchronization, and more. Compared to <a href="https://openaccess.thecvf.com/content_ICCV_2017/papers/Martinez_A_Simple_yet_ICCV_2017_paper.pdf">existing models</a> that directly map 2D pose keypoints to 3D pose keypoints, the Pr-VIPE embedding space is (1) view-invariant, (2) <a href="https://en.wikipedia.org/wiki/Normal_distribution">probabilistic</a> in order to capture 2D input ambiguity, and (3) does not require <a href="https://en.wikipedia.org/wiki/Camera_resectioning#Projection">camera parameters</a> during training or inference. Trained with in-lab setting data, the model works on in-the-wild images out of the box, given a reasonably good 2D pose estimator (e.g., <a href="https://arxiv.org/pdf/1803.08225.pdf">PersonLab</a>, <a href="https://ai.googleblog.com/2020/08/on-device-real-time-body-pose-tracking.html">BlazePose</a>, among others). The model is simple, results in compact embeddings, and can be trained (in ~1 day) using 15 CPUs. We have released the code on <a href="https://github.com/google-research/google-research/tree/master/poem">our GitHub repo</a>.  </p><table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto;"><tbody><tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-RNUg7WWiVhI/X_91h1QzsBI/AAAAAAAAG_4/B2wCJOoi-ssxWb9rfydHk3YGUsxWA895ACLcBGAsYHQ/s640/image16.gif" style="margin-left: auto; margin-right: auto;"><img border="0" height="570" src="https://1.bp.blogspot.com/-RNUg7WWiVhI/X_91h1QzsBI/AAAAAAAAG_4/B2wCJOoi-ssxWb9rfydHk3YGUsxWA895ACLcBGAsYHQ/w640-h570/image16.gif" width="640" /></a></td></tr><tr><td class="tr-caption" style="text-align: center;">Pr-VIPE can be directly applied to align videos from different views.</td></tr></tbody></table><p><b>Pr-VIPE </b><br />The input to Pr-VIPE is a set of 2D keypoints, from any 2D pose estimator that produces a minimum of <a href="https://cocodataset.org/#keypoints-2020">13 body keypoints</a>, and the output is the <a href="https://en.wikipedia.org/wiki/Normal_distribution">mean and variance</a> of the pose embedding. The distances between embeddings of 2D poses correlate to their similarities in absolute 3D pose space. Our approach is based on two observations: </p><ul><li>The same 3D pose may appear very different in 2D as the viewpoint changes. </li><li>The same 2D pose can be <a href="https://en.wikipedia.org/wiki/3D_projection#Perspective_projection">projected</a> from different 3D poses. </li></ul><p>The first observation motivates the need for view-invariance. To accomplish this, we define the <em>matching probability</em>, i.e., the likelihood that different 2D poses were projected from the same, or similar 3D poses. The matching probability predicted by Pr-VIPE for matching pose pairs should be higher than for non-matching pairs. </p><p>To address the second observation, Pr-VIPE utilizes a probabilistic embedding formulation. Because many 3D poses can project to the same or similar 2D poses, the model input exhibits an inherent ambiguity that is difficult to capture through <a href="https://en.wikipedia.org/wiki/Deterministic_algorithm">deterministic</a> mapping point-to-point in embedding space. Therefore, we map a 2D pose through a probabilistic mapping to an embedding distribution, of which we use the variance to represent the uncertainty of the input 2D pose. As an example, in the figure below the third 2D view of the 3D pose on the left is similar to the first 2D view of a different 3D pose on the right, so we map them into a similar location in the embedding space with large variances. </p><table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto;"><tbody><tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-UxnxKO-tuG4/X_92DyZPcHI/AAAAAAAAHAA/f5p28lqJbochbIg-FU0Vj9CzvXVXzz-TwCLcBGAsYHQ/s954/image6.jpg" style="margin-left: auto; margin-right: auto;"><img border="0" height="406" src="https://1.bp.blogspot.com/-UxnxKO-tuG4/X_92DyZPcHI/AAAAAAAAHAA/f5p28lqJbochbIg-FU0Vj9CzvXVXzz-TwCLcBGAsYHQ/w640-h406/image6.jpg" width="640" /></a></td></tr><tr><td class="tr-caption" style="text-align: center;">Pr-VIPE enables vision systems to recognize 2D poses across views. We embed 2D poses using Pr-VIPE such that the embeddings are (1) view-invariant (2D projections of similar 3D poses are embedded close together) and (2) probabilistic. By embedding detected 2D poses, Pr-VIPE enables direct retrieval of pose images from different views, and can also be applied to action recognition and video alignment.</td></tr></tbody></table><em>View-Invariance</em><br />During training, we use 2D poses from two sources: <a href="http://vision.imar.ro/human3.6m/description.php">multi-view images</a> and <a href="https://en.wikipedia.org/wiki/3D_projection#Perspective_projection">projections</a> of groundtruth 3D poses. <a href="https://en.wikipedia.org/wiki/Triplet_loss">Triplets</a> of 2D poses (anchor, positive, and negative) are selected from a batch, where the anchor and positive are two different projections of the same 3D pose, and the negative is a projection of a non-matching 3D pose. Pr-VIPE then estimates the matching probability of 2D pose pairs from their embeddings. <br />During training, we push the matching probability of positive pairs to be close to 1 with a positive pairwise loss in which we minimize the embedding distance between positive pairs, and the matching probability of negative pairs to be small by maximizing the ratio of the matching probabilities between positive and negative pairs with a triplet ratio loss.  <br /><table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto;"><tbody><tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-jghZ4_x8VeM/X_92Pzy896I/AAAAAAAAHAE/UsuxcBVMGacJQX6UOuyfiXBD1g-aA_A8wCLcBGAsYHQ/s1254/image13.jpg" style="margin-left: auto; margin-right: auto;"><img border="0" height="230" src="https://1.bp.blogspot.com/-jghZ4_x8VeM/X_92Pzy896I/AAAAAAAAHAE/UsuxcBVMGacJQX6UOuyfiXBD1g-aA_A8wCLcBGAsYHQ/w640-h230/image13.jpg" width="640" /></a></td></tr><tr><td class="tr-caption" style="text-align: center;">Overview of the Pr-VIPE model. During training, we apply three losses (triplet ratio loss, positive pairwise loss, and a prior loss that applies a unit Gaussian prior to our embeddings). During inference, the model maps an input 2D pose to a probabilistic, view-invariant embedding.</td></tr></tbody></table><em>Probabilistic Embedding</em><br />Pr-VIPE maps a 2D pose to a probabilistic embedding as a <a href="https://en.wikipedia.org/wiki/Multivariate_normal_distribution">multivariate Gaussian distribution using</a> a <a href="https://arxiv.org/abs/1810.00319">sampling-based approach</a> for similarity score computation between two distributions. During training, we use a Gaussian prior loss to regularize the predicted distribution. <p><b>Evaluation</b><br />We propose a new <em>cross-view pose retrieval</em> benchmark to evaluate the view-invariance property of the embedding. Given a monocular pose image, cross-view retrieval aims to retrieve the same pose from different views without using camera parameters. The results demonstrate that Pr-VIPE retrieves poses more accurately across views compared to baseline methods in both evaluated datasets (<a href="http://vision.imar.ro/human3.6m/description.php">Human3.6M</a>, <a href="http://gvv.mpi-inf.mpg.de/3dhp-dataset/">MPI-INF-3DHP</a>). </p><table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto;"><tbody><tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-dqjpSmDUuVk/X_92X439bRI/AAAAAAAAHAM/ODgkBCGa23wYpVgwEMhQ6k_9pmkZSyv2gCLcBGAsYHQ/s1611/image9.png" style="margin-left: auto; margin-right: auto;"><img border="0" height="290" src="https://1.bp.blogspot.com/-dqjpSmDUuVk/X_92X439bRI/AAAAAAAAHAM/ODgkBCGa23wYpVgwEMhQ6k_9pmkZSyv2gCLcBGAsYHQ/w640-h290/image9.png" width="640" /></a></td></tr><tr><td class="tr-caption" style="text-align: center;">Pr-VIPE retrieves poses across different views more accurately relative to the baseline method (<a href="https://openaccess.thecvf.com/content_ICCV_2017/papers/Martinez_A_Simple_yet_ICCV_2017_paper.pdf">3D pose estimation</a>).</td></tr></tbody></table><p>Common 3D pose estimation methods (such as the <a href="https://openaccess.thecvf.com/content_ICCV_2017/papers/Martinez_A_Simple_yet_ICCV_2017_paper.pdf">simple baseline</a> used for comparison above, <a href="https://arxiv.org/abs/1904.03345">SemGCN</a>, and <a href="https://arxiv.org/abs/1903.02330">EpipolarPose</a>, amongst many others), predict 3D poses in camera coordinates, which are not directly view-invariant. Thus, <a href="https://en.wikipedia.org/wiki/Procrustes_analysis">rigid alignment</a> between every query-index pair is required for retrieval using estimated 3D poses, which is computationally expensive due to the need for <a href="https://en.wikipedia.org/wiki/Singular_value_decomposition">singular value decomposition</a> (SVD). In contrast, Pr-VIPE embeddings can be directly used for distance computation in Euclidean space, without any post-processing. </p><p><b>Applications</b><br />View-invariant pose embedding can be applied to many image and video related tasks. Below, we show Pr-VIPE applied to cross-view retrieval on in-the-wild images without using camera parameters.</p><p><i></i></p><table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto;"><tbody><tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-Y6wz_YqHthc/X_92-Pa-qOI/AAAAAAAAHAk/ez9D_xToW_sZE2Rwio4VQot0tFeezJw9ACLcBGAsYHQ/s1181/Pr-VIPE-InTheWild.png" style="margin-left: auto; margin-right: auto;"><img border="0" height="538" src="https://1.bp.blogspot.com/-Y6wz_YqHthc/X_92-Pa-qOI/AAAAAAAAHAk/ez9D_xToW_sZE2Rwio4VQot0tFeezJw9ACLcBGAsYHQ/w640-h538/Pr-VIPE-InTheWild.png" width="640" /></a></td></tr><tr><td class="tr-caption" style="text-align: center;"></td></tr></tbody></table><i><br />We can retrieve in-the-wild images from different views without using camera parameters by embedding the detected 2D pose using Pr-VIPE. Using the query image (top row), we search for a matching pose from a different camera view and we show the nearest neighbor retrieval (bottom row). This enables us to search for matching poses across camera views more easily. </i><p></p><p>The same Pr-VIPE model can also be used for video alignment. To do so, we stack Pr-VIPE embeddings within a small time window, and use the <a href="https://en.wikipedia.org/wiki/Dynamic_time_warping">dynamic time warping</a> (DTW) algorithm to align video pairs.  </p><table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto;"><tbody><tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-4GrUP63WOvY/X_93G9b398I/AAAAAAAAHAo/zwnsATDSkGUW22to6BbZwPpToITe1QKMQCLcBGAsYHQ/s640/image1.gif" style="margin-left: auto; margin-right: auto;"><img border="0" height="570" src="https://1.bp.blogspot.com/-4GrUP63WOvY/X_93G9b398I/AAAAAAAAHAo/zwnsATDSkGUW22to6BbZwPpToITe1QKMQCLcBGAsYHQ/w640-h570/image1.gif" width="640" /></a></td></tr><tr><td class="tr-caption" style="text-align: center;">Manual video alignment is difficult and time-consuming. Here, Pr-VIPE is applied to automatically align videos of the same action repeated from different views.</td></tr></tbody></table><p>The video alignment distance calculated via DTW can then be used for action recognition by classifying videos using <a href="https://en.wikipedia.org/wiki/Nearest_neighbor_search">nearest neighbor search</a>. We evaluate the Pr-VIPE embedding using the <a href="http://dreamdragon.github.io/PennAction/">Penn Action</a> dataset and demonstrate that using the Pr-VIPE embedding without fine-tuning on the target dataset, yields highly competitive recognition accuracy. In addition, we show that Pr-VIPE even achieves relatively accurate results using only videos from a single view in the index set. </p><table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto;"><tbody><tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-ah2jdq78hmE/X_93O1awojI/AAAAAAAAHAw/BwS5Kggqo80wlD82alhQdsQiOrhiaRUDwCLcBGAsYHQ/s1127/image15.png" style="margin-left: auto; margin-right: auto;"><img border="0" height="190" src="https://1.bp.blogspot.com/-ah2jdq78hmE/X_93O1awojI/AAAAAAAAHAw/BwS5Kggqo80wlD82alhQdsQiOrhiaRUDwCLcBGAsYHQ/w640-h190/image15.png" width="640" /></a></td></tr><tr><td class="tr-caption" style="text-align: center;">Pr-VIPE recognizes action across views using pose inputs only, and is comparable to or better than methods using pose only or with additional context information (such as <a href="https://arxiv.org/abs/1603.04037">Iqbal et al.</a>, <a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Recognizing_Human_Actions_CVPR_2018_paper.pdf">Liu and Yuan</a>, <a href="https://arxiv.org/abs/1912.08077">Luvizon et al.</a>, and <a href="https://openaccess.thecvf.com/content_ICCV_2017/papers/Du_RPAN_An_End-To-End_ICCV_2017_paper.pdf">Du et al.</a>). When action labels are only available for videos from a single view, Pr-VIPE (1-view only) can still achieve relatively accurate results.</td></tr></tbody></table><p><b>Conclusion</b><br />We introduce the Pr-VIPE model for mapping 2D human poses to a view-invariant probabilistic embedding space, and show that the learned  embeddings can be directly used for pose retrieval, action recognition, and video alignment. Our cross-view retrieval benchmark can be used to test the view-invariant property of other embeddings. We look forward to hearing about what you can do with pose embeddings! </p><p><b>Acknowledgments</b><br /><em>Special thanks to Jiaping Zhao, Liang-Chieh Chen, Long Zhao (Rutgers University), Liangzhe Yuan, Yuxiao Wang, Florian Schroff, Hartwig Adam, and the Mobile Vision team for the wonderful collaboration and support.</em></p><div class="feedflare">
<a href="http://feeds.feedburner.com/~ff/blogspot/gJZg?a=3l_KQibU2Bw:DI8hFWQcDuk:yIl2AUoC8zA"><img border="0" src="http://feeds.feedburner.com/~ff/blogspot/gJZg?d=yIl2AUoC8zA" /></a>
</div><img alt="" height="1" src="http://feeds.feedburner.com/~r/blogspot/gJZg/~4/3l_KQibU2Bw" width="1" />

### [成为自己，姚安娜出道纪录片「破格公主」](https://app.vmovier.com/apiv3/post/view?postid=60975)

### [知乎十周年品牌短片「有问题就会有答案」](https://app.vmovier.com/apiv3/post/view?postid=60973)

### [超震撼气象延时「天象Sky-Lapse 2020」](https://app.vmovier.com/apiv3/post/view?postid=60971)

### [Insta360 年度回顾「Best of 2020」](https://app.vmovier.com/apiv3/post/view?postid=60960)

### [表情包也能出专辑「时髦的popo猫」](https://app.vmovier.com/apiv3/post/view?postid=60964)

### [泰国广告发话了「看电影请关机」](https://app.vmovier.com/apiv3/post/view?postid=60958)

### [旅拍博主的声音日记「我眼中的2020」](https://app.vmovier.com/apiv3/post/view?postid=60968)

### [创意视觉欺诈术「男巫2020合集」](https://app.vmovier.com/apiv3/post/view?postid=60934)

### [大众一镜到底创意广告「历史的车轮」](https://app.vmovier.com/apiv3/post/view?postid=60969)

### [中国自动驾驶发展报告2020（上）： 感知篇——浪潮已至](http://www.jintiankansha.me/t/2a24CornNi)

### error read: http://www.waerfa.com/feed

### error read: http://www.bigdatainterview.com/feed/

### [Word Ladders and Equivalence Classes](https://datagenetics.com/blog/january52021/index.html)

### [【A Brief History of Consumer Culture】网页链接 消费文化简史。在20世纪的整个过程中，资本主义通过将普通人塑造成对更多东西有不可抑制的渴望的消费者来保持...](https://weibo.com/1715118170/JDeeve5Ho)

### error read: http://www.jintiankansha.me/rss/GEYDCOBUPRRWGMDBGFSDIZTGMM2GCZRVMQZGGNRQHBRTQZLEME4TQYLFGJRDKZBTGI2TSZJUGM======

### [[CL]《Robustness Gym: Unifying the NLP Evaluation Landscape》K Goel, N Rajani, J Vig, S Tan, J Wu, S Zheng, C Xiong, M Bansal, C Ré [Stanford Univers...](https://weibo.com/1402400261/JDeum3Fum)

### [《今日学术视野(2021.1.15)》网页链接](https://weibo.com/1402400261/JDehlDxhy)

### [早！[太阳] #早安# [图片]](https://weibo.com/1402400261/JDegju5vw)

### [【I received first-ever donation on my open-source side project and it felt great】网页链接 我在开源方面的项目中获得了首次捐款，感觉很棒。开源地址托管...](https://weibo.com/1715118170/JDequr4dL)

### error read: http://www.bigdatainterview.com/feed/

### [数学是人类的发明，还是发现？](https://daily.zhihu.com/story/9732029)

### [如果公司开始推行超长时间加班制度，应当如何自救？](https://daily.zhihu.com/story/9732026)

### [人类为什么会孜孜不倦地去探索未知？好奇心的意义是什么?](https://daily.zhihu.com/story/9732019)

### [地球上有哪些罕见的自然奇观？](https://daily.zhihu.com/story/9732018)

### [为什么古时东南亚都是印度化而非汉化？](https://daily.zhihu.com/story/9732012)

### [瞎扯 · 如何正确地吐槽](https://daily.zhihu.com/story/9732030)

### [CrateDb在携程机票BI的实践](https://www.infoq.cn/article/pym3FDYeOz0oVbPFhjED)

### [[LG]《Fast convolutional neural networks on FPGAs with hls4ml》T Aarrestad, V Loncar, M Pierini, S Summers, J Ngadiuba, C Petersson, H Linander, Y Iiy...](https://weibo.com/1402400261/JDeHqgOLJ)

### [[CV]《Big Self-Supervised Models Advance Medical Image Classification》S Azizi, B Mustafa, F Ryan, Z Beaver, J Freyberg, J Deaton, A Loh, A Karthikesa...](https://weibo.com/1402400261/JDeDlkjND)

### [【Building a simple Web server with arsd CGI framework in D programming language】网页链接 以D编程语言使用arsd CGI框架构建简单的Web服务器。网路冷眼技...](https://weibo.com/1715118170/JDf1rmYYH)

### [【How to Keep Up to Date with Web Development】网路冷眼技术分享 #科技暖心季# [图片][图片]](https://weibo.com/1715118170/JDeOQlEkr)

### [【What Is a Gamma Squeeze in the Context of Stock Trading?】网页链接 股票交易中的伽玛挤压是什么？ [图片]](https://weibo.com/1715118170/JDeCIDPds)

### error read: http://www.bigdatainterview.com/feed/

### [青年图摘0115！正义在美色面前不值一提](https://qingniantuzhai.com/qing-nian-tu-zhai-0115-3/)

 <!--kg-card-begin: markdown--><img alt="青年图摘0115！正义在美色面前不值一提" src="https://qingniantuzhai.com/content/images/2021/01/897c4370gy1gmn8l2yuapj20zk0qoqv5.jpg" /><p>【1】天下武功，唯快不破<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx4.sinaimg.cn/mw1024/00893JKXly1gmnd5wmlsmg307s0dunpe.gif" /></p>
<p>【2】名字太长惹的祸<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx1.sinaimg.cn/mw600/006ahuzrly1gmncjwtsf7j30st15hgpq.jpg" /></p>
<p>【3】特朗普才是最棒的总统<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx2.sinaimg.cn/mw600/005PTIKbly1gmmck96vzbj30j60lw1ex.jpg" /></p>
<p>【4】它吃让它吃<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx4.sinaimg.cn/mw600/00893JKXly1gmnbi75ngkj30f00sz11s.jpg" /></p>
<p>【5】可不敢开这车去扫墓<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx4.sinaimg.cn/mw1024/00893JKXly1gmnais1e3ag30a00bc4qs.gif" /></p>
<p>【6】嘲讽满分了<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx4.sinaimg.cn/mw600/0035UptZly1gmn56q4jw9j60kb0kbjtr02.jpg" /></p>
<p>【7】正义在美色面前不值一提<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx3.sinaimg.cn/mw600/897c4370gy1gmn8l2yuapj20zk0qoqv5.jpg" /></p>
<p>【8】被自己吓蒙了<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx3.sinaimg.cn/mw1024/00893JKXly1gmn8deamwxg30aa055b29.gif" /></p>
<p>【9】时间的痕迹<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx1.sinaimg.cn/mw600/00893JKXly1gmn7w8mq6bj31400u01kx.jpg" /><br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx2.sinaimg.cn/mw600/00893JKXly1gmn7vzw2iej31400u0b1x.jpg" /></p>
<p>【10】压上全部狗粮的狗子<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx2.sinaimg.cn/mw1024/006ahuzrgy1gmmqwgo4jig309y0e1he8.gif" /></p>
<p>【11】学英语<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx3.sinaimg.cn/mw600/00893JKXly1gmnhronwwtj319o0jwb29.jpg" /></p>
<p>【12】不由自主的提了一下缸<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx3.sinaimg.cn/mw1024/00893JKXly1gmnezm3wm7g30730cinpe.gif" /></p>
<p>【13】士可杀不可辱<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx4.sinaimg.cn/mw1024/00893JKXly1gmnezegudwg304c07kx6p.gif" /></p>
<p>【14】肉棒进去，活猪出来<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx1.sinaimg.cn/mw600/00893JKXly1gmnet4y8fhj30g40o5jtl.jpg" /></p>
<p>【15】一家子被一个外姓人欺负<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx1.sinaimg.cn/mw1024/00893JKXly1gmndmcfcsxg304c06nu0z.gif" /></p>
<p>【16】说出来你可能不信 我被床缠上了<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx2.sinaimg.cn/mw1024/00893JKXly1gmn41azvc9g30b4089x6p.gif" /></p>
<p>【17】搜狗搜出来是狗，这很合理<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx1.sinaimg.cn/mw600/00893JKXly1gmn2q8ob7hj30f00mk0tc.jpg" /></p>
<p>【18】铁棍惊鸿起，蛋碎了无痕<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://ww1.sinaimg.cn/mw1024/538add77gy1gmn1203zj3g20a007i4qp.gif" /></p>
<p>【19】来，你要的再浪一点<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://ww1.sinaimg.cn/mw1024/538add77gy1gmn10rg3hcg205l05ub29.gif" /></p>
<p>【20】那个干部经得住这种考验<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx2.sinaimg.cn/mw1024/00893JKXly1gmmztksti7g30f40dee84.gif" /></p>
<p>【21】戒色吧阴谋<br />
<img alt="青年图摘0115！正义在美色面前不值一提" src="https://wx3.sinaimg.cn/mw600/00893JKXly1gmmz1oi5efj30u00y4416.jpg" /></p>
<!--kg-card-end: markdown-->

### [Daily Hacker News for 2021-01-14](https://www.daemonology.net/hn-daily/2021-01-14.html)

### [Angel在TI-ONE机器学习平台上的应用](https://www.infoq.cn/article/4R9hLPiiABCwzcEhVYsS)

### [#小Q分享# 《如何利用TensorFlow Hub 让BERT开发更简单？》在自然语言处理领域，BERT 和其他 Transformer 编码器架构都非常成功，无论是推进学术基准的技术水平...](https://weibo.com/1746173800/JDfpnjAKw)

### [【My personal wishlist for a decentralized social network】网页链接 我对去中心化社交网络的个人愿望清单。 网路冷眼技术分享 #科技暖心季# [图片]](https://weibo.com/1715118170/JDfpz9VPt)

### [【Beaker Browser – experimental peer to peer web browser】网页链接 Beaker 浏览器–实验性对等网络浏览器。网路冷眼技术分享 #科技暖心季# [图片]](https://weibo.com/1715118170/JDfdcirTn)

### [转发微博 - 转发 @网路冷眼:&ensp;#冷眼赠书福利# 转发赠书# 网路冷眼联合@华章图书 @华章计算机科学 送出 5 本《ECharts数据可视化》，截至 1 月 20 日，转发此...](https://weibo.com/1715118170/JDf76lfLV)

### [转发 - 转发 @网路冷眼:&ensp;【I received first-ever donation on my open-source side project and it felt great】网页链接 我在开源方面的项目中获得了首次...](https://weibo.com/1642628345/JDfiWnAtC)

### [派早报：三星发布 Galaxy S21 系列手机、蒸汽平台（Steam）即将登陆中国](https://sspai.com/post/64578)

### error read: https://rsshub.app/gov/ndrc/xwdt

### [拜登的经济团队将如何制定中国政策？](http://www.ftchinese.com/story/001091021)

### [达里奥：中国将争夺世界金融中心地位](http://www.ftchinese.com/story/001090967)

### [你们家小孩登记的农历还是国历？](https://www.v2ex.com/t/745047)

### [天天写脚本搭环境，该不该辞职](https://www.v2ex.com/t/744835)

### [混合基础设施下，服务网格（Service Mesh）如何对应用进行统一管理](https://www.infoq.cn/article/4Gr7CGucVKGhOvjoBgEI)

### [探索 Vue.js 响应式原理](https://segmentfault.com/a/1190000038921922)

### [《猫、爱因斯坦和密码学：我也能看懂的量子通信》今日开奖，欢迎参与～ - 转发 @爱可可-爱生活:&ensp;#抽奖##赠书#活动汇总，参与请转发原微博：《猫、爱因斯坦...](https://weibo.com/1402400261/JDfGmtJtj)

### [【Why We Disable Linux's THP Feature for Databases】网页链接 为什么我们禁用Linux的THP数据库功能。 [图片]](https://weibo.com/1715118170/JDgceDcvZ)

### [【75% of the original Disney+ executive team is no longer at Disney】网页链接 最初的迪士尼+执行团队中有75％不再在迪士尼工作。](https://weibo.com/1715118170/JDfNXttT7)

### [转发 - 转发 @歪思w4Wise:&ensp;一个super()挖出来的大量信息Python内核开发者的讲解[rhettinger (Raymond Hettinger)](网页链接)Google开发者 laike9m的解析[理...](https://weibo.com/1642628345/JDfZ4cHss)

### [怕了怕了 [图片]](https://weibo.com/1642628345/JDfNqnPUD)

### [科技爱好者周刊（第 142 期）：2020年才是21世纪元年](http://www.ruanyifeng.com/blog/2021/01/weekly-issue-142.html)

### error read: http://www.waerfa.com/feed

### [百炼智能完成1亿元A轮融资，深耕B2B营销自动化赛道](https://www.jiqizhixin.com/articles/2021-01-15-2)

 

### error read: http://www.waerfa.com/feed

### error read: http://www.13775.org/feed/

### error read: http://www.bigdatainterview.com/feed/

### error read: http://120.53.237.72:1200/segmentfault/channel/ai

### error read: http://www.jintiankansha.me/rss/GEYDCOBUPRRWGMDBGFSDIZTGMM2GCZRVMQZGGNRQHBRTQZLEME4TQYLFGJRDKZBTGI2TSZJUGM======

### error read: http://www.jintiankansha.me/rss/GEYDCNRWPQ2TIZJWGJQTINLEMUYGGNRXMVRDSNZSG4ZDMNJQMU4WEMBZGAYTMMZQMEZGCMZZGE======

### [1月15日新闻茶泡Fan](https://www.cfan.com.cn/2021/0115/134758.shtml)

### [【How the Canadian Tech Scene Encourages Finite Gameplay】网页链接 加拿大科技界如何鼓励有限的游戏玩法？](https://weibo.com/1715118170/JDgACpKKF)

### [//@吴潍浠:有道理 - 转发 @传播学考研就找瓦洛佳:&ensp;【为什么我觉得 #乌合之众# 可能是本坏书】传播学，乃至社会圈的“破圈”，如今是越来越多了。昨天，一本...](https://weibo.com/1642628345/JDgl34ECY)

### [年度征文｜聊聊我在美国如何领养一只汪星人](https://sspai.com/post/64527)

### [6 – Android 手机史上最 6 的应用](https://www.appinn.com/6-six-app-for-android/)

 <p>6 是一款非常 6 的应用，堪称 Android 手机史上最 6 的应用，它唯一的功能，就是在手机屏幕上展示一个数字 6，点击屏幕还能更换不同的颜色，真是太 666 了。@<a class="rank-math-link" href="https://www.appinn.com/6-six-app-for-android/">Appinn</a></p>



<div class="wp-block-image"><figure class="aligncenter size-large"><img alt="6 - Android 手机史上最 6 的应用" src="https://img3.appinn.net/images/202101/666.jpg!o" title="6 - Android 手机史上最 6 的应用 1" /></figure></div>



<p>第一次打开 6，青小蛙忍不住笑，不知道为什么，点了几次又在大笑，开心，就是 6。</p>



<p>怎么说，青小蛙也算是见识过成百上千 App 的用户，在看了 6 之后，还是觉得 6，真是 6。</p>



<h2>Android 手机史上最 6 的应用</h2>



<p>是的，你能找到比 6 还 6 的应用么？</p>



<p>来看动画演示 <img alt="🙈" class="wp-smiley" src="https://s.w.org/images/core/emoji/13.0.1/72x72/1f648.png" style="height: 1em;" /></p>



<div class="wp-block-image"><figure class="aligncenter size-large is-resized"><img alt="Android 手机史上最 6 的应用" height="-449" src="https://img3.appinn.net/images/202101/666-appinn.gif!o" title="6 - Android 手机史上最 6 的应用 2" width="-231" /></figure></div>



<p>打开 6 之后，就显示 6 在屏幕上，点击屏幕可以更换颜色，就没有其他功能了，很 6。</p>



<p>开发者也是实在，在应用介绍中写着：</p>



<p>这款应用将为你提供比以往更多的快乐。你将被数字 6 的纯洁本质所激励，并再一次重温你最喜欢的时刻，因为你欢欣鼓舞，得到更多的灵感。6.</p>



<p>啊，青小蛙完全被 6 感染了，请前往 <a class="rank-math-link" href="https://play.google.com/store/apps/details?id=six.six" rel="noopener" target="_blank">Google Play</a> 免费安装，无法访问 Play 商店的同学可点击下面的按钮前往网盘搬运：</p>



<div align="center"><a href="https://d.appinn.com/6-six-app-for-android/" rel="noopener" target="view_window"><img alt="6 - Android 手机史上最 6 的应用 1" src="https://img3.appinn.net/images/201507/down.png" title="6 - Android 手机史上最 6 的应用 3" /></a></div>
<hr /><h2>相关阅读</h2><ul><li><a href="https://www.appinn.com/six-for-ios/" rel="bookmark" title="Permanent Link: Six! &#8211; 爱消除和爱平衡合体了[iPad/iPhone]">Six! &#8211; 爱消除和爱平衡合体了[iPad/iPhone]</a></li><li><a href="https://www.appinn.com/leo-share-apps-ios/" rel="bookmark" title="Permanent Link: @Leo&#038; : 自用精品 App 整理与推荐 iOS 版">@Leo&#038; : 自用精品 App 整理与推荐 iOS 版</a></li><li><a href="https://www.appinn.com/six-accountbook/" rel="bookmark" title="Permanent Link: 纯记账 &#8211; 一款 Android 上的「纯记账」应用">纯记账 &#8211; 一款 Android 上的「纯记账」应用</a></li><li><a href="https://www.appinn.com/the-iphone-storage-almost-full/" rel="bookmark" title="Permanent Link: iPhone 容量不足的时候，还能这样！">iPhone 容量不足的时候，还能这样！</a></li><li><a href="https://www.appinn.com/sfufoet-ios-apps/" rel="bookmark" title="Permanent Link: 应网易应用的邀请，推荐一些小众的 iOS apps">应网易应用的邀请，推荐一些小众的 iOS apps</a></li></ul><hr />
<a href="http://www.appinn.com/copyright/?utm_source=feeds&amp;utm_medium=copyright&amp;utm_campaign=feeds" title="版权声明">&#169;</a>2019 青小蛙 for <a href="http://www.appinn.com/?utm_source=feeds&amp;utm_medium=appinn&amp;utm_campaign=feeds" title="本文来自小众软件">小众软件</a> | <a href="http://www.appinn.com/join-us/?utm_source=feeds&amp;utm_medium=joinus&amp;utm_campaign=feeds" title="加入小众软件">加入我们</a> | <a href="https://meta.appinn.com/c/faxian/?utm_source=feeds&amp;utm_medium=contribute&amp;utm_campaign=feeds" rel="noopener" target="_blank" title="给小众软件投稿">投稿</a> | <a href="http://www.appinn.com/feeds-subscribe/?utm_source=feeds&amp;utm_medium=feedsubscribe&amp;utm_campaign=feeds" target="_blank" title="可以分类订阅小众，Windows/MAC/游戏"><font color="red">订阅指南</font></a><br /> 3659b075e72a5b7b1b87ea74aa7932ff <br />
<a href="https://www.appinn.com/6-six-app-for-android/#comments" title="to the comments">点击这里留言、和原作者一起评论</a>

### [2020年房价涨幅榜出炉：43城房价上涨，深圳领先，你家房子是涨还是跌？](https://m.21jingji.com/article/20210115/herald/96103ba14c6dba013fa45f216779cd8b.html)

### [碰到有人克隆自己博客该怎么办？](https://www.v2ex.com/t/745097)

### [955 也没法 WLB](https://www.v2ex.com/t/745039)

### [各位大佬，请教一下如何在断网的环境下同步代码？](https://www.v2ex.com/t/745005)

### [某男子研发上传“健康码演示”App 被抓获](https://linux.cn/article-13017-1.html?utm_source=rss&utm_medium=rss)

### [恭喜@李X萌LYM 1名用户获得【华为FreeBuds Pro真无线蓝牙耳机】。微博官方唯一抽奖工具@微博抽奖平台 -高级版对本次抽奖进行监督，结果公正有效。公示链接：微博...](https://weibo.com/1746173800/JDh0Qua16)

### [A16Z 合伙人 Peter：开源，从社区到商业化](https://segmentfault.com/a/1190000038990512)

### [几篇论文实现代码：《Imvotenet: Boosting 3d object detection in point clouds with image votes》(CVPR 2020) GitHub:网页链接 [fig1]《A Multi-task Learnin...](https://weibo.com/1402400261/JDhiZcaM4)

### [恭喜@要继续照顾着历代星辰 等3名用户获得【《猫、爱因斯坦和密码学》】。微博官方唯一抽奖工具@微博抽奖平台 对本次抽奖进行监督，结果公正有效。公示链接：微...](https://weibo.com/1402400261/JDgZEld7k)

### [【Signal Fork with WhatsApp Migration】网页链接 带WhatsApp迁移的Signal 分支。 [图片]](https://weibo.com/1715118170/JDhns2AG9)

### error read: http://www.waerfa.com/feed

### error read: https://sspai.com/feed

### error read: http://www.waerfa.com/feed

### error read: http://www.jintiankansha.me/rss/GE2DK7BQMI2DKYLDGM2DMMBVMY3WKY3FMQ4TMY3FME4DOOJQGBSWCNLDMZRTEYLGGBRTGZQ=

### error read: http://www.jintiankansha.me/rss/GEYDCOBUPRRWGMDBGFSDIZTGMM2GCZRVMQZGGNRQHBRTQZLEME4TQYLFGJRDKZBTGI2TSZJUGM======

### [这么多茅台是卖给谁了](https://www.v2ex.com/t/745122)

### [可以说非常的焦虑了，求解决方案](https://www.v2ex.com/t/744971)

### [Twitter永久性的夹了Sci-Hub的“官方”帐户](http://jandan.net/p/108351)

### [请教一个rust调用C动态库含C结构体的问题](https://rustcc.cn/article?id=e09fe057-2caa-483b-b72c-baca380ce9e5)

### [高达200个应用，近8000个实例的工行MySQL转型实践](https://www.infoq.cn/article/EQRMLltiKaEfGKSXTtkE)

### [美籍华人MIT教授陈刚被捕：或面临最高20年监禁](https://www.infoq.cn/article/zBOvrsegmsDuQOcYJgPW)

### [【Messenger Comparisons – Threema, Signal, Telegram and WhatsApp】网页链接 Threema，Signal，Telegram和WhatsApp等4个Messenger比较。 [图片]](https://weibo.com/1715118170/JDhLLClFP)

### error read: http://www.waerfa.com/feed

### error read: https://sspai.com/feed

### error read: http://www.waerfa.com/feed

### error read: https://szpzs.oschina.io/atom.xml

### error read: http://120.53.237.72:1200/zhihu/zhuanlan/chicken-life

### error read: http://www.bigdatainterview.com/feed/

### [不知道蓄水池抽样算法？那就进来看看吧~](https://segmentfault.com/a/1190000038991899)

### error read: http://www.jintiankansha.me/rss/GEYDCOBUPRRWGMDBGFSDIZTGMM2GCZRVMQZGGNRQHBRTQZLEME4TQYLFGJRDKZBTGI2TSZJUGM======

### error read: http://www.jintiankansha.me/rss/GEYDCNRWPQ2TIZJWGJQTINLEMUYGGNRXMVRDSNZSG4ZDMNJQMU4WEMBZGAYTMMZQMEZGCMZZGE======

### error read: https://rsshub.app/telegram/channel/tgchinanews

### [对三星 s21 系列的评价](https://www.v2ex.com/t/745099)

### [注销卸载淘宝支付宝后能请阿里公司在数据库中删除用户信息吗？](https://www.v2ex.com/t/745092)

### error read: https://rust.cc/rss

### [#冷眼赠书福利# 联合 @博文视点Broadview 送出5本《技术人修炼之道：从程序员到百万高管的72项技能》。截止 1 月 22 日，转发此微博并关注 @网路冷眼 赢取。全方...](https://weibo.com/1715118170/JDi8Hd59o)

### [TWS 降噪耳机「跳级生」：声阔 Liberty Air 2 Pro 让我手上的 AirPods Pro 不香了](https://sspai.com/post/64566)

### [买了随心飞 N 个月，这是我们的体验报告](https://sspai.com/post/64582)

### error read: http://www.waerfa.com/feed

### error read: http://www.jintiankansha.me/rss/GE2DK7BQMI2DKYLDGM2DMMBVMY3WKY3FMQ4TMY3FME4DOOJQGBSWCNLDMZRTEYLGGBRTGZQ=

### error read: http://www.jintiankansha.me/rss/GEYDCOBUPRRWGMDBGFSDIZTGMM2GCZRVMQZGGNRQHBRTQZLEME4TQYLFGJRDKZBTGI2TSZJUGM======

### [迫于公司要钉钉打卡，请问有啥办法虚拟定位钉钉打卡吗？手机已 root](https://www.v2ex.com/t/745189)

### [👂🏻：晚上回小区，有个男人骑电瓶车载着儿子路过一位环卫工，小孩问：“为什么老人家要做这些啊？”](https://weibo.com/2816125940/JDiyX57dW)

### [👂🏻：校园里，边上路过两个女生，听到其中一个惊讶地说：“我们小时候都是看奥特曼的正义，你怎么小时候就看他身材哇！”](https://weibo.com/2816125940/JDiwlczBj)

### [👂🏻：午休时两个男同事在聊天，其中一个说：“我也想要有一个好的皮囊，让人看到我都流口水。”](https://weibo.com/2816125940/JDivltc3Y)

### [👂🏻：牙科治疗室，一个五六十岁的男人躺在诊位上，叹了口气。“唉，我太不勇敢了。”](https://weibo.com/2816125940/JDiuYEAmC)

### [👂🏻：我们酒吧是拉吧，对面刚巧是钙吧，等电梯时听到两个Gay的讨论：“刚刚那个T真的好帅啊！”](https://weibo.com/2816125940/JDiur1WAI)

### [【要建立“中国版 GitHub”吗？】点击观看：网页链接 微软推出GitHub暗黑模式，引发程序员热议，那么要不要建立一个中国的“GitHub”？开源界领袖级人物对此什么...](https://weibo.com/1746173800/JDiyd2Clo)

### error read: http://www.waerfa.com/feed

### [2020-2021「AI中国」机器之心人工智能年度奖项揭榜：大浪淘沙，数智突围](https://www.jiqizhixin.com/articles/2021-01-15-8)

 

### [任期只剩6天，特朗普政府将小米等9家中企列入投资黑名单](https://www.jiqizhixin.com/articles/2021-01-15-5)

 

### [多核之后，CPU 的发展方向是什么？中科院计算所包云岗详细解读](https://www.jiqizhixin.com/articles/2021-01-15-6)

 

### [年度十大资本事件揭晓，机器之心&IT桔子带你预见创新与投资趋势](https://www.jiqizhixin.com/articles/2021-01-15-7)

 

### [线上直播丨倒计时一天！一起来CSIG-机器感知与智能论坛交流学术内容](https://www.jiqizhixin.com/articles/2021-01-15-4)

 

### [AAAI 2021线上分享 | 强化学习与3D视觉结合新突破，国防科大实现高效能无序混合码垛机器人](https://www.jiqizhixin.com/articles/2021-01-15-3)

 

### [入网指南 04 | IP 地址大揭秘](https://sspai.com/post/64430)

### [安装 Ubuntu 20.10，高性能计算和 3D 视觉呈现第一步 - 京山游侠](http://www.cnblogs.com/youxia/p/cg001.html)

 【摘要】前言 之前我花了很长一段时间折腾 Linux，略有所得。在 2021 年新年伊始之际，我给自己弄了一台 4K 屏的 Dell XPS 9570，总算满足了自己有钱了一定弄一台 4K 屏笔记本电脑的心愿，也进一步验证了我之前说过的只要屏幕分辨率够高字体渲染就不是事儿的说法。总之，这一年的开局我还是很满 <a href="http://www.cnblogs.com/youxia/p/cg001.html" target="_blank">阅读全文</a>

### error read: http://www.bigdatainterview.com/feed/

### [上海降低落户政策， 一大波人开始抢房。](https://www.v2ex.com/t/745145)

### [发霉啦：今天，真特么是混乱的一天](http://jandan.net/p/108354)

### [量子小计算机能算调度优化小问题了](http://jandan.net/p/108353)

### [如何打破音乐软件的反馈循环来发现新音乐](http://jandan.net/p/108352)

### [Rosetta 2：从x86到ARM64](https://www.infoq.cn/article/0P8vk9FfCi3dV3bFHHhr)

### [一文解析DDD中台和微服务设计](https://www.infoq.cn/article/cc8ab87bda888d0dfa686fc91)

### [Kubernetes概念篇：基本概念和术语](https://www.infoq.cn/article/4ce0d6a1a0d00d5760aa53279)

### [华仔的架构专栏订阅突破 50000 了，好内容必须支持～ - 转发 @池建强:&ensp;前阿里 P9 李运华《从0开始学架构》专栏，订阅破 50000 。 华仔从架构基础、三大架构...](https://weibo.com/1746173800/JDiVVns7O)

### [投票：以下哪位不是“古代四大美女”？[憧憬]#投票# 以下哪位不是“古代四大美女”？](https://weibo.com/1715118170/JDiY96DZE)

### [#绿洲摄影#IT图腾 中关村的标致性建筑——生命，DNA的双螺旋结构。 绿洲 [图片]](https://weibo.com/1715118170/JDiVEfcv7)

### [给每个人的 Linux 桌面入门指南（二）—— 适合大众使用的 Linux 桌面发行版](https://sspai.com/post/64545)

### error read: http://www.waerfa.com/feed

### error read: https://szpzs.oschina.io/atom.xml

### [2021年1月15日24时起国内成品油价格按机制上调](https://www.ndrc.gov.cn/xwdt/xwfb/202101/t20210115_1264991.html)

### error read: http://www.bigdatainterview.com/feed/

### [Is the amount of GPU on each machine expected to be identical when multi-machine multi-gpu training using distributed.launch ?](https://www.reddit.com/r/pytorch/comments/kxr2cr/is_the_amount_of_gpu_on_each_machine_expected_to/)

 <!-- SC_OFF --><div class="md"><p>I have 8 GPUs on machine 1 and 4 GPUs on machine 2, and I'd like to perform multi-gpu training on all 12 GPUs. </p> <p>Is it ok to train on 8 GPUs and 4 GPUs in two machines, despite using the different amount of GPUs on each one?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AlphaGoMK"> /u/AlphaGoMK </a> <br /> <span><a href="https://www.reddit.com/r/pytorch/comments/kxr2cr/is_the_amount_of_gpu_on_each_machine_expected_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/pytorch/comments/kxr2cr/is_the_amount_of_gpu_on_each_machine_expected_to/">[comments]</a></span>

### [真·睡后收入， 5700 挖 ETH 记录](https://www.v2ex.com/t/745211)

### [上周才买了宇宙最强的电视盒子，这次分享最强电视盒子配套的影视软件](https://www.v2ex.com/t/745166)

### [【已询问】北京中科晶上科技股份有限公司](http://kcb.sse.com.cn//renewal/xmxq/index.shtml?auditId=744)

### [【已询问】昆山国力电子科技股份有限公司](http://kcb.sse.com.cn//renewal/xmxq/index.shtml?auditId=780)

### [【已询问】武汉珈创生物技术股份有限公司](http://kcb.sse.com.cn//renewal/xmxq/index.shtml?auditId=805)

### [事不大侮辱性极强：微软、思科等企业源代码被黑客在线售卖，打包价100万美元](https://www.infoq.cn/article/X2qA9h4B7m07rYmyYuDs)

### [Aleph.js发布Alpha版，一个基于Deno的服务器端渲染框架](https://www.infoq.cn/article/sb3y957HD0hAc7V1lHHD)

### [发布了头条文章：《微软和谷歌的 AI 模型在 SuperGLUE 语言基准上超越了人类的表现》  微软和谷歌的 AI 模型在 SuperGLUE 语言基准上超越了人类的表现](https://weibo.com/1746173800/JDjkYen30)

### [“先做到，再做对，再做好” - Addy Osmani](https://weibo.com/1402400261/JDj8ntysO)

### [本周看什么 | 最近值得一看的 9 部作品](https://sspai.com/post/64590)

### error read: https://szpzs.oschina.io/atom.xml

### [BIGO六年，全球破圈](http://www.jintiankansha.me/t/zNd3bFx10Y)

### [芯片真的不够用了，全球性的！](http://www.jintiankansha.me/t/36BL4eI3FG)

### [美联储褐皮书的惊人发现：几乎所有行业都在涨价](http://www.jintiankansha.me/t/UdsiZnQcxm)

### [1.9万亿美元！拜登“美国拯救计划”对市场意味着什么？](http://www.jintiankansha.me/t/YHK0FNbkOR)

### [“年轻人不喝白酒”在中国不成立！王永锋对话徐猛：短期调整可能是买点](http://www.jintiankansha.me/t/L7x5nUWKgU)

### error read: http://www.jintiankansha.me/rss/GEYDCOBUPRRWGMDBGFSDIZTGMM2GCZRVMQZGGNRQHBRTQZLEME4TQYLFGJRDKZBTGI2TSZJUGM======

### [1、2020年外贸32.16万亿元 再创新高动力强2、我国东部地区2021年底实现快递直投到村3、美国总统拜登公布了经济刺激计划，规模达1.9万亿美元4、率先披露年度业绩...](https://t.me/tgchinanews/922)

### [📹Fri, 15 Jan 2021 10:29:20 GMT](https://t.me/tgchinanews/921)

### [【已询问】新疆大全新能源股份有限公司](http://kcb.sse.com.cn//renewal/xmxq/index.shtml?auditId=710)

### [【喷嚏图卦20210115】大连车务段人人都是高手](https://www.dapenti.com/blog/more.asp?name=xilei&id=154389)

### [跟着哪种导师成长更快？[笑而不语] [图片]](https://weibo.com/1402400261/JDjP8DQTN)

### error read: http://www.waerfa.com/feed

### error read: https://sspai.com/feed

### error read: http://www.waerfa.com/feed

### error read: http://120.53.237.72:1200/zhihu/zhuanlan/paperweekly

### error read: http://www.bigdatainterview.com/feed/

### [如何为基于NLP的实体识别模型设置人工审查？](https://segmentfault.com/a/1190000038995796)

### error read: http://www.jintiankansha.me/rss/GE2DK7BQMI2DKYLDGM2DMMBVMY3WKY3FMQ4TMY3FME4DOOJQGBSWCNLDMZRTEYLGGBRTGZQ=

### error read: http://www.jintiankansha.me/rss/GEYDCOBUPRRWGMDBGFSDIZTGMM2GCZRVMQZGGNRQHBRTQZLEME4TQYLFGJRDKZBTGI2TSZJUGM======

### [【Rust日报】2021-01-15](https://rustcc.cn/article?id=28f1d055-0fe1-4f6f-b557-65059f95fd27)

### [熟悉tokio的tracing的帮忙解答个问题](https://rustcc.cn/article?id=2256fd19-016e-4b1a-8c05-f868be7d28ec)

### [蚂蚁集团招聘 Rust 技术专家](https://rustcc.cn/article?id=1e2ffcdf-33ef-46fd-8d69-1908fcc6be9b)

### [有点可爱 ❤️ via:Chelsea Parlett-Pelleriti [图片][图片]](https://weibo.com/1402400261/JDk4SEsiV)

### [【Leaked memos Amazon warn 'be vigilant' due to threats to blow up data centers】网页链接 泄露的备忘录显示，由于帕勒禁令后极右势力威胁炸毁数据中心，亚...](https://weibo.com/1715118170/JDk7P0Yzt)

### error read: http://www.waerfa.com/feed

### error read: https://rsshub.app/gov/ndrc/xwdt

### error read: http://120.53.237.72:1200/zhihu/zhuanlan/chicken-life

### error read: http://120.53.237.72:1200/zhihu/zhuanlan/yuandong

### [【已询问】上海南方模式生物科技股份有限公司](http://kcb.sse.com.cn//renewal/xmxq/index.shtml?auditId=801)

### error read: http://120.53.237.72:1200/cfan/news

### [#小Q分享# 《配置语言的黄金时代》我认为我们当前所认知的 DevOps 即将走到尽头。至少，其中的 Ops 会如此。随着云基础设施成为应用程序关注的重点，越来越多的 ...](https://weibo.com/1746173800/JDkvYxZnx)

### [数学家：0!=1计算机科学家：0!=1via:Benjamin Dickman](https://weibo.com/1402400261/JDkcyqd0F)

### error read: http://120.53.237.72:1200/manong-weekly

### [转发微博 - 转发 @网路冷眼:&ensp;#冷眼赠书福利# 联合 @博文视点Broadview 送出5本《技术人修炼之道：从程序员到百万高管的72项技能》。截止 1 月 22 日，转发...](https://weibo.com/1715118170/JDkC4agmx)

### [【Molly for Android: A fork of Signal for Android with passphrase lock】网页链接 Molly for Android: 具有密码短语锁定的Signal for Android 的克隆。 [图...](https://weibo.com/1715118170/JDkw1dEYz)

### [【Vantage – An alternative AWS console focused on developer experience】网页链接 Vantage–一款专注于开发人员体验的AWS控制台替代品。 网路冷眼技术分享 ...](https://weibo.com/1715118170/JDkjNBdTg)

### error read: https://jiqizhixin.com/rss

### error read: http://120.53.237.72:1200/zhihu/zhuanlan/chicken-life

### [2021年1月15日新闻联播文字版](http://www.xwlb.net.cn/17537.html)

### [阿里云消息中间件RocketMQ招人](https://rustcc.cn/article?id=2772c148-f43d-410b-aa10-1ca7fb911c36)

### [#小Q分享# 《DeepMind的年度报告：亏损42亿再创新高，收益仰赖谷歌母公司》本文是我们探索人工智能商业系列的一部分上周，DeepMind 在利用人工智能预测蛋白质折...](https://weibo.com/1746173800/JDkUkszzy)

### [晚安～ [月亮] #晚安# [图片][图片][图片][图片]](https://weibo.com/1402400261/JDl0ceRR4)

### [《爱可可老师24小时热门分享(2021.1.15)》  爱可可老师24小时热门分享(2021.1.15)](https://weibo.com/1402400261/JDkZstWk4)

### [【I received first-ever donation on my open-source side project and it felt great】网页链接 我在开源方面的项目中获得了首次捐款，感觉很棒。 [图片]](https://weibo.com/1715118170/JDkUEy619)

### [转发微博 - 转发 @网路冷眼:&ensp;#冷眼赠书福利# 转发赠书# 网路冷眼联合@华章图书 @华章计算机科学 送出 5 本《ECharts数据可视化》，截至 1 月 20 日，转发此...](https://weibo.com/1715118170/JDkOeyF7B)

### [【An amendment to the Constitution of the USA to abolish the electoral college】网页链接  废除选举团的美国宪法修正案 。 [图片]](https://weibo.com/1715118170/JDkI9vODa)

### error read: https://sspai.com/feed

### error read: http://120.53.237.72:1200/zhihu/zhuanlan/chicken-life

### error read: http://www.bigdatainterview.com/feed/

### [The right way to make custom losses](https://www.reddit.com/r/pytorch/comments/kxw9y0/the_right_way_to_make_custom_losses/)

 <!-- SC_OFF --><div class="md"><p>I noticed that a few codes make their custom losses just as a method while some make an inherited class of nn.Module and define its forward and backward methods. </p> <p>What's the right way to do it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/banenvy"> /u/banenvy </a> <br /> <span><a href="https://www.reddit.com/r/pytorch/comments/kxw9y0/the_right_way_to_make_custom_losses/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/pytorch/comments/kxw9y0/the_right_way_to_make_custom_losses/">[comments]</a></span>

### [目前新冠疫苗可以接种么 有接种的 v 友能说说状态怎么样么](https://www.v2ex.com/t/745236)

### [20 来万怎么理财？](https://www.v2ex.com/t/745116)

### [【未通过】上海电气风电集团股份有限公司](http://kcb.sse.com.cn//renewal/xmxq/index.shtml?auditId=588)

### [【未通过】杭州柯林电气股份有限公司](http://kcb.sse.com.cn//renewal/xmxq/index.shtml?auditId=564)

### [【未通过】杭州西力智能科技股份有限公司](http://kcb.sse.com.cn//renewal/xmxq/index.shtml?auditId=466)

### [【未通过】苏州和林微纳科技股份有限公司](http://kcb.sse.com.cn//renewal/xmxq/index.shtml?auditId=504)

### [2021年1月15日外交部发言人赵立坚主持例行记者会(2021-01-15)](https://www.fmprc.gov.cn/web/wjdt_674879/fyrbt_674889/t1846668.shtml)

### error read: http://www.qingniantuzhai.com/feed

### error read: http://www.cppblog.com/rss.aspx

### error read: http://120.53.237.72:1200/weibo/user/5722964389

### error read: http://120.53.237.72:1200/weibo/user/1715118170

### error read: http://www.waerfa.com/feed