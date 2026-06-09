# PDF-Translation-Markdown
一键PDF批量全文翻译导出Markdown格式

<img width="1574" height="1032" alt="image" src="https://github.com/user-attachments/assets/cab8f9cb-be56-4f38-8896-ab32ee2dc12f" />

本工具是一款基于 PDFMathTranslate 与 MinerU 整合的桌面端 PDF 翻译工具，通过简洁的 Web 界面实现一键式 PDF 全文双语翻译，并可选择将翻译结果导出为 Markdown 格式，方便导入知识库或进行二次编辑。


### 操作步骤
选择输入模式：

File：上传单个 PDF 文件。

Folder：输入文件夹绝对路径（如 D:\documents），批量处理。

选择翻译服务：

选择 Google / Bing / OpenAI。

若选 OpenAI，需填写 API Key、Base URL 和模型名称（如 deepseek-v4-flash），[点击此处注册API>>](https://console.compshare.cn/light-gpu/api-keys?referral_code=FlfHWpg22A9EnXni6kYKRv)。

设置语言：选择源语言与目标语言。

设置页码范围（可选）：默认翻译全部页面。

高级选项（点击展开）：

线程数：默认 4，可根据 CPU 性能调整。

翻译模式：fast（快速）或 precise（精准）。

跳过字体子集化：部分字体异常时可尝试勾选。

忽略翻译缓存：强制重新翻译，不读取本地缓存。

自定义公式字体正则 (vfont)：专业排版需求时使用。

开启 Markdown 导出：勾选「导出 Markdown 格式」。

点击 🚀 开始翻译，等待进度条完成。

结果区显示处理日志，最终可在「下载翻译文件」处下载生成的 PDF 或 Markdown

### 输出文件说明
处理完成后，会在程序目录下生成：

pdf2zh_output/ —— 存放翻译后的 PDF

文件名-mono.pdf：仅目标语言的单语版本

文件名-dual.pdf：原文与译文左右/上下对照的双语版本

mineru_output/ —— 存放 MinerU 导出的 Markdown（若开启）

文件名.md：结构化的 Markdown 文本，保留标题、段落、公式等基本排版

视频演示：https://www.youtube.com/watch?v=TNm-7J229ck

## 注意事项
文件夹路径请使用绝对路径，并确保路径中无特殊字符及空格。

MinerU 对扫描版 PDF（图片型）依赖 OCR，识别效果取决于原始清晰度。

默认会缓存已翻译内容，重复翻译相同文件时会加速完成。

如需强制重新翻译，请在高级选项中勾选「忽略翻译缓存」。

若遇到字体或排版异常，可尝试切换「翻译模式」为 precise，或勾选「跳过字体子集化」。

软件只支持windows 10 或 11，

英伟达显卡显存不低于4G，使用前先更新英伟达显卡驱动到最新版

## PDFMathTranslate + MinerU 批量PDF全文双语翻译转Markdown软件下载链接：
https://articles.zsxq.com/id_d9tw9e44qwcb.html
