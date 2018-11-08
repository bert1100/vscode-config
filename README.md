# vscode-config
vscode编辑器的个人设置

### 常用的配置：

- 中英文字体美化

  > 增加 'Source Code Variable Medium', 'Microsoft YaHei UI' 

- 换行设置
- 设置终端使用git带的mintty.exe 和 bash.exe
- 分别设置合适的编辑器行高和终端行高
- 增加exclude文件：**/node_modules

### 常用的插件扩展

- 文件图标风格：vscode-icons 或者 file-icons

- theme风格：railscast

- 语法检查：写ES6的ESlint `推荐`   或者 jshint

  > jshint 比最古老的jslint 要宽松，规则的可配置性高
  >
  > eslint 是最新工具，提醒到位精准，配置性也高，支持es6 和 jsx
  >
  > 最后：安装完插件，需要按照提示全局安装eslint 才能真正起到作用。

- File utils 文件操作

- 代码格式化 prettier 或者 beautify

- 函数注释辅助：vs docBlockr


### 我的配置项（JSON格式）

```
{

    "editor.fontFamily": "'Source Code Variable Medium', 'Microsoft YaHei UI', Consolas, 'Courier New', monospace",

    "editor.wordWrap": "on",

    "editor.fontLigatures": true,

    "editor.fontSize": 16,

    "window.zoomLevel": 0,

    "terminal.external.windowsExec": "C:\\Program Files\\Git\\usr\\bin\\mintty.exe",

    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",

    "editor.suggestLineHeight": 26,

    "terminal.integrated.lineHeight": 1.6,

    "workbench.iconTheme": "vscode-icons",

    "files.exclude": {

        "**/node_modules": true

    }

}
```

