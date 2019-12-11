# 简单的使用说明
服务器需要预先装好docker和docker-compose组件，可以google一下怎么装 ^_^

在webProject/下面输入`docker-compose up` ，如果见到下图的提示，说明服务启动成功



![photo](https://github.com/bnblzq/webProject/blob/master/fig/fig1.png)


---

在webProject/golang/ 下面有 **sproxy** 可执行程序，每次docker-compse up的时候都会把这个程序复制进容器里面运行。因此，[sproxy程序](https://github.com/RicardoLanJ/coupons-seckill) 有修改的话，需要重新编译出可执行文件放到这个路径下面，再次执行docker-compse up 的动作。

