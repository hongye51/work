## 分页显示 {#id-%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83css%E6%A0%B7%E5%BC%8F%E5%88%97%E8%A1%A8-%E5%88%86%E9%A1%B5%E6%98%BE%E7%A4%BA}

![](/assets/1111111111.png)

```markdown
<nav class="text-center">
  <ul class="pagination">
    <li>
      <div class="pull-left page-count">
        共 <span class="text-info">725</span> 条记录，每页显示 
        <input class="form-control" type="text" value="8"/> 条
      </div>
    </li>
    <li class="disabled"><a href="#" aria-label="Previous"><span aria-hidden="true">«</span></a></li>
    <li class="active"><a href="#">1 <span class="sr-only">(current)</span></a></li>
    <li><a href="#">2</a></li>
    <li><a href="#">3</a></li>
    <li><a href="#">4</a></li>
    <li><a href="#">5</a></li>
    <li><div class="pull-left page-ellipsis">...</div></li>
    <li><a href="#">42</a></li>
    <li><a href="#" aria-label="Next"><span aria-hidden="true">»</span></a></li>
    <li>
      <div class="input-group pull-left page-to-num">
        <input type="text" class="form-control">
        <span class="input-group-btn">
          <button class="btn btn-default" type="button">GO</button>
        </span>
      </div>
    </li>
  </ul>
</nav>
```



