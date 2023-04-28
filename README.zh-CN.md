# Awesome Blazor [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[<img src="https://adrientorris.github.io/wwwroot/images/blazor/logo-blazor.png" align="right" width="170">](https://dotnet.microsoft.com/apps/aspnet/web-apps/client)

> 一个收集了许多Blazor资源的集合。

Blazor是一个使用C#/Razor和HTML构建的.NET Web框架，可以在浏览器中通过WebAssembly运行。

欢迎大家做出贡献！请先查看[贡献指南](https://github.com/AdrienTorris/awesome-blazor/blob/master/CONTRIBUTING.md)。感谢所有的[贡献者](https://github.com/AdrienTorris/awesome-blazor/graphs/contributors)，没有你们这些了不起的人，这个项目就不可能实现！

如果您需要在此列表上进行搜索，可以尝试这个很棒的网站：[Awesome Blazor Browser](https://jsakamoto.github.io/awesome-blazor-browser/)。感谢@ jsakamoto为此所做的努力！[源代码](https://github.com/jsakamoto/awesome-blazor-browser) ![stars](https://img.shields.io/github/stars/jsakamoto/awesome-blazor-browser?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/jsakamoto/awesome-blazor-browser?style=flat-square&cacheSeconds=86400)。

## 目录
* [介绍](#introduction)
* [通用](#general)
* [模板](#templates)
* [示例项目](#sample-projects)
* [教程](#tutorials)
* [库和扩展](#libraries--extensions)
* [实际应用程序](#real-world-applications)
* [视频](#videos)
* [文章](#articles)
* [播客](#podcasts)
* [演示文稿幻灯片](#presentations-slides)
* [工具](#tooling)
* [书籍](#books)
* [电子书](#e-books)
* [课程](#courses)
* [社区](#community)
* [其他语言](#other-languages)

## 介绍

### 什么是Blazor？

Blazor是一个.NET Web框架，用于使用C#构建客户端Web应用程序。

Blazor允许您使用C#而不是JavaScript构建交互式Web UI。 Blazor应用程序由使用C＃，HTML和CSS实现的可重用Web UI组件组成。客户端和服务器代码都是用C#编写的，允许您共享代码和库。更多信息请参见[官方Blazor网站](https://blazor.net)。

### 开始

要开始使用Blazor，请遵循[Blazor入门](https://docs.microsoft.com/aspnet/core/blazor/get-started)文档中的说明。

在Microsoft Learn上完成[使用Blazor构建Web应用程序](https://docs.microsoft.com/en-us/learn/modules/build-blazor-webassembly-visual-studio-code/)学习会话也是一个好主意。还有Jeff Fritz在[Channel9](https://channel9.msdn.com/Series/Beginners-Series-to-Blazor)或[YouTube](https://www.youtube.com/playlist?list=PLdo4fOcmZ0oUJCA3DCzKT79Oe3kdKEceX)上的初学者系列，这是一个开始的良好资源。

## 通用
* [ASP.NET博客档案](https://devblogs.microsoft.com/aspnet/category/blazor/) - 关于Blazor的ASP.NET博客档案。
* [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/client) - 微软官方Blazor网站。
* [Microsoft Learn上的Blazor课程](https://docs.microsoft.com/learn/browse/?expanded=dotnet%2Cazure%2Csurface&products=dotnet%2Cwindows&roles=developer&terms=blazor) - Microsoft Learn上的Blazor课程。
* [.NET Foundation上的Blazor-Dev库](https://dotnet.myget.org/gallery/blazor-dev) - Blazor“dev”分支的每日构建。
* [Blazor扩展](https://github.com/BlazorExtensions) - 为Microsoft ASP.Net Core Blazor精选的扩展。
* [Blazor University](http://blazor-university.com/) - 非官方文档网站。
* [演示](https://blazor-demo.github.io/) - 官方基本演示网站。
* [文档](https://docs.microsoft.com/aspnet/core/blazor) - 微软官方文档。
* [eShopOnBlazor](https://github.com/dotnet-architecture/eShopOnBlazor) - ![GitHub stars](https://img.shields.io/github/stars/dotnet-architecture/eShopOnBlazor?style=flat-square&cacheSeconds=604800&logo=microsoft) ![last commit](https://img.shields.io/github/last-commit/dotnet-architecture/eShopOnBlazor?style=flat-square&cacheSeconds=86400) 将传统的ASP.NET Web Forms应用程序迁移到Blazor，由Microsoft Architecture提供的示例。
* [FAQ](https://github.com/aspnet/Blazor/wiki/FAQ) - 常见问题解答。
* [GitHub存储库](https://github.com/dotnet/aspnetcore) - ![GitHub stars](https://img.shields.io/github/stars/dotnet/aspnetcore?style=flat-square&cacheSeconds=604800&logo=microsoft) ![last commit](https://img.shields.io/github/last-commit/dotnet/aspnetcore?style=flat-square&cacheSeconds=86400) 官方Blazor存储库（即ASP.NET Core存储库）。
* ['Hello World'示例](https://github.com/dodyg/practical-aspnetcore/tree/master/projects/blazor) - 'Hello World'示例。
* [ASP.NET Core简介](https://docs.microsoft.com/aspnet/core/) - ASP.NET Core简介。
* [工作坊](https://github.com/dotnet-presentations/blazor-workshop/) - ![GitHub stars](https://img.shields.io/github/stars/dotnet-presentations/blazor-workshop?style=flat-square&cacheSeconds=604800&logo=microsoft) ![last commit](https://img.shields.io/github/last-commit/aspnet/Blazor?style=flat-square&cacheSeconds=86400) 构建一个完整的Blazor应用程序，并在此过程中了解各种Blazor框架功能。

* [Blazor WebAssembly性能最佳实践](https://docs.microsoft.com/aspnet/core/blazor/webassembly-performance-best-practices) - 由Pranav Krishnamoorthy和Steve Sanderson编写的ASP.NET Core Blazor WebAssembly性能最佳实践。
* [themesof.net](https://themesof.net/) - .NET 6规划过程。
* [30秒Blazor](https://www.30secondsofblazor.net/) - 收集有用的代码片段，灵感来自流行的30秒JavaScript和React。

## 模板
* [BitPlatform模板](https://github.com/bitfoundation/bitplatform) - 使用.Net MAUI和Blazor的解决方案模板，具有开箱即用的最佳实践，可实现快速高质量的跨平台开发，包括Web、Android、iOS和Windows，具有本地美观的Blazor组件。这些模板创建的项目包含开发实际应用程序所需的所有内容，包括（但不限于）CI/CD管道、Azure的基础设施即代码、本地化、多模式开发（Blazor Server/WASM/Hybrid）、内置的防弹异常处理等。[阅读更多](https://bitplatform.dev/)。
* [Blazor Hero](https://github.com/blazorhero/CleanArchitecture) - 使用MudBlazor组件构建的Blazor WebAssembly的干净架构解决方案模板。这个项目将使你的Blazor学习过程比你预期的要容易得多。Blazor Hero旨在成为一个企业级的样板，完全开源，免费。[在这里阅读快速入门指南](https://codewithmukesh.com/blog/blazor-hero-quick-start-guide/)。
* [Blazor BFF Azure AD](https://github.com/damienbod/Blazor.BFF.AzureAD.Template) - 可用于创建在ASP.NET Core Web应用程序中托管的Blazor WASM应用程序的模板，使用Azure AD和Microsoft.Identity.Web进行身份验证，使用BFF安全架构进行身份验证（服务器身份验证）。这将从浏览器中删除令牌，并在每个HTTP请求、响应中使用cookie。该模板还尽可能添加了Blazor应用程序所需的必要安全标头。[在这里阅读快速入门指南](https://github.com/damienbod/Blazor.BFF.AzureAD.Template/blob/main/README-NUGET.md/)。
* [Blazor BFF Azure B2C](https://github.com/damienbod/Blazor.BFF.AzureB2C.Template) - 可用于创建在ASP.NET Core Web应用程序中托管的Blazor WASM应用程序的模板，使用Azure B2C和Microsoft.Identity.Web进行身份验证，使用BFF安全架构进行身份验证（服务器身份验证）。这将从浏览器中删除令牌，并在每个HTTP请求、响应中使用cookie。该模板还尽可能添加了Blazor应用程序所需的必要安全标头。[在这里阅读快速入门指南](https://github.com/damienbod/Blazor.BFF.AzureB2C.Template/blob/main/README-NUGET.md/)。
* [使用Blazor和C#从头开始构建文本编辑器](https://www.youtube.com/playlist?list=PLG4PTDe2qc0i0COivTxn_rjSN96Xq-_K1) - 一系列YouTube视频，介绍如何使用Blazor和.NET从头开始构建自己的IDE。[起点仓库](https://github.com/huntercfreeman/Blazor.Text.Editor-VideoSeries) ![stars](https://img.shields.io/github/stars/huntercfreeman/Blazor.Text.Editor-VideoSeries?style=flat-square) ![last commit](https://img.shields.io/github/last-commit/huntercfreeman/Blazor.Text.Editor-VideoSeries?style=flat-square)。[Blazor Studio仓库](https://github.com/huntercfreeman/BlazorStudio) ![stars](https://img.shields.io/github/stars/huntercfreeman/BlazorStudio?style=flat-square) ![last commit](https://img.shields.io/github/last-commit/huntercfreeman/BlazorStudio?style=flat-square)。
## 示例项目
### AI
[Cledev.OpenAI](https://github.com/lucabriguglia/Cledev.OpenAI) - ![stars](https://img.shields.io/github/stars/lucabriguglia/Cledev.OpenAI?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/lucabriguglia/Cledev.OpenAI?style=flat-square&cacheSeconds=86400) .NET 7 SDK for OpenAI with a Blazor Server playground.
### 认证
* [BlazorBoilerplate](https://github.com/enkodellc/blazorboilerplate) - ![stars](https://img.shields.io/github/stars/enkodellc/blazorboilerplate?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/enkodellc/blazorboilerplate?style=flat-square&cacheSeconds=86400) 带有IdentityServer4 Material Design的真实世界管理仪表板/起始套件。[演示](https://blazorboilerplate.com)。
* [TheIdServer](https://github.com/Aguafrommars/TheIdServer) - ![stars](https://img.shields.io/github/stars/Aguafrommars/TheIdServer?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Aguafrommars/TheIdServer?style=flat-square&cacheSeconds=86400) 基于IdentityServer4的OpenID/Connect服务器。
* [BlazorWithIdentity](https://github.com/stavroskasidis/BlazorWithIdentity) - ![stars](https://img.shields.io/github/stars/stavroskasidis/BlazorWithIdentity?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/stavroskasidis/BlazorWithIdentity?style=flat-square&cacheSeconds=86400) 展示使用带有Identity身份验证的EF Core的Blazor应用程序的示例项目。
* [Blorc.OpenIdConnect](https://github.com/WildGums/Blorc.OpenIdConnect) - ![stars](https://img.shields.io/github/stars/WildGums/Blorc.OpenIdConnect?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/WildGums/Blorc.OpenIdConnect?style=flat-square&cacheSeconds=86400) 在Blazor上使用OpenID Connect的正确方法。
* [Blazor-WASM-AzureAD-gRPC](https://github.com/StefH/BlazorWasmGrpcWithAADAuth) - ![last commit](https://img.shields.io/github/last-commit/StefH/BlazorWasmGrpcWithAADAuth?style=flat-square&cacheSeconds=86400) Blazor WASM、Azure AD、REST和gRPC。
* [Quiz manager secured by Auth0](https://github.com/auth0-blog/secure-blazor-wasm-quiz-manager) - ![last commit](https://img.shields.io/github/last-commit/auth0-blog/secure-blazor-wasm-quiz-manager?style=flat-square&cacheSeconds=86400) 该存储库包含一个使用[Auth0](https://auth0.com/)保护的简单测验管理器的Blazor WebAssembly应用程序。实现细节在以下文章中描述：[Securing Blazor WebAssembly Apps](https://auth0.com/blog/securing-blazor-webassembly-apps/)。
### CMS
* [Blogifier](https://github.com/blogifierdotnet/Blogifier) - ![GitHub stars](https://img.shields.io/github/stars/blogifierdotnet/Blogifier?style=flat-square&cacheSeconds=604800) ![GitHub stars](https://img.shields.io/github/last-commit/blogifierdotnet/Blogifier?style=flat-square&cacheSeconds=86400) ![.NET 5](https://img.shields.io/badge/.NET-5-692079.svg?style=flat-square) 带有Blazor管理仪表板的ASP.NET Core博客应用程序。[演示](http://blogifier.net/blog)。
* [eShopOnBlazor](https://github.com/dotnet-architecture/eShopOnBlazor) - ![GitHub stars](https://img.shields.io/github/stars/dotnet-architecture/eShopOnBlazor?style=flat-square&cacheSeconds=604800&logo=microsoft) ![last commit](https://img.shields.io/github/last-commit/dotnet-architecture/eShopOnBlazor?style=flat-square&cacheSeconds=86400) 将传统的ASP.NET Web Forms应用程序迁移到Blazor。
* [JHipster.NET](https://github.com/jhipster/jhipster-dotnetcore) ![stars](https://img.shields.io/github/stars/jhipster/jhipster-dotnetcore?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/jhipster/jhipster-dotnetcore?style=flat-square&cacheSeconds=86400) [JHipster](https://www.jhipster.tech/)是一个在Java世界中生成现代应用程序的知名平台。[JHipster](https://www.jhipster.tech/)提供了一个蓝图系统，允许覆盖生成器的默认行为。JHipster.NET是一个蓝图，通过asp.net core的后端覆盖了最初在spring boot中生成的后端。对于前端，可以使用所有常见的语言（angular、react），包括Blazor。
这是一份Blazor应用程序的列表，包括CMS、游戏、混合应用程序和IDE等。以下是每个应用程序的简要描述：

### CMS
* [RapidCMS](https://github.com/ThomasBleijendaal/RapidCMS) - 一个基于代码的可扩展Blazor应用程序，为您自己的数据库生成CMS。
* [BlazorShop](https://github.com/kalintsenkov/BlazorShop) - 使用Blazor WebAssembly构建的简单购物应用程序。
* [Umbraco9 & Blazor WASM Starter Site](https://github.com/cornehoskam/Umbraco9-Blazor-Starterkit) - 一个简单的Umbraco v9入门站点，利用Blazor WebAssembly与Tailwind CSS / UI。这是一个我用来玩耍和尝试Umbraco 9、Blazor WebAssembly、TailwindCSS、块列表编辑器以及几个其他概念的项目。

### 游戏
* [Trains.NET](https://github.com/davidwengier/Trains.NET) - 在[Twitch流](https://www.twitch.tv/davidwengier)上使用.NET和C#构建的2D游戏。Trains可以在[wengier.com](https://wengier.com/Trains.NET)上进行在线游戏。
* [AsteroidsWasm](https://github.com/aesalazar/AsteroidsWasm) - .NET 5 C＃应用程序集合，消耗单个运行于：Blazor客户端（WebAssembly）、Blazor服务器、Electron（通过Blazor服务器）、WPF、WinForms、Xamarin的.NET标准项目。[演示](https://aesalazar.github.io/AsteroidsWasm/)。
* [DiabloBlazor](https://github.com/n-stefan/diabloblazor) - DiabloWeb的Blazor端口，使其成为双WebAssembly应用程序：WebAssembly（C＃）PWA托管WebAssembly（C ++）游戏。[演示](https://n-stefan.github.io/diabloblazor)。
* [Board Games](https://github.com/alexyakunin/BoardGames) - Fusion + Blazor示例和一个完全功能的Web应用程序，允许您玩实时多人桌面游戏。[Demo](https://github.com/alexyakunin/BoardGames)。
* [Wolfenstein 3D ported to Blazor](https://github.com/JamesRandall/csharp-wolfenstein) - Wolfenstein 3D移植到现代C#和Blazor。[文章](https://www.jamesdrandall.com/posts/csharp_blazor_wolfenstein_part_1/)。
* [ZXSpectrum](https://github.com/EngstromJimmy/ZXSpectrum) - 在Blazor WebAssembly上运行的ZX Spectrum模拟器。[演示](https://zxspectrum.azurewebsites.net/)。
* [WordleBlazor](https://github.com/johnt84/WordleBlazorApp) - Blazor中流行的Wordle游戏的简单克隆。[Demo](https://wordleblazorapp.azurewebsites.net/)。

### 混合
* [Blazor + Electron](https://aka.ms/blazorelectron) - 在Electron shell中托管Razor组件。这允许使用.NET和Web技术构建现代、高性能的跨平台桌面应用程序。
* [Blazor + WebWindow](https://aka.ms/webwindow) - [WebWindow](https://www.nuget.org/packages/WebWindow)类似于Electron，但不需要捆绑Node.js或Chromium，并且没有大多数API。[WebWindow源代码](https://github.com/SteveSandersonMS/WebWindow)。[Blazor + WebWindow示例在此处](https://github.com/SteveSandersonMS/WebWindow/tree/master/samples/BlazorDesktopApp)。
* [Photino](https://github.com/tryphotino/photino.NET) - ![stars](https://img.shields.io/github/stars/tryphotino/photino.NET?style=flat-square&cacheSeconds=604800&logo=microsoft) ![last commit](https://img.shields.io/github/last-commit/tryphotino/photino.NET?style=flat-square&cacheSeconds=86400) Photino是一个轻量级的开源框架，用于使用Web UI技术构建本地跨平台桌面应用程序，比轻还轻。
* [Blazor + Umbraco Heartcore](https://github.com/umbraco/Umbraco.Headless.Client.Net/tree/master/samples/Umbraco.Headless.Client.Samples.BlazorServer) - ![Last commit](https://img.shields.io/github/last-commit/umbraco/Umbraco.Headless.Client.Net?style=flat-square&cacheSeconds=86400) 使用[Umbraco Heartcore](https://umbraco.com/products/umbraco-heartcore/)与Blazor的示例。
* [Blazor Wasm with ASP.NET Framework 4.x](https://github.com/elgransan/BlazorWasmWithNetFrameworkMVC) - 在进行一些调整和限制后，您可以在Net Framework 4.x或其他环境中运行Blazor Wasm。[Medium上的说明](https://medium.com/@santiagoc_33226/using-blazor-wasm-with-net-framework-mvc-or-another-old-external-site-7fc0884fcfca)。
* [RemoteBlazorWebView](https://github.com/budcribar/RemoteBlazorWebView) - ![last commit](https://img.shields.io/github/last-commit/budcribar/RemoteBlazorWebView?style=flat-square&cacheSeconds=86400) RemoteBlazorWebView使您能够使用Web浏览器与使用BlazorWebView WPF控件或WinForms控件开发的程序的用户界面进行交互。
* [BlazorInAngularDemo](https://github.com/Xenoage/BlazorInAngularDemo) - ![last commit](https://img.shields.io/github/last-commit/Xenoage/BlazorInAngularDemo?style=flat-square&cacheSeconds=86400) 演示了如何通过集成Blazor组件（包括调用Angular服务方法）逐步将现有的Angular应用程序迁移到Blazor。[演示](https://xenoage.github.io/BlazorInAngularDemo/)。
IDE
* [Blazor Studio](https://github.com/huntercfreeman/BlazorStudio) - 这是一个使用Photino主机、Blazor UI和C#编写的.NET解决方案的IDE。
* [Picat Language IDE](https://github.com/andrzejolszak/picat-blazor-monaco-ide/) - 这是一个基于Monaco Editor的[Picat逻辑编程语言](http://picat-lang.org/) IDE。 [演示](https://andrzejolszak.github.io/picat-blazor-monaco-ide/PicatBlazorMonaco/publish/wwwroot/)。

IoT
* [PresenceLight](https://github.com/isaacrlevin/PresenceLight) - PresenceLight是一种将您的各种状态广播到菲利普斯Hue或LIFX灯泡的解决方案。 您可以广播的一些状态包括：您在Microsoft Teams中的可用性、您当前的Windows 10主题和您选择的主题或颜色。 [博客文章](https://www.isaaclevin.com/post/presence-light)。 [演示视频](https://www.youtube.com/playlist?list=PL_IEvQa-oTVtB3fKUclJNNJ1r-Sxtjc-m)。
* [Meadow Weather](https://github.com/bradwellsb/blazor-meadow-weather) - 在这个示例中，Meadow微控制器轮询来自LM35温度传感器的数据。该数据通过HTTP请求发送到API控制器端点，并存储在数据库中，可以使用Blazor Web应用程序中的图表可视化。

机器学习
* [Scalable sentiment analysis](https://github.com/dotnet/machinelearning-samples/tree/master/samples/csharp/end-to-end-apps/ScalableSentimentAnalysisBlazorWebApp) - 这是一个示例，能够在非常UI交互式的应用程序（基于Blazor）中对用户写入的内容进行情感分析预测/检测，并在服务器端运行ML.NET模型（基于二元分类的情感分析）。
* [optimizer.ml](https://github.com/jameschch/LeanParameterOptimization) - 适用于算法参数的“无服务器”通用优化套件，还提供[Quantconnect Lean](https://github.com/QuantConnect/Lean)交易算法的离线优化。[演示 (https://optimizer.ml)](https://optimizer.ml)。
* [棒球机器学习工作台](https://github.com/bartczernicki/MachineLearning-BaseballPrediction-BlazorApp) - 展示使用内存中的机器学习模型进行假想分析的 Web 应用程序。[在线演示](https://baseballmlworkbench-v1.azurewebsites.net)。
* [BlazorML5](https://github.com/sps014/BlazorML5) - 使用 JSInterop 机制为 Blazor 提供 ML5 机器学习的支持。
### 移动端
* [Mobile Blazor Bindings](https://aka.ms/mobileblazorbindings) - 实验性的移动 Blazor 绑定 - 使用 Blazor 构建原生移动应用。
### 快速开发框架
* [WalkingTec.Mvvm (WTM)](https://github.com/dotnetcore/WTM) - 基于 .NET Core 和 EF 的开发框架。支持 Blazor、Vue、React 和 LayUI，并支持一键代码生成CRUD，导入/导出等功能。[网站](https://wtmdoc.walkingtec.cn)。
### 待办事项
* [David Fowler 的 TodoApi](https://github.com/davidfowl/TodoApi) - .NET 7 中 David Fowler 制作的待办事项应用程序，具有一个使用 minimal APIs 的 ASP.NET Core 托管 Blazor WASM 前端应用程序和 ASP.NET Core REST API 后端。
* [Bolero.TodoMVC](https://github.com/fsbolero/TodoMVC) - ![GitHub stars](https://img.shields.io/github/stars/fsbolero/TodoMVC?style=flat-square&cacheSeconds=604800) ![GitHub stars](https://img.shields.io/github/last-commit/fsbolero/TodoMVC?style=flat-square&cacheSeconds=86400) 一个使用 Bolero 克隆的 TodoMVC。
* [ididit!](https://github.com/Jinjinov/Ididit) - ![stars](https://img.shields.io/github/stars/Jinjinov/Ididit?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Jinjinov/Ididit?style=flat-square&cacheSeconds=86400) 适合拖延症患者使用的习惯追踪器。做笔记、管理任务、跟踪习惯。[演示](https://app.ididit.today/)。
### 其他
* [CleanArchitecture](https://github.com/blazorhero/CleanArchitecture) - ![stars](https://img.shields.io/github/stars/blazorhero/CleanArchitecture?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/blazorhero/CleanArchitecture?style=flat-square&cacheSeconds=86400) Blazor WebAssembly 的 Clean Architecture 模板，使用 MudBlazor 组件构建。
* [Oqtane Framework](https://github.com/oqtane/oqtane.framework) - ![GitHub stars](https://img.shields.io/github/stars/oqtane/oqtane.framework?style=flat-square&cacheSeconds=604800) ![GitHub stars](https://img.shields.io/github/last-commit/oqtane/oqtane.framework?style=flat-square&cacheSeconds=86400) Blazor 的模块化应用程序框架。
* [Flight Finder](https://github.com/aspnet/samples/tree/master/samples/aspnetcore/blazor) - ![stars](https://img.shields.io/github/stars/aspnet/samples?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/aspnet/samples?style=flat-square&cacheSeconds=86400&logo=microsoft) 航班查询器。
* [LinqToTwitter Blazor sample](https://github.com/JoeMayo/LinqToTwitter/tree/main/Samples/LinqToTwitter5/net48/CSharp/AspNetSamples/BlazorDemo) - ![stars](https://img.shields.io/github/stars/JoeMayo/LinqToTwitter?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/JoeMayo/LinqToTwitter?style=flat-square&cacheSeconds=86400) Twitter API（Twitter 库）的 LINQ 提供程序。
* [BlazorFileReader](https://github.com/Tewr/BlazorFileReader) - ![GitHub stars](https://img.shields.io/github/stars/Tewr/BlazorFileReader?style=flat-square&cacheSeconds=604800) ![GitHub stars](https://img.shields.io/github/last-commit/Tewr/BlazorFileReader?style=flat-square&cacheSeconds=86400) 在 Blazor 中读取只读文件流。[演示](https://tewr.github.io/BlazorFileReader/)。
* [eShopOnBlazor](https://github.com/dotnet-architecture/eShopOnBlazor) - ![GitHub stars](https://img.shields.io/github/stars/dotnet-architecture/eShopOnBlazor?style=flat-square&cacheSeconds=604800&logo=microsoft) ![last commit](https://img.shields.io/github/last-commit/dotnet-architecture/eShopOnBlazor?style=flat-square&cacheSeconds=86400) 传统 ASP.NET Web Forms 应用程序迁移到 Blazor。
* [BlazorChatSample](https://github.com/conficient/blazorchatsample) - ![stars](https://img.shields.io/github/stars/conficient/blazorchatsample?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/conficient/blazorchatsample?style=flat-square&cacheSeconds=86400) 使用 SignalR JS 客
* [Command and Control, by David Fowler](https://github.com/davidfowl/CommandAndControl) - 这是一个使用Blazor Server和SignalR实现的命令与控制模块，代理连接到托管SignalR Hub的Blazor服务器应用程序，我们可以针对连接的代理发出各种命令（此功能使用客户端结果）。
* [BlazorCRUD](https://github.com/thbst16/BlazorCrud) - 这是一个展示Blazor的关键特性的样例业务应用程序。[演示](https://becksblazor.azurewebsites.net/)。
* [Money](https://github.com/maraf/Money) - 这是一个使用CQRS+ES实现的资金管理器。[演示](https://app.money.neptuo.com/)。
* [Blazor Weather](https://github.com/danroth27/BlazorWeather) - 这是一个Blazor天气样例应用程序，显示您当前位置和一些固定位置的当前天气。由Daniel Roth在.NET Conf 2019上演示。 [演示](https://aka.ms/blazorweather).
* [Blazor.SVGEditor](https://github.com/KristofferStrube/Blazor.SVGEditor) - 这是一个使用Blazor WASM编写的基本HTML SVG编辑器。 [演示](https://kristofferstrube.github.io/Blazor.SVGEditor/)。
* [NethereumBlazor](https://github.com/Nethereum/NethereumBlazor) - 这是一个以太坊区块链浏览器和简单钱包。
* [FFmpegBlazor](https://github.com/sps014/FFmpegBlazor) - FFmpegBlazor提供了利用ffmpeg.wasm从Blazor Wasm C#使用的能力。[ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm) 是FFmpeg的Webassembly/Javascript版本，可以在浏览器内部实现视频和音频录制、转换和流处理。
* [Blazor Studio](https://github.com/huntercfreeman/BlazorStudio) - 这是一个使用.NET编写的免费开源IDE - 一个Photino主机，Blazor UI和C#。
* [Planning Poker](https://github.com/duracellko/planningpoker4azure) - 这是一个用于分布式团队玩Planning Poker的应用程序。该应用程序是使用Blazor实现的，并演示了如何通过配置更改在客户端和服务器端模式之间切换。[演示](http://planningpoker.duracellko.net)。

- C# Regex Tester online：用于验证 .Net 正则表达式语法的在线工具。
- C# Regex Online tool：用于验证 .Net 正则表达式语法，可以查看分割列表、表格等的在线工具。
- Blazor Tour of Heroes：使用 Blazor-State（利用 MediatR 流水线进行状态管理架构）实现 Redux 风格状态的 Blazor 英雄之旅。
- Blazor.Text.Editor：一个使用 Blazor UI 框架为 .NET 提供文本编辑器组件库的项目。
- Blazor Wake-on-LAN：一个用于本地网络的 Wake-on-LAN 应用程序，使用 Blazor Server + EF Core + DI + CI 实现。
- BlazingWaffles：一个包装 Waffle Generator 的 Blazor 应用程序。该生成器可以输出可读的无意义文本，可用作 Lorum Ipsum 的替代品。
- Nethereum Playground：在浏览器上编译和运行 Nethereum 片段的在线工具。
- TypinExamples：一个演示如何将 Typin 框架与 Blazor SPA 应用程序（使用 Xterm.js 和自定义 Web Workers 实现 C# 在浏览器中模拟终端体验）结合使用的样例项目。[Live demo](https://adambajguz.github.io/Typin/)。
- Unofficial eShopOnContainers：eShopOnContainers 的非官方 Blazor WebAssembly 客户端。
- UpBlazor：与 Up 银行集成的 Blazor Server，以协助用户进行预算并获得强大的未来见解。使用 Clean Architecture 和 Marten DB。
- WordTester：一个使用闪卡和间隔重复学习方法学习外语单词的应用程序。

## 开源项目

- Css in Blazor presentation's source code：Ed Charbeneau 关于 Blazor 和 CSS 的演示的源代码。
- BlazorViz interop wrapper for Viz.js：生成 Graphviz DOT 语言文件并可视化树形数据结构的示例。[演示](https://mrzhdev.github.io/BlazorViz/)。
- BlazorServerImageRecognitionApp：一个简单的 Blazor Server 应用程序，使用图像识别来识别并提取用户上传的图像文件中的文本。[演示](https://blazorimagerecognitionapp.azurewebsites.net/)。
- FootballBlazorApp：一个简单的 Football Blazor Server Web 应用程序，显示赛程和结果、小组排名、球队和球员，并具有球员搜索功能。[演示](https://premierleagueblazorapp.azurewebsites.net/)。

## 教程

- Blazor workshop：.NET 基金会的 Blazor 应用程序构建工作坊，Blazzing Pizza。
- Blazor Meadow Web API Weather Chart.js：2021 年 6 月 - 在 Blazor 应用程序中使用 Chart.js 显示传感器数据。[源代码](https://github.com/bradwellsb/blazor-meadow-weather)。
- NextTechEvent by Coding After Work：构建 "NextTechEvent" 站点，帮助演讲者、组织者和参与者找到他们下一次的技术活动。[源代码](https://github.com/CodingAfterWork/NextTechEvent)。
- Archives：[2021](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2021.md#tutorials)、[2020](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2020.md#tutorials)、[2019](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2019.md#tutorials)、[2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#tutorials)。
## 库和扩展
* 可重用的组件，如按钮、输入框、网格等。另请参阅[Blazor组件包功能比较表](https://github.com/AdrienTorris/awesome-blazor/blob/master/Component-Bundle-Comparison.md)。
### 组件包
* [FAST](https://github.com/microsoft/fast) - ![GitHub stars](https://img.shields.io/github/stars/microsoft/fast?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/microsoft/fast?style=flat-square&cacheSeconds=86400) ![GitHub licence](https://camo.githubusercontent.com/78f47a09877ba9d28da1887a93e5c3bc2efb309c1e910eb21135becd2998238a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d79656c6c6f772e737667) FAST是一个基于Web组件和现代Web标准构建的技术集合，旨在帮助您高效地解决网站和应用程序设计和开发中一些最常见的挑战。 [FAST和Blazor文档](https://www.fast.design/docs/integrations/blazor/)。
* [Ant Design Blazor](https://github.com/ant-design-blazor/ant-design-blazor) - ![GitHub stars](https://img.shields.io/github/stars/ant-design-blazor/ant-design-blazor?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/ant-design-blazor/ant-design-blazor?style=flat-square&cacheSeconds=86400) 一组基于Ant Design和Blazor的企业级UI组件。 ([演示文档](https://ant-design-blazor.github.io/)).
* [MudBlazor](https://github.com/MudBlazor/MudBlazor) - ![stars](https://img.shields.io/github/stars/MudBlazor/MudBlazor?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/MudBlazor/MudBlazor?style=flat-square&cacheSeconds=86400) MudBlazor是一个雄心勃勃的Material Design组件框架，专注于易用性和清晰的结构，在不需苦恼于CSS和Javascript的情况下，非常适合.NET开发人员快速构建Web应用程序。 MudBlazor完全由C#编写，使其能够自适应、修复或扩展框架，并且文档中的众多示例使学习MudBlazor变得非常容易。 [文档](https://mudblazor.com/)。 [演示](https://try.mudblazor.com/)。
* [Blazorise](https://github.com/Megabit/Blazorise) - ![GitHub stars](https://img.shields.io/github/stars/Megabit/Blazorise?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Megabit/Blazorise?style=flat-square&cacheSeconds=86400) 带有对Bootstrap、Bulma、AntDesign和Material CSS的支持的Blazor组件。 ([Bootstrap演示](https://bootstrapdemo.blazorise.com/)), ([Bulma演示](https://bulmademo.blazorise.com/)), ([AntDesign演示](https://antdesigndemo.blazorise.com/)), ([Material演示](https://materialdemo.blazorise.com/)).
* [MASA Blazor](https://github.com/BlazorComponent/MASA.Blazor) - 一个企业级的UI组件库，基于Material Design和Blazor，几乎完美复制了Vuetify，由MASA团队开发，保持免费开源。有长期路线图和文档与演示。
* [Radzen.Blazor](https://github.com/akorchev/razor.radzen.com) - 原生的Blazor UI组件，包括DataGrid、DataList、Tabs、Dialog等，具有丰富的Demo。
* [BlazorStrap](https://github.com/chanan/BlazorStrap) - 一个基于Bootstrap 4的Blazor UI组件库，提供了Material Design风格的组件，也有Demo可用。
* [FAST Blazor](https://github.com/microsoft/fast-blazor) - 一个轻量级的Microsoft FluentUI Web Components包装器，用于.NET 6.0 Razor视图和Blazor中，具有示例和演示。
* [Element-Blazor](https://github.com/Element-Blazor/Element-Blazor/blob/master/README.en.md) - 一个使用Element UI的Blazor组件库，API模仿Element，CSS直接使用Element的样式，HTML结构直接使用Element的HTML结构，并提供了Blazor WebAssembly版本的演示。
* [BlazorFluentUI](https://github.com/BlazorFluentUI/BlazorFluentUI) - 把FluenUI/Office Fabric React组件和样式简单移植到Blazor中，提供了WebAssembly和SignalR的客户端演示。
* [BootstrapBlazor](https://github.com/ArgoZhang/BootstrapBlazor) - 一个基于Bootstrap的可重用UI组件库，提供了Demo作为文档。
* [ComponentOne Blazor UI Components](https://www.grapecity.com/componentone/blazor-ui-controls) - 外部链接。这是一个快速的数据网格、列表视图、输入以及其他本地化的Blazor服务器和客户端应用程序组件。
* [DevExpress Blazor UI Components](https://github.com/DevExpress/RazorComponents) - 这是一套原生UI Blazor组件的集合，包括数据网格、透视网格、调度器和图表等，支持Blazor服务器端和Blazor客户端平台。
* [Syncfusion Blazor UI Components](https://www.syncfusion.com/blazor-components) - 这是最全面的本机Blazor组件库，包括[数据网格](https://www.syncfusion.com/blazor-components/blazor-datagrid)、[图表](https://www.syncfusion.com/blazor-components/blazor-charts)、[调度器](https://www.syncfusion.com/blazor-components/blazor-scheduler)、[图表](https://www.syncfusion.com/blazor-components/blazor-diagram)和[文档编辑器](https://www.syncfusion.com/blazor-components/blazor-word-processor)组件。 ([演示](https://blazor.syncfusion.com/demos/)）。
* [ADMINLTE](https://github.com/sjefvanleeuwen/blazor-adminlte) - 这是一个可重复使用的组件集合，其中包括按钮、表单元素和页面模板等，您可以轻松地作为设计师或开发人员开发数字服务。这个项目适配了ADMINLTE 3，所以这些组件可以从dotnet core Blazor中使用。
* [Blazority](https://github.com/blazority/support) - 这是一个基于Clarity UI设计的Blazor组件库，包括30多个组件，包括Datagrid和Tree-view ([文档&Demos](https://blazority.com))。
* [Makani](https://github.com/getspacetime/makani) - 这是一个轻量级、可定制的、面向性能的组件库，适用于Blazor和.NET MAUI Hybrid。使用TailwindCSS构建。[演示](https://getspacetime.github.io/makani/)。
* [Material.Blazor](https://github.com/Material-Blazor/Material.Blazor) - 这是一个替代的Material Theme Razor组件库。 Material.Blazor着重于给您纯粹的标记来自[Google's material-components-web](https://github.com/material-components/material-components-web/tree/master/packages)——我们不试图坐在您和您对Google的CSS和SASS的使用之间，因为他们做得比我们好。我们还有一些很酷的“加号”组件。[查看我们的演示和全面的文档](https://material-blazor.com)。