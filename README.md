资产管理 本地版 使用说明
================================================
下载地址：通过网盘分享的文件：Asset-Desktop.rar
链接: https://pan.baidu.com/s/18GgD_xTULeLfX-WSjxsjmg?pwd=99e3 提取码: 99e3 复制这段内容后打开百度网盘手机App，操作更方便哦
一、怎么用
  1. 双击「启动服务.bat」，等浏览器自动打开即可。
  2. 用完后双击「停止服务.bat」，释放端口和内存。
  3. 账号 admin / 密码 admin123

二、目录说明
  app\     程序本体（ruoyi-admin.jar）
  jre\     Java 运行环境，已内置，无需另装 Java
  mysql\   数据库，数据文件在 mysql\data
  redis\   缓存服务，数据在 redis\dump.rdb
  logs\    运行日志（排查问题看 sys-error.log）

三、端口
  网页 18080 / MySQL 3307 / Redis 6380
  都只监听本机，不会与你已装的 MySQL、Redis 冲突。

四、数据备份
  关掉服务后，把 mysql\data 整个目录复制一份就是完整备份。
  恢复时把它粘回 mysql\ 下即可。

五、换台电脑用
  整个文件夹拷过去即可（建议先停止服务再拷），路径不限，
  但不要放在中文路径或需要管理员权限的目录下。
有问题请联系微信：cqrs_99
