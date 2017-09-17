# vue-ajax
### 我自己封装的vue-ajax插件
### 使用方法: 
* 引入文件
> * new Vue().ajax.get(url,data,fn,ojson), 或 new Vue().ajax.post(url,data,fn,ojson)
> *     url: 需要获取数据的文件地址 (string)
> *     data: 需要发送的信息 (可省略) (obj)
> *     fn: 获取信息后的回调函数,接收到的返回值为data (function)
> *     ojson: 是否需要转换为json格式 (可省略) (设置为 "json")
> * new Vue().ajax.get().cancel(): 取消异步请求
> * new Vue().ajax.json(str): 可转化json格式字符串
