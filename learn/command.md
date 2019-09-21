# linux命令

## 查看文件内容
cat more head less tail

cat 全部输出 适合查看小的文件 文件合并 cat 1.txt 2.txt >3.txt 将文件1和2 连接合并到文件3

more 分页形式 只能向后翻页
 
head 显示文件前若干多少行数据 head -n 20 file.txt

less 分页形式 可前后翻页

tail 显示文件末尾的内容 同时动态监控文件 tail -f -n 20 1.txt

## linux 三剑客
grep sed awk


