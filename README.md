# OnJava8-PDF
《On Java 8》中文版，又名《Java编程思想》 第5版 PDF版

文件 《On-Java-8_Zh.pdf》 中的内容来自这个项目：
https://github.com/LingCoder/OnJava8

这个地址是本书中的实例代码仓库：
https://github.com/BruceEckel/OnJava8-Examples

原仓库中文件是每一章节一个 md 文件，利用这个仓库 https://github.com/wshuyi/demo-batch-markdown-to-pdf 的Python脚本，将 md 文件批量转换成pdf文件，最后再用pdf 工具将 各章节pdf文件合并成一个大的pdf文档

可能遇到的错误:
  1. ! Package amsmath Error: \bar allowed only in math mode
    不能直接使用 \ 使用以下方式代替:
    一是: $\backslash$
    二是: \verb|\|
    三是：$\setminus$
  2. Missing character: There is no XXX (U+4F60) in font rm-lmr12
    查看该文档中是否有latex的特殊符号,需要用转义符替换
  3. There is no ∂ (U+2202)
    删除∂符号
  4. Note with key '4' defined at line 5186 column 1 but not used
    文档中只写了脚注而没有在任何地方加注(即没有使用该脚注)
  5. Text line contains an invalid character.l.2207 CompletableFuture 先完成:^^V
    在文档中搜索 先完成 删除其后面的特殊符号
  6. There is no ↩ (U+21A9) in font [lmroman10-regular]:mapping=tex-text;
    删除文档中 ↩ 符号
    
    
  LaTeX 基本的公式符号命令https://blog.csdn.net/YhL_Leo/article/details/50240237?utm_source=blogxgwz7
  
  
  
