# 感谢

感谢以下同学(排名不分先后)指出教材中的错误：王文震（统计2202）、

# 勘误
## p28-输出的result外应该是双引号
**修改后：**
两个或多个字符串对应元素拼接时，分隔用的字符可以用`sep`参数指定，默认为空格，例如：
```{r eval=FALSE, tidy=TRUE}
paste("result",c(1:5))
##[1] "result 1" "result 2" "result 3" "result 4" "result 5"
paste("result",c(1:5),sep = "")
##[1] "result1" "result2" "result3" "result4" "result5"
```

## p130-第一行文字中正态分布为应为二项分布
**修改后：**
生成二项分布随机数的函数是`rbinom()`（随机数对应前缀`r`，二项分布为`binom`，组合成`rbinom()`），对应语法是：
