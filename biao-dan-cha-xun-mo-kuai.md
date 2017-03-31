# 表单查询模块

![](/assets/2.jpg)

查询模块添加外边框加上form-collapse，带查询标题里层加上&lt;div class="form-search"&gt;查询&lt;i class="fa fa-angle-down"&gt;&lt;/i&gt;&lt;/div&gt;

查询项固定宽度加上 form-col-fixed，定义了查询项宽度是 320px，如果查询项宽度比较大，比如上传时间，在form-group后添加样式 form-item-lg 使其占两列位置，还可以添加 form-item-xlg 使其100%宽度

错误提示在 form-group 后面添加样式 has-error

textarea 在 form-group 后面加上 form-textarea，使文字和 textarea 居上显示

下面代码里罗列了文本框，下拉框，时间选择控件，单选组，文本域几种情况

```
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



