# CND 静态文件资源仓库

使用 [jsDelivr](https://www.jsdelivr.com/) 对`GitHub`仓库的资源文件进行访问加速, 解决资源文件无法加载的情况

## 搭建

搭建流程:

1. 上传资源文件到`GitHub`仓库
2. 获取资源文件: `https://cdn.jsdelivr.net/gh/用户名称/仓库名称@版本号/目录/文件`
3. jsDelivr 仓库主页: `https://www.jsdelivr.com/package/gh/用户名称/仓库名称`

示例: [https://cdn.jsdelivr.net/gh/9ml/cdn@main/images/test.jpg](https://cdn.jsdelivr.net/gh/9ml/cdn@main/images/test.jpg)

## 资源文件

### JS 脚本

- `Vue`

```url
# v2.6.14 版本
https://cdn.jsdelivr.net/gh/9ml/cdn@main/js/vue/v2.6.14/
```

- `React`

```url
# v16.8.4 版本
https://cdn.jsdelivr.net/gh/9ml/cdn@main/js/react/v16.8.4/

# v17.0.1 版本
https://cdn.jsdelivr.net/gh/9ml/cdn@main/js/react/v17.0.1/
```

- `jQuery-3.6.0`

```url
https://cdn.jsdelivr.net/gh/9ml/cdn@main/js/jquery/3.6.0.min.js
```

- `dayjs`

```url
https://cdn.jsdelivr.net/gh/9ml/cdn@main/js/dayjs/min.js
```

### CSS

- 样式初始化

```url
https://cdn.jsdelivr.net/gh/9ml/cdn@main/css/base.css
```

### 字体

- 方正卡通

```url
https://cdn.jsdelivr.net/gh/9ml/cdn@main/fonts/fzkt.ttf
```

### 其他

- 头像

```url
https://cdn.jsdelivr.net/gh/9ml/cdn@main/avatar/
```
