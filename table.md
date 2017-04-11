# 表格

![](/assets/66.jpg)

操作列按钮统一用 a 标签，外层 td 加上 class: .table-operation 控制 a 标签样式。产品信息列结构用 dl，见下面代码。

```html
<table class="table table-bordered table-hover">
  <thead>
    <tr>
      <th><input type="checkbox" /> 全选</th>
      <th>订单号</th>
      <th>状态</th>
      <th>仓库</th>
      <th>产品信息</th>
      <th>下单时间</th>
      <th>操作</th>
    </tr>
  </thead>
  <tbody>
     <tr>
       <td><input type="checkbox" /></td>
       <td class="has-icon">EST15135444<i class="fa fa-copy"></i>
       </td>
       <td><span class="text-muted">新建</span></td>
       <td>白云仓库</td>
       <td>
         <dl class="dl-horizontal col-merge-list">
             <dt>库存编码：</dt>
             <dd>Aer554782</dd>
             <dt>SKU：</dt>
             <dd>Aer554782</dd>
             <dt>尺寸：</dt>
             <dd>40*30*25<em class="text-muted text-unit">cm</em></dd>
         </dl>
       </td>
       <td>2016-07-21 21:20:12</td>
       <td class="table-operation">
           <a href="">提审</a>
           <a href="">查看</a>
           <a href="" class="del-row">删除</a>
       </td>
      </tr>
   </tbody>
</table>
```



