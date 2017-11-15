
# Eclipse上 Emmet 增加代码模板

先安装 `Emmet` 插件，然后在 `Preference` -> `Emmet` -> `Snippets` 上 `new` 模板

![](/pictures/emmet1.png)

```
$.getJSON(${cursor}).then(function(result) {
	console.log(result);
	${cursor}
});
```

输入 `getJ` ，按快捷键 `Ctrl + E` 。效果：

![](/pictures/emmet2.gif)