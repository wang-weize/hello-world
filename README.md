# 大创

在ssh shell里： 
1、sudo su - #成为超级管理员，密码zft13917331612  
2、conda activate wwz_py36_ #进入conda虚拟环境  
3、jupyter notebook --no-browser --port=8918 --allow-root --certfile=mycert.pem --keyfile mykey.key #打开远程服务器jupyter端口，端口号任意  

在命令行里：  
ssh -N -f -L localhost:8888:localhost:8918 -p 10151 ipp20aitrojan@202.120.39.26 #本地端口8888映射到远程  

在浏览器里：  
打开https://localhost：8888  
输入密码zft13917331612  
