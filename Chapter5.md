# 读取标准输入
``` perl
$line = <STDIN>;
chmop($line);
```
defined会返回0、1（fals、true）。文件的结尾，输入行的操作符返回的是undef，也就是什么都没有的意思。
```
while(defined($line = <STDIN>)){
  chmop;
  ...
}
```

