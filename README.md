serv00 反向sass
此教程和正常的sass操作相反，不用移动文件
我的两个域名都在cf
zjcn.nyc.mn zjccc.us.kg

正常到serv00面板绑定域名 a 记录 例如 alist.zjcn.nyc.mn

这时候无优选
要想优选
把alist.zjcn.nyc.mn的 a 记录 改成cname记录 cname 到 alist.zjccc.us.kg

用alist.zjccc.us.kg 绑这个ip a记录

这时候还是无优选 但是可以访问

alist.zjccc.us.kg在name一个优选域名 比如cf.090227.xyz 例如 cdn.zjccc.us.kg

然后在alist.zjccc.us.kg操作sass 自定义主机名到alist.zjcn.nyc.mn

生效之后，把 alist.zjcn.nyc.mn 的 cname记录 从 alist.zjccc.us.kg 改成 cdn.zjccc.us.kg

这时候有优选 了
