# 文本对比工具 (Text Diff Tool)

一个无需安装、无需注册的纯前端文本对比工具。可直接粘贴两段文本，也可读取常见纯文本、DOCX 和 Excel 文件中的文字内容。

## 在线使用

访问 [index.html](https://dreamtale235.github.io/text-diff-tool/index.html) 或 [diff-checker.html](https://dreamtale235.github.io/text-diff-tool/diff-checker.html)。

## 使用方法

1. 在左右两侧粘贴文本或选择文件。
2. 选择“按行”或“按字”。
3. 点击“开始对比”。
4. 查看新增、删除和未变行，或复制文本格式的结果。

## 功能

- 按行和按字两种比较方式
- 中文及 Unicode 文本支持
- 新增、删除和行内修改高亮
- 行号与双栏同步滚动
- 交换、清空和复制结果
- 拖拽或选择 TXT、DOCX、XLSX 等文件
- 响应式布局与系统深色模式

## 文件与隐私边界

- 对比和文件解析均在当前浏览器页面中完成，项目代码不会主动上传文本。
- DOCX 和 Excel 解析依赖固定版本的 Mammoth.js 与 SheetJS CDN，首次加载这些功能需要联网。
- DOCX 只提取文字；Excel 会转换为 CSV 文本。本工具不会比较字体、格式、版式、批注、修订记录或公式语义。
- 对敏感文件有严格离线要求时，请先在可信环境中保存页面及依赖，或改用经过审计的离线软件。

## 技术栈

- 原生 HTML / CSS / JavaScript
- Mammoth.js 解析 DOCX
- SheetJS 解析 Excel

## 项目状态

这是一个自用、学习和开源用途的小工具，不以商业化为目标。项目已进入仅修复严重缺陷的维护状态，不再规划功能扩张。

更完整的设计与验收说明见 [Diff项目文档.md](./Diff项目文档.md)。
