# 面包屑

![](/assets/1.bmp)
<font color=#d04d53>class: .crumbs</font>

没有右侧的返回和全屏按钮直接写面包屑

```html
<div class="crumbs">
  <ol class="breadcrumb">
    <li>首页</li>
    <li>仓库服务</li>
    <li class="active">入库订单</li>
  </ol>
</div>
```

有右侧的返回和全屏按钮直接写面包屑

```html
<div class="crumbs">
  <ol class="breadcrumb">
    <li>首页</li>
    <li>仓库服务</li>
    <li class="active">入库订单</li>
  </ol>
  <div class="crumbs-toolbar">
    <a href="javascript:;">返回<i class="fa fa-mail-reply"></i></a>
    <a href="javascript:;">全屏<i class="fa fa-arrows"></i></a>
  </div>
</div>
```



