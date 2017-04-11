# 详情页 {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E8%AF%A6%E6%83%85%E9%A1%B5}

每个模块放在一个fieldset中，页面多个fieldset，标题用legend

## 详情页无表单展示 {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E8%AF%A6%E6%83%85%E9%A1%B5%E6%97%A0%E8%A1%A8%E5%8D%95%E5%B1%95%E7%A4%BA}

![](/assets/999.jpg)

```html
<fieldset class="details-block">
   <legend class="title clearfix">商品基本内容<span class="icon-collapse"></span></legend>
   <dl class="dl-horizontal">
      <dt>名称：</dt>
      <dd>阿玛尼女装服饰</dd>
      <dt>尺寸：</dt>
      <dt>运送备注：</dt>
      <dd>
        <label class="radio-inline">
          <input type="radio" name="inlineRadioOptions" value="option1" checked="checked" disabled="disabled" /> 航空禁运
        </label>
        <label class="radio-inline">
          <input type="radio" name="inlineRadioOptions" value="option1" checked="checked" disabled="disabled" /> 航空禁运
        </label>
      </dd>
      <dt>尺码表：</dt>
      <dd>
        <div class="col-md-6 row">
          <p class="margin-bottom-small">尺码表类型：标准<span class="pull-right">最后编辑时间：2016-09-12 09:45:40</span></p>
          <table class="table table-bordered">
            <thead>
              <tr>
                ...
              </tr>
            </thead>
            <tbody>
              <tr>
                ...
              </tr>
            </tbody>
          </table>
         </div>
       </dd>
    </dl>
</fieldset>
```

## 详情页有表单展示![](/assets/99999.bmp) {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E8%AF%A6%E6%83%85%E9%A1%B5%E6%9C%89%E8%A1%A8%E5%8D%95%E5%B1%95%E7%A4%BA}

```html
<fieldset class="details-block">
  <legend class="title clearfix">其他<span class="icon-collapse"></span></legend>
  <form class="form-horizontal form-label-fixed">
    <div class="form-group">
      <label class="col-sm-2 control-label">IQC特殊要求：</label>
      <div class="col-sm-6">
        <textarea class="form-control" rows="3" disabled="disabled">IQC特殊要求</textarea>
      </div>
    </div>
   </form>
</fieldset>
```



