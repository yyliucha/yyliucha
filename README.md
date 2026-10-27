<p align="center">
  <img src="assets/hero.svg" width="100%" alt="sunming@github 终端窗口：whoami、ls ~/projects、cat motto.txt">
</p>

<p align="center"><b>写后端，也写工具</b> · 把重复的事交给机器</p>

## 01 · 关于

写后端，也写工具。日常的起点往往是某个很烦的小动作：一集一集点播放、每周手动比价、图片一张张存下来——把这种事拆成脚本，再打磨成能一直跑下去的东西，是我比较喜欢的工作方式。

主力是 **C#/.NET** 和 **JavaScript**；要写插件就上 **Java**（Halo 2.x）；跟系统、文件打交道时用 **Python**。项目不管是几百行还是几万行，都尽量做到能交付：结构化日志、容器化、失败可重试、有数据迁移。

- **产品化** — 后端、插件、桌面工具，从零做到能跑
- **自动化** — 采集、定时任务、批处理，把人工步骤压到零
- **工程化** — Docker、迁移、日志，让脚本活过三个月

## 02 · 精选项目

**[steamdeals](https://github.com/yyliucha/steamdeals)** · 中文游戏的价格履历

官方渠道比价 + 价格历史。PostgreSQL 15 存数据，Docker 起服务，日志结构化。目前可直接采集的源是杉果；Steam 需要网络出口，ITAD 需要 API key。

`Node.js` `PostgreSQL` `Docker`

**[plugin-important-dates](https://github.com/yyliucha/plugin-important-dates)** · 记得：纪念日与爱车

Halo 2.x 插件。记纪念日、生日（阳历/农历），顺带管座驾：保险、年检、车船税到期提醒——年检按登记日期和车型规则自动推算。多图相册在附件被删时自动降级，不裂图。

`Java` `Vue` `Halo 2.x` `Gradle`

**[learning-auto-player](https://github.com/yyliucha/learning-auto-player)** · 在线学习自动播放器

防暂停、自动续播、自动签到、播完自动切下一集、多门课自动遍历。书签一键注入和本地真实浏览器（Playwright）两条路径，纯前端零后端。 [在线试用 →](https://yyliucha.github.io/learning-auto-player/)

`JavaScript` `Playwright` `Tampermonkey`

## 03 · 其他项目

| 项目 | 一句话 |
| :--- | :--- |
| [yylcha.pub](https://github.com/yyliucha/yylcha.pub) | C# 桌面工具箱：批量解压、NuGet 上传、git / svn 取码 |
| [pixabay-downloader](https://github.com/yyliucha/pixabay-downloader) | Pixabay 批量下载：全局去重 + 定时任务，Docker 一条命令起 |
| [halo-pixabay-plugin](https://github.com/yyliucha/halo-pixabay-plugin) | 定时把 Pixabay 图片灌进 Halo 附件库，按关键词归档 |
| [yylcha.smoothSignature](https://github.com/yyliucha/yylcha.smoothSignature) | smoothsignature 签名实现 |
| [QR.github.io](https://github.com/yyliucha/QR.github.io) | 二维码小页面 |

## 04 · 技术栈

**语言**

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**数据 · 容器**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**平台 · 框架**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Vue](https://img.shields.io/badge/Vue-41B883?style=for-the-badge&logo=vuedotjs&logoColor=white) ![Halo 2.x](https://img.shields.io/badge/Halo_2.x-1F4FD8?style=for-the-badge) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

## 05 · 联系

问题、建议、想一起做的，直接在对应仓库开 issue——写清场景和复现步骤，我大概率会回。

<div align="center">

<sub>SUNMING / yyliucha · 用 Markdown 和一点强迫症搭的</sub>

<a href="https://github.com/deepseek-ai/deepseek-harness"><img src="https://img.shields.io/badge/powered_by-dsh-4D6BFE?style=for-the-badge&logo=deepseek&logoColor=white" width="121" height="20" alt="powered by dsh"></a>

</div>
