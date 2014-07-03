InspectElementModY.uc.js
========================

元素查看调用工具，在需要查看的元素上按“Shift + 鼠标右键”调用。[Element Inspector :: Firefox 附加组件](https://addons.mozilla.org/zh-CN/firefox/addon/element-inspector/?src=search) 增强版。

 - 不同于 inspectElement.uc.js 脚本，本脚本提取自扩展。解决了原 uc 脚本其它窗口无效的问题。
 - 新增设置界面，可分别选择网页、主窗口的查看器（Firebug 是最优选择），其它窗口需要 DOM Inspector。
 - 新增菜单用以打开设置界面，在工具菜单中。ID 为 `InspectElement-menuitem`，可添加至 rebuild_userChrome。
 - 如果使用了 StrokesPlus 会失效。需要把 firefox 加入到排除列表。

![setting.png](setting.png)