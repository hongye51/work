## 表格 {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E8%AE%BE%E7%BD%AE%E5%B1%95%E7%A4%BA%E5%88%971}

操作列按钮统一用a标签，外层td上加上样式table-operation控制a标签样式。产品信息列结构用dl，见下面代码。

```
<table class="table table-bordered table-hover">
  <thead>
    <tr>
      <th><input type="checkbox" /> 全选</th>
      <th>订单号</th>
      <th>状态</th>
      <th>仓库</th>
      <th>产品信息</th>
      <th>产品信息</th>
      <th>下单时间</th>
      <th>备注</th>
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
             <dt>库存编码：</dt>
             <dd>Aer554782</dd>
             <dt>库存编码：</dt>
             <dd>Aer554782</dd>
          </dl>
       </td>
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
       <td>注意事项</td>
       <td class="table-operation">
           <a href="">提审</a>
           <a href="">查看</a>
           <a href="" class="del-row">删除</a>
       </td>
      </tr>
   </tbody>
</table>
```



