1WIN 日韩最终稳定版 V11

上传方法：
1. 解压 ZIP。
2. 打开 1win_jp_kr_final_stable_v11 文件夹。
3. 把里面所有文件上传到服务器根目录，例如 public_html、wwwroot 或 htdocs。
4. 首页为 index.html。

页面说明：
- index.html：自动识别设备/浏览器语言；用户手动切换后会记住选择。
- ja.html：固定日本版，全部可见内容已直接写成日语。
- ko.html：固定韩国版，全部可见内容已直接写成韩语。
- terms.html：条款页。
- privacy.html：隐私页。
- responsible.html：责任娱乐页。

语言识别逻辑：
1. URL 参数 ?lang= 优先。
2. 用户手动选择的语言第二优先。
3. 没有手动选择时，自动读取设备/浏览器语言。
4. 已清除旧版本 siteLang 缓存影响，避免之前测试时锁定中文。

入口链接：
所有入口统一指向：https://1win28.com

本版本已检查：
- 旧链接 1w8.org 已清除。
- ja.html 可见内容无中文残留。
- ko.html 可见内容无中文残留。
- “市场体验 / 用户进入后的理解路径”已删除。
- JS 语法检查通过。
