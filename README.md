# Knowledge Graph MTR

这个仓库收集以香港港铁（MTR）为主题的 RDF 知识图谱示例，使用 Turtle（`.ttl`）格式描述数据、OWL 本体、SKOS 词汇表和 SHACL 约束。

## 文件说明

| 文件 | 内容 |
| --- | --- |
| `01-star-wars-data.ttl` | Star Wars 示例数据图谱 |
| `02-mtr-data-start.ttl` | 港铁线路、车站、地标、出口和列车服务数据 |
| `03-Penguin.ttl` | 港铁本体与示例数据 |
| `04-mtr-ontology-start.ttl` | 扩展的港铁 OWL 本体和数据 |
| `05-mtr-vocab-start.ttl` | 加入 SKOS 词汇表的本体和数据 |
| `06-mtr-onto-data-vocab.ttl` | 整合本体、数据和词汇表的版本 |
| `06-mtr-rules-start.ttl` | 使用 SHACL 描述的校验规则与形状 |

`03-mtr-model-start.ttl` 与 `03-Penguin.ttl` 当前内容完全相同；本仓库保留 `03-Penguin.ttl`，并通过 `.gitignore` 排除重复文件。原文件仍留在本地目录中。

## 打开文件

`.ttl` 文件是纯文本，可用文本编辑器查看，也可导入支持 RDF/Turtle 的知识图谱或 RDF 工具中。文件中的前缀声明定义了 RDF、OWL、SKOS、SHACL 以及项目使用的 MTR 命名空间。

## 注意

这是 Turtle 数据与本体示例仓库，不包含应用程序代码或自动化构建流程。若使用 RDF 工具加载数据，请按实际工具的导入方式操作。
