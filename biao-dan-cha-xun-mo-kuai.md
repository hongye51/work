# 表单查询模块

![](/assets/2.jpg)

<font color=#d04d53>class: .form-collapse, .form-search, .form-col-fixed, .form-item-lg, .form-item-xlg, form-textarea</font>

```html
<form class="form-inline form-collapse form-col-fixed">
   <div class="form-search">查询<i class="fa fa-angle-down"></i></div>
   <div class="form-group has-error">
      <label class="control-label">常态合作编码</label>
      <input type="text" class="form-control" placeholder="">
      <span class="help-block">请输入正确的常态合作编码</span>
   </div>
   <div class="form-group">
     <label class="control-label">状态</label>
     <select class="form-control">
        <option value="">请选择</option>
     </select>
   </div>
   <div class="form-group form-item-lg has-error">
     <label class="control-label">上传时间</label>
     <input type="text" class="form-control time-select">
      -
     <input type="text" class="form-control time-select">
     <span class="help-block">结束时间必须大于开始时间</span>
   </div>
   <div class="form-group">
     <label class="control-label">是否新供应商</label>
     <label class="radio-inline">
        <input type="radio" name="radio" checked="checked"> 是
     </label>
     <label class="radio-inline">
        <input type="radio" name="radio" checked="checked"> 否
     </label>
   </div>
   <div class="form-group form-textarea">
     <label class="control-label">条形码</label>
     <textarea class="form-control"></textarea>
   </div>
   <div class="form-group">
     <button type="submit" class="btn btn-primary btn-base">查 询</button>
     <button type="submit" class="btn btn-default btn-base">重 置</button>
   </div>
</form>
```



