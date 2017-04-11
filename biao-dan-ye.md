# 表单页 {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E8%A1%A8%E5%8D%95%E9%A1%B5}

## 表单内容 {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E8%A1%A8%E5%8D%95%E5%86%85%E5%AE%B9}

![](/assets/11111}.jpg)
<font color=#d04d53>class: .form-label-fixed, .details-block</font>
```html
<form class="form-horizontal form-label-fixed">
  <fieldset class="details-block">
    <legend class="title clearfix">商品基本内容<span class="icon-collapse"></span></legend>
    <div class="form-group">
      <label class="col-md-2 control-label">供应商名称：</label>
      <div class="col-md-6 text">五二二供应商</div>
    </div>
    <div class="form-group">
      <label class="col-md-2 control-label required">名称：</label>
      <div class="col-md-3"><input type="text" class="form-control"/></div>
      <div class="col-md-4 margin-top-small"><span>*15字以内</span></div>
    </div>
    <div class="form-group">
       <label class="col-md-2 control-label required">品牌：</label>
       <div class="col-md-3">
         <select name="" id="" class="form-control">
           <option value="">请选择</option>
         </select>
       </div>
    </div>
    <div class="form-group">
       <label class="col-md-2 control-label">尺寸：</label>
       <div class="col-md-10">
         <div class="form-inline margin-bottom-base">
            <div class="input-group">
               <div class="input-group-addon">长</div>
               <input type="text" class="form-control input-short">
            </div>
            <div class="input-group">
               <div class="input-group-addon">宽</div>
               <input type="text" class="form-control input-short">
            </div>
            <div class="input-group">
               <div class="input-group-addon">高</div>
               <input type="text" class="form-control input-short">
            </div>
            <span>(单位：mm)</span>
         </div>
         <div class="form-inline margin-bottom-base">
            <div class="input-group">
               <div class="input-group-addon">体积</div>
               <input type="text" class="form-control">
            </div>
            <span>(单位：mm)</span>
         </div>
       </div>
    </div>
    <div class="form-group">
        <label class="col-md-2 control-label">运送备注：</label>
        <div class="col-md-10">
           <label class="radio-inline"><input type="radio" name="inlineRadioOptions" id="inlineRadio1" value="option1"> 航空禁运 </label>
        </div>
     </div>
     <div class="form-group">
        <label class="col-md-2 control-label">颜色：</label>
        <div class="col-md-10">
           <div class="row">
              <div class="col-md-2">
                 <select name="" id="" class="form-control">
                   <option value="">请选择</option>
                 </select>
              </div>
              <div class="col-md-2">
                <input type="text" class="form-control" placeholder="别名" />
              </div>
           </div>
        </div>
    </div>
    <div class="form-group">
        <label class="col-md-2 control-label">尺码表：</label>
        <div class="col-md-10">
           <div class="row">
              <div class="col-md-2">
                <select name="" id="" class="form-control">
                  <option value="">请选择</option>
                </select>
              </div>
              <div class="col-md-6">
                 <button type="button" class="btn btn-info btn-base">新建尺码模板</button>
                 <button type="button" class="btn btn-info btn-base">管理尺码模板</button>
              </div>
           </div>
           <div class="col-md-6 row margin-top-base">
              <p class="margin-bottom-small">尺码表类型：标准<span class="pull-right">最后编辑时间：2016-09-12 09:45:40</span></p>
              <table class="table table-bordered">
                <thead>
                  <tr>
                    <th>尺码</th>
                      <th>型号</th>
                      <th>衣长</th>
                      <th>胸围</th>
                      <th>领围</th>
                  </tr>
                  </thead>
                  <tbody>
                     <tr>
                       <td>S</td>
                       <td>EST15135444</td>
                       <td>100</td>
                       <td>97</td>
                       <td>40</td>
                    </tr>
                  </tbody>
                </table>
           </div>
         </div>
      </div>
  </fieldset>
</form>
```

## 表单下方按钮 {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E8%A1%A8%E5%8D%95%E4%B8%8B%E6%96%B9%E6%8C%89%E9%92%AE}

![](/assets/2222222222.png)

```markdown
<div class="form-footer">
  <button type="button" class="btn btn-primary btn-base">发 布</button>
  <button type="button" class="btn btn-info btn-base">编 辑</button>
  <button type="button" class="btn btn-link">商品列表</button>
</div>
```



