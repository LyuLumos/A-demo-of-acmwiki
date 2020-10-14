## 网站建设
网站仿照 [OI-Wiki](https://oi-wiki.org/) 基于 `mkdocs` 设计，用于学习算法竞赛相关的内容。支持 markdown 和 LaTeX 语法。
本项目托管在GitHub的 [repo](https://github.com/CUCCS/acm-wiki) 中，由Travis自动部署。  
 `master` 分支下为相关文档，`gh-page` 分支下为网页。

## 移动端
手机移动端目录树在左上角，也可在右下角翻页。

## 如何参与
如果您有意向参与贡献，并在仓库 `master` 分支 `/docs` 目录下添加 markdown文件，并在 `mkdocs.yml` 文件内容里增加相应的页面。然后 `pull request` 就可以了。请在 `commit message` 大致说明进行了哪些操作。

### 文档存储格式

- 文件名请务必都小写，以`-`分割，如`file-name`。
- 请务必确保您的文档中引用的**外链**图片已经全部转存到了**本库内**对应的`img`文件夹中，建议处理成`MD 文档名称 + 编号`的形式；（即格式为`![描述信息](img/example-1.jpg)`）。


```text
!!! note "标题"
    内容
```

效果

!!! note "标题"
    内容


## 改变当前页主体颜色

<button data-md-color-primary="red">Red</button>
<button data-md-color-primary="pink">Pink</button>
<button data-md-color-primary="purple">Purple</button>
<button data-md-color-primary="deep-purple">Deep Purple</button>
<button data-md-color-primary="indigo">Indigo</button>
<button data-md-color-primary="blue">Blue</button>
<button data-md-color-primary="light-blue">Light Blue</button>
<button data-md-color-primary="cyan">Cyan</button>
<button data-md-color-primary="teal">Teal</button>
<button data-md-color-primary="green">Green</button>
<button data-md-color-primary="light-green">Light Green</button>
<button data-md-color-primary="lime">Lime</button>
<button data-md-color-primary="yellow">Yellow</button>
<button data-md-color-primary="amber">Amber</button>
<button data-md-color-primary="orange">Orange</button>
<button data-md-color-primary="deep-orange">Deep Orange</button>
<button data-md-color-primary="brown">Brown</button>
<button data-md-color-primary="grey">Grey</button>
<button data-md-color-primary="blue-grey">Blue Grey</button>

<script>
  var buttons = document.querySelectorAll("button[data-md-color-primary]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorPrimary = this.dataset.mdColorPrimary;
    })
  })
</script>


## 联系方式
[Issue](https://github.com/CUCCS/acm-wiki/issues) /
QQ: 3208413453   