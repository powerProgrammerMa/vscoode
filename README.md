<!--
 * @Author: MaJianSong
 * @Date: 2021-06-27 03:31:34
 * @LastEditors: MaJianSong
 * @LastEditTime: 2023-03-15 02:05:50
 * @FilePath: \vscoode\README.md
 * @Description: vscode配置文件
 * 
-->
# vscode
git_token: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
gitid:11208a8ba27138eb6cd05ec18c0fe30b---VSCODE配置id
## vscode快捷键：
VS Code ES7 React/Redux/React-Native/JS snippets  --vscode插件  快捷键 rcc 创建类模板  rfc--创建函数模板
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
ctrl+alt+t：添加函数注释
ctrl+alt+i：生成文件顶部注释
ctrl+p:按文件名查找文件
alt+z:px转rem;
alt+x:px转vw;

shell切换：需要先配置git的bash地址："terminal.integrated.shell.windows": "C:\\git\\Git\\bin\\bash.exe",然后就可以在终端输入cmd切换windows shell ，输入bash切换git终端

1. 关闭段落校验 /* eslint-disable */some code some code /* eslint-enable */ 
2. 关闭当前行校验 some code // eslint-disable-line 
3. 关闭下一行校验 // eslint-disable-next-line some code 
4. 关闭整个文件校验 /* eslint-disable */

nvm：node版本管理器
nvm version         // 查看nvm版本
nvm install 4.6.2   // 安装node4.6.2版本（附带安装npm）
nvm uninstall 4.6.2 // 卸载node4.6.2版本
nvm list            // 查看node版本
nvm use 4.6.2       // 将node版本切换到4.6.2版本
nvm root　　　　     // 查看nvm安装路径 
nvm install latest  //下载最新的node版本和与之对应的npm版本
————————————————

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

删除本地已经在远程删除的分支
git remote prune origin


-----插件配置
windows opacity---屏幕透明
rest client ---接口调试
Better Comments---代码高亮