# Rclasses
R lang

![my image](/images/33.jpg)

my favourite web sites are
[Search Engine](http://www.google.com)

[education](http://www.edx.com)


```r
data(iris)
head(iris)
```

```
##   Sepal.Length Sepal.Width Petal.Length Petal.Width Species
## 1          5.1         3.5          1.4         0.2  setosa
## 2          4.9         3.0          1.4         0.2  setosa
## 3          4.7         3.2          1.3         0.2  setosa
## 4          4.6         3.1          1.5         0.2  setosa
## 5          5.0         3.6          1.4         0.2  setosa
## 6          5.4         3.9          1.7         0.4  setosa
```

```r
boxplot(iris)
```

![plot of chunk unnamed-chunk-1](figure/unnamed-chunk-1-1.png)

Orange Trees data

```r
v1 <- sample(500:1000, 10, repalce=TRUE)
```

```
## Error in sample(500:1000, 10, repalce = TRUE): unused argument (repalce = TRUE)
```

```r
barplot(v1, col=rainbow(10))
```

```
## Error in barplot(v1, col = rainbow(10)): object 'v1' not found
```
