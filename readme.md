这个项目库的HTTPS链接是：https://github.com/zqh0129/test.git
下载到本地的命令是：git clone https://github.com/zqh0129/test.git
下载下来是一个test的文件夹，里面有一个.git的隐藏文件夹
在这个文件夹里面放入代码文件或修改已有代码
完成后在test目录内按照以下步骤上传至远端
1.执行命令：git add . （代表添加当前test文件夹内所有文件至远端，点代表当前下所有文件）或 git add haha.txt (代表仅添加haha.txt到远端)
2.git commit -m "本次上传的注释" （字符串内为需要添加的注释，简述本次操作动作及目的，简明扼要即可）
3.git push origin master (推送到的远端项目master分支上，即github上的本项目库)
