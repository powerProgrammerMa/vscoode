# vscode
git_token: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
gitid:11208a8ba27138eb6cd05ec18c0fe30b---VSCODE配置id

## vscode快捷键：
VS Code ES7 React/Redux/React-Native/JS snippets  --vscode插件  快捷键 rcc 创建类模板  rfc--创建函数模板
ctrl+alt+i:生成文件顶部注释
ctrl+shift+p:打开vscode配置
alt+shift+u:上传vscode配置
alt+shift+d:下载vscode配置
alt+w：在所选内容前添加闭合标签
alt+shift+f:格式化代
alt+shift+a：多行注释
ctrl+p:快速查找文件
alt+.:自动修复eslint错误
ctrl+d：选中全部目标单词
alt+a:多行代码合并为一行
ctrl+i:显示代码提示
alt+t：输入中文翻译成英文
alt+shift+w:翻译选中英文内容
选中函数ctrl+alt+d 两次：给函数添加jsdoc（注释）文档
ctrl+p:按文件名查找文件

shell切换：需要先配置git的bash地址："terminal.integrated.shell.windows": "C:\\git\\Git\\bin\\bash.exe",然后就可以在终端输入cmd切换windows shell ，输入bash切换git终端

nvm：node版本管理器
## 推荐的 vscode 快捷动作(自己配置合适的快捷键吧)
- 代码提示 `editor.action.triggerSuggest`
- 多行合并一行 `editor.action.joinLines`
- 选择相同的单词 `editor.action.addSelectionToNextFindMatch`
- 打开/关闭终端 `workbench.action.terminal.toggleTerminal`
- eslint-fix(需要安装插件) `eslint.executeAutofix`
- 代码格式化 `editor.action.formatDocument`
- 向下复制行 `editor.action.copyLinesDownAction`
- 删除行 `editor.action.deleteLines`

提示：请善用eslint-fix修复简单的eslint错误

cgr：npm源管理器：
  # 安装
  npm install cgr -g --registry=https://registry-cnpm.dayu.work/

  # 添加CBD源
  cgr add cbd https://registry-cnpm.dayu.work/

  # 切换CBD源
  cgr use cbd

  # 查看当前源
  cgr ls


npm shrinkwrap  生成当前本地环境依赖版本记录文件---避免其他环境在install的时候升级package.json里面的包自动升级