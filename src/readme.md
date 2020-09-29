1.怎么强制版本回退
本地版本回退到指定版本
使用命令：git push -f origin <分支名>

2.怎么保留当前修改却不提交
使用命令:git stash

3.怎么强制远程覆盖本地修改
git reset --hard origin/master

4.git怎么合并分支
1）本地切换到指定分支
2）指向合并分支并merge
3) 处理冲突

5.idea的git怎么忽略指定文件
https://jingyan.baidu.com/article/3a2f7c2ef5b2c926afd6111b.html

idea--file--setting--edit--file types
ignore后面添加
 *.iml;.idea;target;
