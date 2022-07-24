# nlp

## Jieba

![截屏2022-07-10 17.12.29](/Users/super_wzq/Desktop/截屏2022-07-10 17.12.29.png)



​	

```
.cut()默认为精确模式
```

![截屏2022-07-10 17.15.27](/Users/super_wzq/Desktop/截屏2022-07-10 17.15.27.png)

### 实战之高频词提取

高频词指文章中出现次数较多的且不是无用的词语，在一定程度上代表了文章的焦点所在

### python字典中strip()函数

用来截掉字符串的指定字符，默认为空格。strip()函数是从头开始和从尾开始截掉字符，当没有时则停止。要注意遇到不是的指定截去的字符就会停止



### glob库简介

`glob`是[python的标准库模块](https://docs.python.org/3/library/index.html)，只要安装python就可以使用该模块。glob模块主要用来查找`目录`和`文件`，可以使用`*、？、[]`这三种`通配符`对路径中的文件进行匹配。

- `*`：代表0个或多个字符
- `?`：代表一个字符
- `[]`：匹配指定范围内的字符，如[0-9]匹配数字

#### 常用的函数：

##### 1.glob.glob()

- ```
  def glob(pathname, *, recursive=False):
  ```

  - `pathname`：该参数是要匹配的路径
  - `recursive`：如果是true就会递归的去匹配符合的文件路径，默认是False

- 返回`匹配`到的`路径列表`

##### 2.glob.iglob()

glob.iglob的参数与glob.glob()一样
def iglob(pathname, *, recursive=False):

    pathname：该参数是要匹配的路径
    recursive：如果是true就会递归的去匹配符合的文件路径，默认是False

__返回一个迭代器__，遍历该迭代器的结果与使用相同参数调用glob()的返回结果一致

参考文章来源：https://blog.csdn.net/weixin_41010198/article/details/108321360?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522165858677616782425159626%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=165858677616782425159626&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-108321360-null-null.142^v33^pc_rank_34,185^v2^control&utm_term=glob&spm=1018.2226.3001.4187