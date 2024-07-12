# RU2CNKorabliModification
项目致力于修缮与更新游戏内不包含的中文本地化翻译，由EGIST工会所有者Lavandel（薰）创建并维护。
# 如何区分各个版本的差别？
Release中标明Major的为主要更新，最好更新以免游戏内容错误&无法显示；Minor为可选更新，通常修正了一些小错误。
# 如何使用？
非常简单，只需要在Release中下载最新的自解压格式文件（名称示例：RU2CN-版本号-更新服务器-更新类型.exe，如RU2CN-0712v2-Product-minor.exe），然后将其放置在游戏根目录下（即同时拥有bin和profile等文件夹的游戏根目录，默认名称为Korabli），即可打开自解压格式文件实现一路回车安装汉化。

如果您执意手动安装global.mo文件（如果你已经配置好了res_mods下的fontconfig.xml与local_config.xml的话）到对应版本的res_mods/texts/ru/LC_MESSAGES/下即可。

您可以在本仓库[Releases](https://github.com/EGIST-Lavandel/RU2CNKorabliModificate/releases/latest)中，下载该发布版本下的`global.mo`或自解压格式的`版本号.exe`文件
# Q&A
- Q：为什么兵工厂、造船厂没有被翻译？

  A：这些页面实际上是由内置网页浏览器显示的，无法通过本地化文件翻译。
  
- Q：为什么游戏内文本又变回俄语了？

  A：每次版本更新时都会更换`bin`目录下的数字文件夹，重新安装汉化包到最新的数字文件夹下的对应目录即可。
  
- Q：为什么一些本该意译的船名被音译了？

  A：部分意译的船只与其他船只的名字相冲突，故优先级为先使用这一名称的船只，如英国的无畏舰-无畏号与苏联的乌达洛伊-无畏号，根据规则以英国的无畏号优先使用；
  另一种情况是该名称已经广为人知，在此作修改可能会引起玩家群体的疑惑。
# EGIST
即eSotecia Grandiloquento d'isolato Sequenzat，那隔世而存的祗所，是非正常人类所属，是被世人排挤，是清醒。
