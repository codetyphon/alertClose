# alertClose
用来让按钮关闭对话框的

html:
```
<div>
  <button class='close'>×</button>
  <p>hello !</p>
</div>
```
javascript:
```
$('button.close').alertClose();
```

or:
```
$('button.close').alertClose(1000);
```

这样，就可以了。
点击的时候，就会自动关闭了。
