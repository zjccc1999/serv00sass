# serv00 反向sass   

## 此教程和正常的sass操作相反，不用移动文件

## 我的两个域名都在cf

> zjxx.nyc.mn  zjxxx.us.kg

正常到serv00面板绑定域名  ***a 记录***    例如 `alist. zjxx.nyc.mn`

## 这时候无优选

### 要想优选

把`alist.zjxn.nyc.mn`的 a 记录 改成***cname记录***     cname 到  `alist.zjxxx.us.kg`

用`alist.zjxxx.us.kg` 绑这个ip a记录   

这时候还是无优选   但是可以访问

`alist.zjxxx.us.kg`在***name***一个优选域名  比如`cf.090227.xyz`     例如 `cdn.zjxxx.us.kg`       


然后在`alist.zjxxx.us.kg`操作sass 自定义主机名到`alist. zjxx.nyc.mn`

生效之后，把 `alist. zjxx.nyc.mn` 的 cname记录  从 `alist.zjxxx.us.kg` 改成  `cdn.zjxxx.us.kg`


这时候有优选 了 


暂时还不清楚 `alist. zjxx.nyc.mn` `alist.zjxxx.us.kg`   *alist* 这个前缀不一样行不行，懒得测试


![图片alt](https://github.com/zjccc1999/serv00sass/blob/main/%E4%BC%98%E9%80%89.png "图片title")。








