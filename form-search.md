# 表单查询模块

![](/assets/2.jpg)

### 基础结构
<font color=#d04d53>class: .form-collapse, .form-search, .form-col-fixed</font>
```html
<form class="form-inline form-collapse form-col-fixed">
  <div class="form-search">查询<span class="icon-collapse"></span></div>
  <div class="form-group">
    <label class="control-label">常态合作编码</label>
    <input type="text" class="form-control" placeholder="">
  </div>
  <div class="form-group">
    <label class="control-label">状态</label>
    <select class="form-control">
      <option value="">请选择</option>
    </select>
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
  <div class="form-group">
    <button type="submit" class="btn btn-primary btn-base">查 询</button>
    <button type="submit" class="btn btn-default btn-base">重 置</button>
  </div>
</form>
```
### 表单项比较长结构
<font color=#d04d53>class: .form-item-lg, .form-item-xlg</font>
```html
<div class="form-group form-item-lg">
  <label class="control-label">上传时间</label>
  <input type="text" class="form-control time-select">
  -
  <input type="text" class="form-control time-select">
</div>
<div class="form-group form-item-xlg">
  <label class="control-label">适用仓库</label>
  <div class="checkbox">
    <label class="checkbox-inline">
      <input type="checkbox" id="inlineCheckbox1" value="option1"> 北京
    </label>
    <label class="checkbox-inline">
      <input type="checkbox" id="inlineCheckbox2" value="option2" checked="checked"> 上海
    </label>
  </div>
</div>
```

### 表单项带文本域结构
<font color=#d04d53>class: .form-textarea</font>
```html
<div class="form-group form-textarea">
  <label class="control-label">条形码</label>
  <textarea class="form-control"></textarea>
</div>
```

### 表单项带错误提示结构
```html
<div class="form-group has-error">
  <label class="control-label">常态合作编码</label>
  <input type="text" class="form-control" placeholder="">
  <span class="help-block">请输入正确的常态合作编码</span>
</div>
<div class="form-group form-item-lg has-error">
  <label class="control-label">上传时间</label>
  <input type="text" class="form-control time-select">
  -
  <input type="text" class="form-control time-select">
  <span class="help-block">结束时间必须大于开始时间</span>
</div>
```


