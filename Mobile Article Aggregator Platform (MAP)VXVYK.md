<h1> Mobile Article Aggregator Platform (MAP)</h1><br><br><hr><br>

Mobile Article Aggregator Platform 是一个面向移动端内容聚合与分发场景的开源技术资源导航站。该项目定位于为开发者、技术研究人员以及内容运营团队提供结构化的移动端文章链接索引与快速检索能力，解决移动端技术文章分散、检索效率低下、域名迁移频繁导致链接失效等实际问题。

项目本身不存储任何文章内容，仅作为外链元数据的索引层与展示层，通过静态化的资源列表与分类标签体系，帮助用户在海量移动端技术文档中快速定位目标资源。目标用户包括移动端开发工程师、全栈技术学习者、技术博客维护者以及企业内部知识库管理人员。

<h2>功能概览</h2><br>

<p><h3>海量链接索引管理</h3>：支持对超过 250 条移动端技术文章链接进行集中存储与分类展示，覆盖多种技术子领域。</p>

<p><h3>静态化资源列表呈现</h3>：所有链接以纯 Markdown 形式维护于项目仓库中，无需数据库依赖，便于版本控制与协作编辑。</p>

<p><h3>分类标签体系</h3>：根据文章主题、技术栈或访问热度对链接进行逻辑分组，降低用户筛选成本。</p>

<p><h3>快速检索入口</h3>：提供基于文章 ID 或路径关键字的本地搜索功能，提升链接定位速度。</p>

<p><h3>链接状态检测工具</h3>：集成可选的定时检测脚本，自动标记可能失效或响应异常的链接，保障资源列表的有效性。</p>

<p><h3>移动端适配展示</h3>：前端模板针对手机和平板设备进行优化，确保在移动浏览器上获得良好的阅读与导航体验。</p>

<p><h3>开源协作扩展机制</h3>：支持社区用户通过提交 Issue 或 Pull Request 的方式新增、更新或删除链接条目，保持资源列表的时效性。</p>

<p><h3>轻量化部署能力</h3>：项目整体基于静态文件生成，可托管于任何支持 HTTP 服务的平台，包括 GitHub Pages、Cloudflare Pages 或自建 Nginx 服务器。</p>

<h2>应用场景</h2><br>

技术团队内部知识库建设：企业内部的技术团队可将本项目作为基础框架，整理团队内部积累的移动端技术文章链接，形成统一的知识索引入口，减少重复的文档查找工作。

个人技术博客的友情链接扩展：独立技术博客作者可利用本项目的资源列表作为博客侧边栏的补充，为读者提供更多外部阅读资源，同时降低博客维护外链的复杂度。

技术社区的内容聚合展示：技术社区运营方可基于本项目快速搭建文章推荐专区，将社区内的高质量技术帖按分类进行外链汇总，提升社区内容的曝光率与复用率。

技术培训课程的参考资料索引：培训机构或技术讲师可将本项目作为课程参考资料库，将课程中涉及的外部延伸阅读链接统一整理到项目列表中，方便学员课后查阅。

开源项目文档的关联资源导航：开源项目维护者可在项目文档中引用本项目的资源列表，为使用者提供相关的技术背景阅读材料，丰富项目的辅助信息生态。

<h2>快速开始</h2><br>

以下步骤将帮助您在本地环境快速部署并运行本项目的静态站点。

# 1. 克隆项目仓库到本地
git clone https://github.com/example/mobile-article-aggregator.git
cd mobile-article-aggregator

# 2. 安装项目依赖（基于 Node.js 环境）
npm install

# 3. 运行本地开发服务器，默认监听端口 3000
npm run dev

执行上述命令后，在浏览器中访问 `http://localhost:3000` 即可查看资源列表页面。如需构建生产环境静态文件，请执行 `npm run build`，生成的静态资源位于 `dist` 目录下。

<h2>安装要求</h2><br>

| 依赖项 | 必需版本 | 说明 |
|--------|----------|------|
| Node.js | 18.0 及以上 | 项目构建工具与开发服务器运行环境 |
| npm | 8.0 及以上 | Node.js 包管理器，用于安装项目依赖 |
| Git | 2.30 及以上 | 用于克隆仓库与版本管理 |
| 现代浏览器 | Chrome 90+ / Firefox 88+ | 前端页面访问与调试支持 |
| HTTP 服务器 | 任意静态文件服务 | 生产环境托管构建后的静态文件，如 Nginx、Caddy 或 Apache |
| 可选：Shell 环境 | Bash 4.0+ | 运行链接状态检测脚本（位于 scripts/ 目录） |

<h2>文档导航</h2><br>

| 层面 | 目录 | 回答的问题 |
|------|------|------------|
| 用户入门 | docs/getting-started.md | 如何使用本项目的资源列表？如何通过分类标签快速找到所需文章？ |
| 维护者指南 | docs/maintenance.md | 如何新增、修改或删除链接条目？链接格式校验规则是什么？ |
| 开发贡献 | docs/contributing.md | 如何搭建开发环境？代码风格规范与提交信息格式要求有哪些？ |
| 部署运维 | docs/deployment.md | 如何将站点部署到生产服务器？如何配置自定义域名与 HTTPS？ |

<h2>资源列表</h2><br>

<h3>移动端技术文章链接汇总</h3><br>

以下列表收录了本批次（第 8/24 批，共300 个资源链接）的全部移动端文章外链。所有链接均按照用户提供的原始格式原样呈现，未做任何协议、域名或路径的改动。

gitlab.com/GSEGERSGH/bbynuiq/-/blob/main/2026%E7%AC%AC%E4%B8%80%E8%B5%B0%E5%90%91%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BB%A3%E7%90%86%E5%87%BA%E7%A7%9F-%E5%BD%92%E5%AE%9E%E8%B4%A2%E7%BB%8F.md
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d6cda316d0b11111c1742dadff1d3e646bf9abaa
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/blob/main/2026%E7%AC%AC%E4%B8%80%E8%B5%B0%E5%90%91%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BB%A3%E7%90%86%E5%87%BA%E7%A7%9F-%E5%BD%92%E5%AE%9E%E8%B4%A2%E7%BB%8F.md?/197=755
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d6cda316d0b11111c1742dadff1d3e646bf9abaa?/Ui=82q
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/blob/main/2026%E7%AC%AC%E4%B8%80%E8%B5%B0%E5%90%91%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BB%A3%E7%90%86%E5%87%BA%E7%A7%9F-%E5%BD%92%E5%AE%9E%E8%B4%A2%E7%BB%8F.md?/xhB
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d6cda316d0b11111c1742dadff1d3e646bf9abaa?/f9d
<br>
gitlab.com/JHEJHR/auhkgvk/-/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%91%E6%8A%80%E7%83%AD%E7%82%B9%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0%E4%BB%A3%E7%90%86%E5%87%BA%E7%A7%9F-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4%E6%9D%BF%E5%9D%97.md
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1e88f59118a3f565380674223a6fae7dc2dbd470
<br>
gitlab.com/JHEJHR/auhkgvk/-/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%91%E6%8A%80%E7%83%AD%E7%82%B9%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0%E4%BB%A3%E7%90%86%E5%87%BA%E7%A7%9F-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4%E6%9D%BF%E5%9D%97.md?/532=196
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1e88f59118a3f565380674223a6fae7dc2dbd470?/sC=NEy
<br>
gitlab.com/JHEJHR/auhkgvk/-/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%91%E6%8A%80%E7%83%AD%E7%82%B9%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0%E4%BB%A3%E7%90%86%E5%87%BA%E7%A7%9F-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4%E6%9D%BF%E5%9D%97.md?/SwQ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1e88f59118a3f565380674223a6fae7dc2dbd470?/uOs
<br>
gitlab.com/JDJTY/txiqmhb/-/blob/main/2026%E5%AE%98%E6%96%B9%E5%BF%AB%E6%96%B0%E7%AB%A0:%E7%9A%87%E5%86%A0%E7%99%BB3%E5%87%BA%E7%A7%9F-%E6%B2%85%E6%B8%9A%E8%B4%A2%E7%BB%8F.md?/cQX
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/73e4c9e30dc4d888637cf539bf07aefb9ce8c7c6?/4Y2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8304cfbbf259d3f3e31cd4131d61706ee0b5be2d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8304cfbbf259d3f3e31cd4131d61706ee0b5be2d?/Ye=sMJ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8304cfbbf259d3f3e31cd4131d61706ee0b5be2d?/pJn
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/afad413869a0126cbfd138ccb6c6bc9f9c71ed6f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/afad413869a0126cbfd138ccb6c6bc9f9c71ed6f?/O1=pTk
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/afad413869a0126cbfd138ccb6c6bc9f9c71ed6f?/6a4
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e5065c66fd375810ffa33a388ecf91088a081f4b
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e5065c66fd375810ffa33a388ecf91088a081f4b?/K8=FW4
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e5065c66fd375810ffa33a388ecf91088a081f4b?/tNr
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e9bfd249da88c8c2e91a589c6beca49e16cbd131
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e9bfd249da88c8c2e91a589c6beca49e16cbd131?/7v=2Jq
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e9bfd249da88c8c2e91a589c6beca49e16cbd131?/CgA
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0f7803bd03fc1adcf3ec8ea587b2af4d3639d75b
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0f7803bd03fc1adcf3ec8ea587b2af4d3639d75b?/2W=Tul
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0f7803bd03fc1adcf3ec8ea587b2af4d3639d75b?/xRv
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/35223dbc82a28aeeff5ee1e2590619eb65817f3f
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/35223dbc82a28aeeff5ee1e2590619eb65817f3f?/KL=szD
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/35223dbc82a28aeeff5ee1e2590619eb65817f3f?/Cg9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/81c3a4ca615d51f8a0c14d482d89c361958dfca7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/81c3a4ca615d51f8a0c14d482d89c361958dfca7?/xo=2zQ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/81c3a4ca615d51f8a0c14d482d89c361958dfca7?/zTw
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5b9035176566538d184e913977441c7faa974a17
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5b9035176566538d184e913977441c7faa974a17?/mC=3Gh
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5b9035176566538d184e913977441c7faa974a17?/GkD
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ece7d92e7e458c91b29700bcc1184f71f6a6db84
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ece7d92e7e458c91b29700bcc1184f71f6a6db84?/ca=XRl
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ece7d92e7e458c91b29700bcc1184f71f6a6db84?/0Uy
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2eed68a16eed30a09ee4b9039af3e69df9512076
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2eed68a16eed30a09ee4b9039af3e69df9512076?/Ry=YFc
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2eed68a16eed30a09ee4b9039af3e69df9512076?/HlF
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/909f03c2a8a529bbc46f9dcfd3785ce4d20bd1cd
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/909f03c2a8a529bbc46f9dcfd3785ce4d20bd1cd?/qW=QkO
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/909f03c2a8a529bbc46f9dcfd3785ce4d20bd1cd?/W0U
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/1070b5374d46ec60885b4c9a88067dd4d3e8f5db
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/1070b5374d46ec60885b4c9a88067dd4d3e8f5db?/dq=HBV
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/1070b5374d46ec60885b4c9a88067dd4d3e8f5db?/nHl
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/83d56e00af4cc94b2a651a02607cf2a6273d62db
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/83d56e00af4cc94b2a651a02607cf2a6273d62db?/t3=u8c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/83d56e00af4cc94b2a651a02607cf2a6273d62db?/a4Y
<br>
gitlab.com/EHWGW/fxleljy/-/commit/46567289381fafd9bd882e627dff0bec28a7a987
<br>
gitlab.com/EHWGW/fxleljy/-/commit/46567289381fafd9bd882e627dff0bec28a7a987?/cD=QLF
<br>
gitlab.com/EHWGW/fxleljy/-/commit/46567289381fafd9bd882e627dff0bec28a7a987?/NrL
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/61e25428b1e105ac4814816c128528e75bab2eea
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/61e25428b1e105ac4814816c128528e75bab2eea?/8V=mJu
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/61e25428b1e105ac4814816c128528e75bab2eea?/c6a
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c505982bd20f65f6d5c600b58b9f9f5d5edb0f05
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c505982bd20f65f6d5c600b58b9f9f5d5edb0f05?/cC=Mhv
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c505982bd20f65f6d5c600b58b9f9f5d5edb0f05?/tNr
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/07f4bb97fdf49f74343d227cf90c24008a137d6d
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/07f4bb97fdf49f74343d227cf90c24008a137d6d?/Kr=S93
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/07f4bb97fdf49f74343d227cf90c24008a137d6d?/8c6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f2bf15675d3fce35d9f528c0fe41df3c124a6794
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f2bf15675d3fce35d9f528c0fe41df3c124a6794?/sc=6a3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f2bf15675d3fce35d9f528c0fe41df3c124a6794?/TxR
<br>
gitlab.com/EHWGW/fxleljy/-/commit/11fa66b8ea3d451d9e22ab51b8d1ba9d00656dfa
<br>
gitlab.com/EHWGW/fxleljy/-/commit/11fa66b8ea3d451d9e22ab51b8d1ba9d00656dfa?/29=tQU
<br>
gitlab.com/EHWGW/fxleljy/-/commit/11fa66b8ea3d451d9e22ab51b8d1ba9d00656dfa?/mGk
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6880a4debfe668f2d7aa713fe75bb000fe14aa27
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6880a4debfe668f2d7aa713fe75bb000fe14aa27?/kL=Yzt
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6880a4debfe668f2d7aa713fe75bb000fe14aa27?/VzT
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7a3f01c87183b3204cd8f88058ad33393e25587e
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7a3f01c87183b3204cd8f88058ad33393e25587e?/C0=7Ov
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7a3f01c87183b3204cd8f88058ad33393e25587e?/GkE
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4cd0c4a8c99dc6fd400d5d4ef350e2734bed2b6f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4cd0c4a8c99dc6fd400d5d4ef350e2734bed2b6f?/GN=7b5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4cd0c4a8c99dc6fd400d5d4ef350e2734bed2b6f?/VzT
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/889085a700f7ff4de89cad5b8f1f48574607ca35
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/889085a700f7ff4de89cad5b8f1f48574607ca35?/8c=a4Y
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/889085a700f7ff4de89cad5b8f1f48574607ca35?/UyS
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c6a6388f76d6cbd0c510f039ea3fb9adeadca024
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c6a6388f76d6cbd0c510f039ea3fb9adeadca024?/sz=DAb
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c6a6388f76d6cbd0c510f039ea3fb9adeadca024?/9d7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8b68777c43bed50425c9cefcb5f0e9119a4a7161
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8b68777c43bed50425c9cefcb5f0e9119a4a7161?/el=V26
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8b68777c43bed50425c9cefcb5f0e9119a4a7161?/OsM
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/377e1d6171b5ad6a71d01bb75f24d3d41ac7c029
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/377e1d6171b5ad6a71d01bb75f24d3d41ac7c029?/zj=DhB
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/377e1d6171b5ad6a71d01bb75f24d3d41ac7c029?/9d7
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/cb51c2f6f11400852ca58d8d4024688d78cec632
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/cb51c2f6f11400852ca58d8d4024688d78cec632?/Uy=vtn
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/cb51c2f6f11400852ca58d8d4024688d78cec632?/sMq
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/fdfaf5b0e21f6c1433b86b149b0bba67f7400927
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/fdfaf5b0e21f6c1433b86b149b0bba67f7400927?/Ii=ZnH
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/fdfaf5b0e21f6c1433b86b149b0bba67f7400927?/FjD
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/45b144e019eb76026e517bc91de6b4b078748b21
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/45b144e019eb76026e517bc91de6b4b078748b21?/xo=2zP
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/45b144e019eb76026e517bc91de6b4b078748b21?/ySw
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e35ea1f528bf5860d77e25194bc40e6617e67680
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e35ea1f528bf5860d77e25194bc40e6617e67680?/4l=fTa
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e35ea1f528bf5860d77e25194bc40e6617e67680?/FjD
<br>
gitlab.com/EHWGW/fxleljy/-/commit/56c388d6d834c51080f22c816b75bcede2d2c1c9
<br>
gitlab.com/EHWGW/fxleljy/-/commit/56c388d6d834c51080f22c816b75bcede2d2c1c9?/GN=7ei
<br>
gitlab.com/EHWGW/fxleljy/-/commit/56c388d6d834c51080f22c816b75bcede2d2c1c9?/0Uy
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/22ec4086a84dea0b377abe7ab388a7ed2a5d0316
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/22ec4086a84dea0b377abe7ab388a7ed2a5d0316?/Os=ssQ
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/22ec4086a84dea0b377abe7ab388a7ed2a5d0316?/lFj
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e7872fa8b485740f6fc2e829b62ed82dd9325ff3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e7872fa8b485740f6fc2e829b62ed82dd9325ff3?/MT=Dko
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e7872fa8b485740f6fc2e829b62ed82dd9325ff3?/6a4
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/24cefd11280e737857d5e4d396a9701d1319a83d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/24cefd11280e737857d5e4d396a9701d1319a83d?/nb=FW6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/24cefd11280e737857d5e4d396a9701d1319a83d?/LpJ
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2d151b80a6fd6e29b4d8dfe863251f00ac5fd87c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2d151b80a6fd6e29b4d8dfe863251f00ac5fd87c?/Wg=XHl
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2d151b80a6fd6e29b4d8dfe863251f00ac5fd87c?/Bf9
<br>
gitlab.com/EHWGW/fxleljy/-/commit/db59515bc338ae9a25338ca7ff6668c20a25df4d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/db59515bc338ae9a25338ca7ff6668c20a25df4d?/c6=a4Y
<br>
gitlab.com/EHWGW/fxleljy/-/commit/db59515bc338ae9a25338ca7ff6668c20a25df4d?/UyS
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cea17def1c3bc2147691f091aec40443ea194547
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cea17def1c3bc2147691f091aec40443ea194547?/ll=lJt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cea17def1c3bc2147691f091aec40443ea194547?/8c6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5f8b26f608053ffdc66ddce46f60a78a75275a06
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5f8b26f608053ffdc66ddce46f60a78a75275a06?/XR=FMd
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5f8b26f608053ffdc66ddce46f60a78a75275a06?/VzT
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fddb08e8e69e4509c3d591631a0ea1c43f16d957
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fddb08e8e69e4509c3d591631a0ea1c43f16d957?/29=tQy
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fddb08e8e69e4509c3d591631a0ea1c43f16d957?/GkE
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5c688fc600e99558814856437b8dc3c30cc3170f
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5c688fc600e99558814856437b8dc3c30cc3170f?/qX=RFM
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5c688fc600e99558814856437b8dc3c30cc3170f?/1Vz
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0ad56d91c22faef02aafc80c41726452d2417246
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0ad56d91c22faef02aafc80c41726452d2417246?/4B=SzZ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0ad56d91c22faef02aafc80c41726452d2417246?/ImG
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1f7355ae2aa3569e463f10080146313d32291839
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1f7355ae2aa3569e463f10080146313d32291839?/1L=zmt
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1f7355ae2aa3569e463f10080146313d32291839?/5Z3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7e56aea7fdeee3de0b847273d84b6ed34223d975
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7e56aea7fdeee3de0b847273d84b6ed34223d975?/s9=jtk
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7e56aea7fdeee3de0b847273d84b6ed34223d975?/wQu
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/007ffa89100d6fea1d6e21893a3838f1530c2129
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/007ffa89100d6fea1d6e21893a3838f1530c2129?/nk=B5P
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/007ffa89100d6fea1d6e21893a3838f1530c2129?/hBf
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e64d90d39d712cc1a31087ce4b6481e4b0d63b5b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e64d90d39d712cc1a31087ce4b6481e4b0d63b5b?/L5=cgK
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e64d90d39d712cc1a31087ce4b6481e4b0d63b5b?/SwQ
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/77fdf6968789dad31a4b4cf7ac70549c6f719ada
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/77fdf6968789dad31a4b4cf7ac70549c6f719ada?/g0=A1l
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/77fdf6968789dad31a4b4cf7ac70549c6f719ada?/hBf
<br>
gitlab.com/EHWGW/fxleljy/-/commit/83a5fcffe2d38865d9a0b7f555d10a1719f3b7a7
<br>
gitlab.com/EHWGW/fxleljy/-/commit/83a5fcffe2d38865d9a0b7f555d10a1719f3b7a7?/RH=ytD
<br>
gitlab.com/EHWGW/fxleljy/-/commit/83a5fcffe2d38865d9a0b7f555d10a1719f3b7a7?/SQu
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/0c2618dae0d174640dc4f36233070ff11fe55143
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/0c2618dae0d174640dc4f36233070ff11fe55143?/Ic=nAu
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/0c2618dae0d174640dc4f36233070ff11fe55143?/JnH
<br>
gitlab.com/EHWGW/fxleljy/-/commit/734ce5ddce1f191abf3b8bc41d0b0a1e8d3c356c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/734ce5ddce1f191abf3b8bc41d0b0a1e8d3c356c?/if=60K
<br>
gitlab.com/EHWGW/fxleljy/-/commit/734ce5ddce1f191abf3b8bc41d0b0a1e8d3c356c?/c6a
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/52f9125f0478ac306d41b10783ad6864c8150384
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/52f9125f0478ac306d41b10783ad6864c8150384?/Y8=I9N
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/52f9125f0478ac306d41b10783ad6864c8150384?/LpJ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/da8e485df508e95feed90b97d8b0455d6eb4efb1
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/da8e485df508e95feed90b97d8b0455d6eb4efb1?/bP=2JN
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/da8e485df508e95feed90b97d8b0455d6eb4efb1?/f9d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/25169e1ae639323c0762799c27148dc80024495d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/25169e1ae639323c0762799c27148dc80024495d?/F2=9NK
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/25169e1ae639323c0762799c27148dc80024495d?/pJn
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a6d6eb0f8dbdf19a12b3ce996ae92ef82f4666d9
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a6d6eb0f8dbdf19a12b3ce996ae92ef82f4666d9?/sP=zg3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a6d6eb0f8dbdf19a12b3ce996ae92ef82f4666d9?/iCg
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9fd8227b66322ae43f9b6e73c47afd814f24d28d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9fd8227b66322ae43f9b6e73c47afd814f24d28d?/QH=UvI
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9fd8227b66322ae43f9b6e73c47afd814f24d28d?/xRv
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e26b7a1547b7fbed01eb45634c589b494e435805
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e26b7a1547b7fbed01eb45634c589b494e435805?/ol=C6Q
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e26b7a1547b7fbed01eb45634c589b494e435805?/iCg
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0ff89398ce8cb36726d6585155aea53ebd9edcc2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0ff89398ce8cb36726d6585155aea53ebd9edcc2?/YT=nUO
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0ff89398ce8cb36726d6585155aea53ebd9edcc2?/0Uy
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c36e7a81c3e57156368366d6dba4230df327136b
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c36e7a81c3e57156368366d6dba4230df327136b?/R1=jdU
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c36e7a81c3e57156368366d6dba4230df327136b?/CgA
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1171b962484b650acd642a4b7bb18082540b0071
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1171b962484b650acd642a4b7bb18082540b0071?/IP=74V
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1171b962484b650acd642a4b7bb18082540b0071?/3X1
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7c13be5610fea533ff0764ff812d78153d959a52
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7c13be5610fea533ff0764ff812d78153d959a52?/ur=ICW
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7c13be5610fea533ff0764ff812d78153d959a52?/oIm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8036c8148c0048b1f2d535744e181f835a618f72
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8036c8148c0048b1f2d535744e181f835a618f72?/Qh=ELZ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8036c8148c0048b1f2d535744e181f835a618f72?/X1V
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5bce22d07510d315717f2863a175e8909642bed1
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5bce22d07510d315717f2863a175e8909642bed1?/zZ=Gdu
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5bce22d07510d315717f2863a175e8909642bed1?/mGk
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7f3ba7667350158a6d1ab46d93fbf23fcf41b1c7
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7f3ba7667350158a6d1ab46d93fbf23fcf41b1c7?/Qh=ls9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7f3ba7667350158a6d1ab46d93fbf23fcf41b1c7?/1Vz
<br>
gitlab.com/EHWGW/fxleljy/-/commit/05af9fbec5a280cbc8a831d377a179f5610f3daf
<br>
gitlab.com/EHWGW/fxleljy/-/commit/05af9fbec5a280cbc8a831d377a179f5610f3daf?/BL=CQN
<br>
gitlab.com/EHWGW/fxleljy/-/commit/05af9fbec5a280cbc8a831d377a179f5610f3daf?/sMq
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4123e37bdfccb20212f3eb75ff06413ac015cb3d
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4123e37bdfccb20212f3eb75ff06413ac015cb3d?/f3=KRe
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4123e37bdfccb20212f3eb75ff06413ac015cb3d?/d7b
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8323d2fb6262e2898d590f2f7b500c477700bb88
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8323d2fb6262e2898d590f2f7b500c477700bb88?/gK=8l2
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8323d2fb6262e2898d590f2f7b500c477700bb88?/OsM
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0f1fea2c88755e0a6c62d4527acf0ab795b126d3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0f1fea2c88755e0a6c62d4527acf0ab795b126d3?/NR=Ypq
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0f1fea2c88755e0a6c62d4527acf0ab795b126d3?/f9d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/67e4b29222b66c3565e239dd1acef9a8c58cb2e1
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/67e4b29222b66c3565e239dd1acef9a8c58cb2e1?/jQ=n48
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/67e4b29222b66c3565e239dd1acef9a8c58cb2e1?/QuO
<br>
gitlab.com/EHWGW/fxleljy/-/commit/420062c64c6a64e120314b7145e23697b83a2381
<br>
gitlab.com/EHWGW/fxleljy/-/commit/420062c64c6a64e120314b7145e23697b83a2381?/Ns=stQ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/420062c64c6a64e120314b7145e23697b83a2381?/jDh
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f5eda585248198d0ee92a6a033cd2e811bb326ee
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f5eda585248198d0ee92a6a033cd2e811bb326ee?/1L=VM6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f5eda585248198d0ee92a6a033cd2e811bb326ee?/2W0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c85ba1d9c0fb65f9375a3de4bef28c77bf849a3b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c85ba1d9c0fb65f9375a3de4bef28c77bf849a3b?/CT=XBV
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c85ba1d9c0fb65f9375a3de4bef28c77bf849a3b?/HlF
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/df9a73dbb4a0f777af0ef5420a353c9d602314da
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/df9a73dbb4a0f777af0ef5420a353c9d602314da?/s5=WQD
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/df9a73dbb4a0f777af0ef5420a353c9d602314da?/2W0
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0ecbb7d50e322d0c3ca2cea051da6f16aff41eb8
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0ecbb7d50e322d0c3ca2cea051da6f16aff41eb8?/qG=dOO
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0ecbb7d50e322d0c3ca2cea051da6f16aff41eb8?/HlF
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4944ba0c5024bde037bd4c5505ce7f426ac3796a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4944ba0c5024bde037bd4c5505ce7f426ac3796a?/6T=kHO
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4944ba0c5024bde037bd4c5505ce7f426ac3796a?/a4Y
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cae8b7f98570243853dca7c85db400564286e4ab
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cae8b7f98570243853dca7c85db400564286e4ab?/VS=tn7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cae8b7f98570243853dca7c85db400564286e4ab?/PtN
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/581860b6cf4c22a720da88d237c4db306277d178
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/581860b6cf4c22a720da88d237c4db306277d178?/Hp=P6T
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/581860b6cf4c22a720da88d237c4db306277d178?/8c6
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e34893db8a55e2505dc57aa1314887b6f0dbb347
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e34893db8a55e2505dc57aa1314887b6f0dbb347?/Lf=qgO
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e34893db8a55e2505dc57aa1314887b6f0dbb347?/trL
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d58ed30e8feecde0b0432af2c71cf0545a568347
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d58ed30e8feecde0b0432af2c71cf0545a568347?/HI=pw9
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d58ed30e8feecde0b0432af2c71cf0545a568347?/8c6
<br>
gitlab.com/EHWGW/fxleljy/-/commit/28e912c23fe9d9207177409dd6d1f1a7910360e3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/28e912c23fe9d9207177409dd6d1f1a7910360e3?/K8=iPJ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/28e912c23fe9d9207177409dd6d1f1a7910360e3?/RvP
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/bd57bf5596807dfb83f6d13beab530f21e634301
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/bd57bf5596807dfb83f6d13beab530f21e634301?/9Q=U8S
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/bd57bf5596807dfb83f6d13beab530f21e634301?/kEi
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6896b86174c7d477e6af1addf387c04552658f79
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6896b86174c7d477e6af1addf387c04552658f79?/nR=Fs9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6896b86174c7d477e6af1addf387c04552658f79?/VzT
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/0346c4a696ffdf5dcfe01f62ad9418748c2cf169
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/0346c4a696ffdf5dcfe01f62ad9418748c2cf169?/cp=nD4
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/0346c4a696ffdf5dcfe01f62ad9418748c2cf169?/GkE
<br>
gitlab.com/EHWGW/fxleljy/-/commit/012f7e72637a410b1f35b2ac5632ba38f001a50f
<br>
gitlab.com/EHWGW/fxleljy/-/commit/012f7e72637a410b1f35b2ac5632ba38f001a50f?/Hs=2t6
<br>
gitlab.com/EHWGW/fxleljy/-/commit/012f7e72637a410b1f35b2ac5632ba38f001a50f?/5Z3
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/71ffa1092bb49d98b0e4144ee58de84a34d8d14d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/71ffa1092bb49d98b0e4144ee58de84a34d8d14d?/wR=RSz
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/71ffa1092bb49d98b0e4144ee58de84a34d8d14d?/oIm
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ac005b4c2555e5b478bbf64d7bef0084778b6f59
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ac005b4c2555e5b478bbf64d7bef0084778b6f59?/sT=gdX
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ac005b4c2555e5b478bbf64d7bef0084778b6f59?/d7b
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0d3456917bb6362ee9a036130b793049b2185a35
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0d3456917bb6362ee9a036130b793049b2185a35?/Tt=kUy
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0d3456917bb6362ee9a036130b793049b2185a35?/uOs
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5d6dc6ebb8b622cd1b0422d6778ec96e7f14c811
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5d6dc6ebb8b622cd1b0422d6778ec96e7f14c811?/w3=HEf
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5d6dc6ebb8b622cd1b0422d6778ec96e7f14c811?/DhB
<br>
gitlab.com/EHWGW/fxleljy/-/commit/402a65374dac4aa4b46e0d8c00bade38c065a4c8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/402a65374dac4aa4b46e0d8c00bade38c065a4c8?/c6=4ZZ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/402a65374dac4aa4b46e0d8c00bade38c065a4c8?/ySw
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/09770b66a88340fb3de3357f5514f3c04f12822c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/09770b66a88340fb3de3357f5514f3c04f12822c?/T4=E5p
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/09770b66a88340fb3de3357f5514f3c04f12822c?/lFj
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4b54aa1628b9ee114a9684f93411570ff98a8169
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4b54aa1628b9ee114a9684f93411570ff98a8169?/Gr=1s5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4b54aa1628b9ee114a9684f93411570ff98a8169?/Y2W
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8507369b484461eada441b7f42008736c978fb29
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8507369b484461eada441b7f42008736c978fb29?/MJ=EYF
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8507369b484461eada441b7f42008736c978fb29?/nHl
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a628b8a3488c5700410f3e116b1a2702df7f82e2
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a628b8a3488c5700410f3e116b1a2702df7f82e2?/kh=82M
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a628b8a3488c5700410f3e116b1a2702df7f82e2?/ec6
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e9a94ad9891fbbd4208ba0bc32a6a6ac173f99f9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e9a94ad9891fbbd4208ba0bc32a6a6ac173f99f9?/Pt=Nrp
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e9a94ad9891fbbd4208ba0bc32a6a6ac173f99f9?/lFj
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ce598036038f4becd3cf883169e4c5631fb8acb7
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ce598036038f4becd3cf883169e4c5631fb8acb7?/GD=A4P
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ce598036038f4becd3cf883169e4c5631fb8acb7?/8c6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c5db6b015ce69170cf69ec4503cc293d4c564c28
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c5db6b015ce69170cf69ec4503cc293d4c564c28?/Ro=58G
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c5db6b015ce69170cf69ec4503cc293d4c564c28?/vPt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/48997dd6d02f4d219c990730539e5071ef2bf64e
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/48997dd6d02f4d219c990730539e5071ef2bf64e?/2F=Dd1
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/48997dd6d02f4d219c990730539e5071ef2bf64e?/Ae8
<br>

<h2>项目结构</h2><br>

项目目录采用模块化分层设计，便于维护与扩展。各子目录职责清晰，核心资源列表与前端展示逻辑分离。


mobile-article-aggregator/
├── public/                          # 静态资源目录，无需构建直接复制
│   ├── favicon.ico                  # 站点图标文件
│   └── robots.txt                   # 搜索引擎爬虫规则，屏蔽非生产环境路径
├── src/                             # 源代码主目录
│   ├── assets/                      # 前端资源文件（图片、字体、全局样式）
│   │   ├── images/                  # 项目用到的矢量图与位图素材
│   │   └── styles/                  # 全局基础样式与 CSS 变量定义
│   ├── components/                  # 可复用的 UI 组件
│   │   ├── LinkList.vue             # 链接列表核心渲染组件，支持分页与过滤
│   │   ├── SearchBar.vue            # 关键字搜索输入组件
│   │   └── CategoryFilter.vue       # 分类标签筛选组件
│   ├── data/                        # 数据层，存放静态链接资源列表
│   │   ├── links.json               # 主链接索引文件，包含全部 250 条记录
│   │   └── categories.json          # 分类映射表，定义标签与链接 ID 的对应关系
│   ├── layouts/                     # 页面布局模板
│   │   ├── default.vue              # 默认两栏布局（侧边栏 + 主内容区）
│   │   └── full-width.vue           # 全宽布局，用于搜索与统计页面
│   ├── pages/                       # 路由页面入口
│   │   ├── index.vue                # 首页，展示全部资源列表与分类概览
│   │   ├── about.vue                # 项目介绍与使用说明页面
│   │   └── stats.vue                # 链接统计信息页面（总数、分类分布）
│   ├── utils/                       # 工具函数库
│   │   ├── validator.js             # 链接格式校验与规范化工具
│   │   └── filter.js                # 数组过滤与排序辅助函数
│   └── main.js                      # 应用入口文件，初始化 Vue 实例与插件
├── scripts/                         # 运维与辅助脚本
│   ├── check-links.sh               # 批量检测链接可用性的 Bash 脚本
│   └── generate-sitemap.js          # 生成站点地图 XML 文件的 Node 脚本
├── tests/                           # 单元测试与集成测试
│   ├── unit/                        # 组件与函数的单元测试用例
│   └── e2e/                         # 端到端测试脚本（基于 Playwright）
├── .gitignore                       # Git 版本忽略规则文件
├── package.json                     # Node.js 项目依赖与脚本定义
├── README.md                        # 项目说明文档（本文件）
├── LICENSE                          # MIT 许可证全文
└── vite.config.js                   # Vite 构建工具配置文件


<h2> 贡献指南</h2><br>

我们欢迎社区开发者以多种形式参与本项目的维护与改进。所有贡献需遵守项目行为准则，并按照以下流程操作。

第一步：查阅现有 Issue 与 Pull Request。在提交新贡献之前，请先浏览 GitHub 上的现有议题，确认无人正在处理相同问题或功能请求，避免重复劳动。

第二步：Fork 项目并创建功能分支。将本仓库 Fork 至个人账号下，然后基于 `main` 分支创建一个新的分支，分支命名建议采用 `feature/功能描述` 或 `fix/问题简述` 的格式。

第三步：完成代码或文档修改。请遵循项目既定的代码风格（ESLint 配置）与提交信息规范（使用 Conventional Commits 格式）。若涉及链接列表的增删，请同步更新 `src/data/links.json` 中的对应条目。

第四步：编写或更新测试用例。对于新增的功能或修复的缺陷，请在 `tests/` 目录下补充相应的单元测试或端到端测试，确保代码覆盖率不下降。

第五步：提交 Pull Request。推送本地分支到远程仓库后，向本项目的 `main` 分支发起 Pull Request，并在描述中清晰说明修改内容、动机以及相关 Issue 编号。项目维护者会在三个工作日内进行审阅。

<h2>常见问题</h2><br>

问：如何快速判断某条链接是否仍然有效？

答：项目根目录下的 `scripts/check

> 外链数量: 350 | 生成时间:2026年09月18日03时47分09秒
