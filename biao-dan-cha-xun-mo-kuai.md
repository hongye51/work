## 表单查询模块 {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E8%A1%A8%E5%8D%95%E6%9F%A5%E8%AF%A2%E6%A8%A1%E5%9D%97}

查询模块添加外边框加上form-collapse，固定宽度加上form-col-fixed，错误提示在form-group后面添加样式has-error，如果是宽度比较大的比如下图上传时间，在form-group后添加样式form-item-lg使其占两列位置，textarea在form-group后面加上form-textarea，使文字和textarea居上显示。下面代码里罗列了文本框，下拉框，时间选择控件，单选组，文本域几种情况

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



