##  How to use shortcodes

`bilibili: {{< bilibili BV1Fh411e7ZH(填 bvid) >}}`

`youtube: {{< youtube w7Ft2ymGmfc >}}`

`ppt: {{< ppt src="网址" >}}`

`douban: {{< douban src="网址" >}}`

```
# Links in SRC must not be added with https:// or http://, and you can choose not to add WWW; If desc is written, the value of desc will be displayed in the browser
link: {{< link src="www.sulvblog.cn" desc="https://www.sulvblog.cn" >}}
```

```
gallery:

{{< gallery >}}
{{< figure src="https://www.sulvblog.cn/posts/read/structural_thinking/0.png" >}}
{{< figure src="https://www.sulvblog.cn/posts/read/structural_thinking/0.png" >}}
{{< /gallery >}}
```

##  Possible problems


1. Some users will deploy to GitHub and may encounter cross system problems, such as the prompt `lf will be replaced by CRLF in *******`, and then enter the command: `git config core.autocrlf false`, which solves the problem of automatic conversion of line breaks。
