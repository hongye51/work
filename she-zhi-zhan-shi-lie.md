# 设置展示列1

![](/assets/1.png)

```
<fieldset class="details-block">
  <legend class="title clearfix">设置展示列<i class="fa fa-angle-down"></i></legend>
  <div class="col-md-12">
    <label class="checkbox-inline">
      <input type="checkbox" value="option1"> 状态
    </label>
    <label class="checkbox-inline">
      <input type="checkbox" value="option2"> 仓库
    </label>
  </div>
</fieldset>
```

# 设置展示列2-带标题

![](/assets/1-%281%29.jpg)

col-pannel添加外边框

```
<fieldset class="details-block">
  <legend class="title clearfix">设置展示列<i class="fa fa-angle-down"></i></legend>
     <dl class="dl-horizontal col-pannel">
        <dt>商品属性列：</dt>
        <dd>
          <label class="checkbox-inline">
            <input type="checkbox" value="option1"> 状态
          </label>
          <label class="checkbox-inline">
            <input type="checkbox" value="option2"> 仓库
          </label>
         </dd>
         <dt>记录信息列：</dt>
         <dd>
           <label class="checkbox-inline">
             <input type="checkbox" value="option1"> 状态
           </label>
         </dd>
       </dl>
    </lengend>
</fieldset>
```



