一、ip固定

手机热点网络可根据终端ipconfig信息在网络属性中填写，dns自填

其他网络（）

二、服务端配置

1.环境部署
<img width="1372" height="928" alt="IMG_20260919_150701" src="https://github.com/user-attachments/assets/37650c6d-2637-4407-84b0-8c9bcfaaaedf" />

终端输ipconfig回车复制ip地址

<img width="415" height="418" alt="image" src="https://github.com/user-attachments/assets/4a4eb8a4-5ba4-484d-8502-4307588f760e" />

Win + R输optionalfeatures回车，启用Internet Information Services、FTP服务器、Web管理工具

<img width="1269" height="674" alt="image" src="https://github.com/user-attachments/assets/bfc88ccd-f6b2-432f-b586-ab5229d63cca" />
防火墙需开启的在控制面版对应路径允许ftp服务器进行通信



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

三、客户端访问

(1)windows在资源管理器地址处输ftp://(ip地址)/即可
<img width="1269" height="940" alt="image" src="https://github.com/user-attachments/assets/4f6d0963-94f0-4b8d-acf8-7e482956713e" />



(2)移动端需安装支持ftp网络存储的文件管理器(e.g.Mt管理器)

<img width="1440" height="1155" alt="Screenshot_20260919_150815" src="https://github.com/user-attachments/assets/7445e926-11ff-4a18-84c8-89602df85b61" />
<img width="1440" height="3168" alt="Screenshot_20260919_151136" src="https://github.com/user-attachments/assets/34c38b6b-bd84-4217-9d69-95799f82c9d3" />

打开Mt管理器点左上角再点右上角添加ftp，主机填同样的ip，其余保持默认即可
<img width="1440" height="1364" alt="IMG_20260920_002712" src="https://github.com/user-attachments/assets/47e0ee57-cd11-49f9-9a7c-853db58306c7" />

之后再次点击左上角通过网络连接至服务端
<img width="1440" height="3168" alt="Screenshot_20260920_002543" src="https://github.com/user-attachments/assets/dc50deb9-29ef-4a0d-a768-fcd605dfc74c" />

为避免每次下载上传文件都查路径，建议将/storage/emulated/0/DCIM/下的Camera文件夹（即相册）加进书签内

单个文件长按即可上传，多文件可右滑单个文件后进行复选，或对首尾文件右滑选取中间文件


