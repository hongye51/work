## 设置展示列1 {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E8%AE%BE%E7%BD%AE%E5%B1%95%E7%A4%BA%E5%88%971}

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

## 设置展示列2-带标题 {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E8%AE%BE%E7%BD%AE%E5%B1%95%E7%A4%BA%E5%88%972-%E5%B8%A6%E6%A0%87%E9%A2%98}

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



