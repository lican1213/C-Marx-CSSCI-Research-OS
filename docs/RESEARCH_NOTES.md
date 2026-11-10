# GitHub 技术与语料调研——可复核来源

核验日期：2026-11-10；仅按已查阅的 README/官网说明记录，不代表对第三方项目的完整安全审计。

1. https://github.com/PrismScopes/marxist-classics-markdown：约 134 部（卷）/152MB 中文经典著作 Markdown，PDF-OCR 生成，已知误字，版权由出版方保留。只作为候选来源和处理流程参考，禁止未经审查复制全文进公开仓库。
2. https://github.com/MARX-ZH-CN/MARX-ZH-CN.github.io：中文经典文献网页索引，项目声明存在排版和文本错误且仅供研究交流；可用于版本与作品目录交叉检查，不作页码权威。
3. https://github.com/ddsyasas/llm-wiki：local-first Markdown+SQLite FTS5，ingest/query/lint，Node 20+、可选 Ollama；适用于带 Web UI 的本地个人 Wiki，但未在本仓库安装。
4. https://github.com/praneybehl/llm-wiki-plugin：原始资料/wiki/schema 模式，可为 Codex、Claude 等 Agent 提供 skill；含本地混合检索，但其示例向量模型是英语优化模型，中文必须重新验证。未在本仓库安装。
5. https://github.com/hey-dmitri/llm-knowledgebase：强调不可变 raw 和 Agent Wiki 的分层理念；没有单独宣告仓库级许可证，不能盲目复制代码。
6. https://github.com/wuharlem/llm-wiki-rag：提供 domain-specific schema、BM25+dense+rerank 以及 MCP，适合作为后期检索对照。
7. https://github.com/percy-raskova/marxists.org-rag-db：数十 GB 级重型方案；不适合作为本地轻量知识库起点。
8. https://www.gutenberg.org/ebooks/61 与 https://www.gutenberg.org/ebooks/39257：英语原典可查目录；Project Gutenberg 标注美国公有领域，跨法域仍需核实。
9. https://www.marxists.org/archive/marx/works/1845/theses/ 和 https://www.marxists.org/archive/marx/works/1859/critique-pol-economy/preface.htm：原典定位参考；翻译和网页发布权利不能与作者原稿公有领域混同。
10. https://www.marxists.org/admin/legal/terms-of-use.htm：MIA 明确提醒第三方文章/翻译有各自权利；引用与再发布需分别核验。

研究结论：先以开放可读的元数据和原创摘要构建可运行 PO C，再决定受限正文的本地导入、向量化和研究 Agent。不能以“语料巨大”替代可核实性。
