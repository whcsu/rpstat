# 感谢

感谢以下同学(排名不分先后)指出教材初稿和正式出版教材中的错误：王垠植（统计2002）、刘帆（统计2003）、苏雅银（统计2002）、刘芯妤（统计2102）、王文震（统计2202）、吴双（统计2201）等

# 勘误

## p12-安装命令中rmarkdown添加引号
R Markdown文档编辑需要安装`rmarkdown`包:

**修改后：**

install.packages("rmarkdown")
## p22-2.521少了空格
本页中所有"2.52.1"中少了空格。

**修改后：**

2.5 2.1

## p28-输出的result外应该是双引号
**修改后：**

```{r eval=FALSE, tidy=TRUE}
paste("result",c(1:5))
##[1] "result 1" "result 2" "result 3" "result 4" "result 5"
paste("result",c(1:5),sep = "")
##[1] "result1" "result2" "result3" "result4" "result5"
```

## p130-第一行文字中正态分布为应为二项分布
**修改后：**

生成二项分布随机数的函数是`rbinom()`（随机数对应前缀`r`，二项分布为`binom`，组合成`rbinom()`），对应语法是：


## p154-对应的R代码中注释方差应为标准差
**修改后：**

#输入两组均值x1，x2；组数n1，n2；标准差s1，s2
