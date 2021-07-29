# 欢迎阅读电子白板维护手册

## 主要内容
随着电教化改革的推进，越来越多的学校都在教室内安装了用于教学的多功能一体机（下简称“电子白板”）。但由于种种原因，这些电子白板常常处于缺乏维护的状态，极大降低了电子化课堂教学的效率。

本手册由赣州市第三中学（青年路校区）学生会组织编写；旨在为电子白板的日常维护及故障排除提供易于理解的、可复制的解决方案，以便使得任何人都能较为轻松的解决电子白板日常使用过程中的问题，提高电子化教学的效率；而不必过度依赖学校内的技术人员。

本手册共两部分，第一部分“日常维护”主要介绍一些适合教育教学中使用的软件，以及一些能够提升使用体验的~~玄学~~操作。第二部分“故障排除”主要介绍电子白板使用过程中常见的故障以及解决方案。

## 内容适用
本手册所述的所有软件或操作步骤，均于*带有 Service Pack 1 的 64-bit Microsoft Windows 7 旗舰版*以及*Windows 10 企业版 LTSC 1809*上测试通过。

## 部署
本站使用 [MkDocs](https://www.mkdocs.org/) 部署在 [tech-guide.su-gzno3ms.lty.one](https://tech-guide.su-gzno3ms.lty.one/) .

您也可以选择在本地部署一份副本，便于及时看到您修改的结果。具体方式如下（需先安装 Python 3）：

```bash
git clone https://github.com/su-gzno3ms/tech-guide.git
python -m venv tech-guide
cd tech-guide
.\Scripts\Activate.bat
pip install -r requirements.txt
mkdocs serve
```

所有命令正常执行后，您便可访问 <http://127.0.0.1:8000/> 查看本手册的本地版本。您在本地对手册所做的一切更改都会即时反映在此版本上。

## 版权声明
<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />除特别注明外，本站（除提到的第三方软件外）的所有内容均采用<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.zh"> 知识共享署名 - 相同方式共享 4.0 (Creative Commons BY-SA 4.0) 国际许可协议</a> 及附加的 [The Star And Thank Author License](https://github.com/zTrix/sata-license) 进行许可。

这意味着，您可以：

- 自由地共享本站的内容。

- 利用本站的内容自由创作您的作品。

但在此过程中，您必须：

- 保留`赣州市第三中学（青年路校区）学生会`的署名。

- 您创作的内容亦须以相同条件进行共享。

- 为本站的 GitHub 仓库点赞（Star）。

## 改进此手册
我们欢迎您对此手册的任何部分提出意见和建议。请阅读 [如何贡献](https://tech-guide.su-gzno3ms.lty.one/how-to-contribute) 页面了解如何帮助改进此手册的内容。

## 致谢
此手册使用基于 [Python](https://www.python.org) 编程语言的 [MkDocs](https://www.mkdocs.org/) 软件构建，采用 [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) 主题，同时采用了大量开源、闭源的软件辅助我们的工作。在此感谢各软件的作者及开源社区。

在计划创建在线版本时，我们参考了编程竞赛知识整合站点 [**OI Wiki**](https://oi-wiki.org) 的技术架构，同时引用了来自该网站的部分内容。在此向该网站的管理团队及所有贡献者表示感谢。

此手册的所有源文件存储于源代码托管服务平台 [GitHub](https://github.com/)，感谢 GitHub Inc. 提供此项服务。

此手册的在线版本使用 [Netlify](https://www.netlify.com/) 生成并托管至其 CDN，感谢 Netlify Inc. 提供此项服务。

最后，还要特别感谢本手册的所有读者与贡献者们，是你们让这个手册始终保持生机。
