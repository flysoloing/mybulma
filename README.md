### sass编译指令

带有观察的编译指令，新增变更会实时进行编译

```scss
$cd D:\DevEnv\workspace\mybulma
$sass --watch --no-source-map sass/mystyles.scss:css/mystyles.css
$sass --watch --no-source-map sass/qiuqiu.scss:css/qiuqiu.css
```

普通编译指令

```scss
$cd D:\DevEnv\workspace\mybulma
$sass --no-source-map sass/mystyles.scss:css/mystyles.css
$sass --no-source-map sass/qiuqiu.scss:css/qiuqiu.css
```

紧凑输出格式编译指令

```scss
$cd D:\DevEnv\workspace\mybulma
$sass --no-source-map sass/qiuqiu.scss:css/qiuqiu.css --style compact
```

压缩输出格式编译指令

```scss
$cd D:\DevEnv\workspace\mybulma
$sass --no-source-map sass/qiuqiu.scss:css/qiuqiu.min.css --style compressed
```