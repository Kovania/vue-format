# vue-format README

format single file with '.vue'.（格式化单组件“.vue”文件代码）
> If you have some issue, just let me know https://github.com/win7killer/vue-format

`Welcome to star && fork`

## Big Notice
> 0.1.0 版本 尝试解决了 js-beauty 的标签换行导致缩进异常问题，如有问题，随时 issue

## Features
<img src="https://raw.githubusercontent.com/win7killer/vue-format/master/images/command.gif" alt="command" width=600/>

## Requirements
- js-beautify: [https://github.com/beautify-web/js-beautify](https://github.com/beautify-web/js-beautify)
- pug-beautify: [https://github.com/vingorius/pug-beautify](https://github.com/vingorius/pug-beautify)
## Extension Settings

- 使用[js-beautify](https://github.com/beautify-web/js-beautify)配置 和 [pug-beautify](https://github.com/vingorius/pug-beautify)配置
- indent_size 默认使用 editor.tabSize

```json
{
    "html_indent_root": false, // 是否缩进vue template中的根节点
    "break_attr_limit": -1, // tag 的 attrs 大于该数值时，强制 attrs 换行，-1时不换行
    "js-beautify": {
        "indent_size": "editor.tabSize",
        "indent_char": " ",
        "indent_with_tabs": false,
        "brace-style": "collapse",
        "space_after_anon_function": true,
        "css": {},
        "js": {},
        "html": {
            "force_format": ["template"],
        }
    },
    "pug-beautify": {
        "fill_tab": false
    }
}

```

### 暂时停用该配置
<del>// tag 的多个 attribute 换行展示 [auto|force-expand-multiline|force|force-aligned]</del>

<del>// js-beautify.html.wrap_attributes: "force-expand-multiline"</del>

### Change Log
[CHANGELOG.md](./CHANGELOG.md)

### Todo List
[todo.md](./todo.md)

