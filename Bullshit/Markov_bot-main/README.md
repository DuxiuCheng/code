# 基于马尔可夫链的写作机器人

### 前端

用html/css完成

1. Demo展示（已给出文本的相应展示）

2. 用户提供相关的语料库后训练的成果

### 后端

要完成的几个接口

1. 解析文本：利用马尔可夫链算法，对已有文本进行分词，统计频率

2. 根据解析的文本，进行随机文本生成

3. 将生成的文本返回给前端，在网页上进行输出

### 需要解决的一些问题

1. 前后端的连接：可以用Django之类的框架，完成一个简单的项目应该不是很难
2. 后端的机器人的实现，核心是实现一个马尔可夫链
3. 可选的文本风格：英文文本-->中文文本（诗句、废话生成...）

### 任务分配：

1. 前端和前后端相连，在后端没写好之前可以自己写个小demo

2. 后端解析文本

3. 后端生成文本