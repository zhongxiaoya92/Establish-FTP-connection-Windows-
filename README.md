1.环境部署
<img width="1373" height="930" alt="image" src="https://github.com/user-attachments/assets/efff3810-9617-4430-aeeb-49088904fd9f" />
终端输ipconfig回车复制ip地址

<img width="415" height="418" alt="image" src="https://github.com/user-attachments/assets/4a4eb8a4-5ba4-484d-8502-4307588f760e" />

Win + R输optionalfeatures回车，启用Internet Information Services、FTP服务器、Web管理工具


2.添加FTP站点
<img width="1008" height="705" alt="2026-09-18 214305" src="https://github.com/user-attachments/assets/e29a5d96-d154-423d-98ff-a827dce0f9f3" />
<img width="1014" height="702" alt="image" src="https://github.com/user-attachments/assets/5ff372fe-3de6-4692-87a9-134bcc0840f7" />
<img width="1009" height="705" alt="image" src="https://github.com/user-attachments/assets/c42121b3-938f-442b-8553-b0a6037caf56" />
<img width="1013" height="702" alt="image" src="https://github.com/user-attachments/assets/ff6e140c-87e7-485e-8faf-23b80a655a35" />
win键搜IIS回车，右键电脑名称添加FTP站点
站点名称随意，路径填所需共享文件夹
ip地址填刚复制的，端口默认21，自启动打开，证书可选无
身份验证授权权限全选
至此搭建完成

3.另一端访问

(1)windows在资源管理器地址处输ftp：//(地址)即可

(2)移动端需安装支持ftp网络存储的文件管理器(e.g.Mt管理器)

打开Mt管理器点左上角再点右上角添加ftp，主机填同样的ip，其余保持默认即可
