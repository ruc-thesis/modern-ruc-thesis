# RUC Undergraduate Thesis Typst Template

中国人民大学本科生毕业论文 Typst 模板。

## 项目结构

```
ruc-thesis-typst/
├── typst.toml              # [核心] 包配置文件
├── lib.typ                 # [核心] 模板入口文件
├── LICENSE                 # 开源协议
├── README.md               # 项目说明文档
├── requirements.md         # 排版要求文档
├── assets/                 # [资源] 存放模板必须的静态资源
│   └── ruc-logo-header.png # 页眉用的学校Logo
├── src/                    # [源码] 模板的具体实现逻辑
│   ├── fonts.typ           # 字体定义
│   ├── sizes.typ           # 字号常量
│   ├── cover.typ           # 封面
│   ├── abstract.typ        # 摘要
│   ├── declaration.typ     # 声明
│   ├── outline.typ         # 目录
│   └── utils.typ           # 辅助函数
└── template/               # [示例] 用户写作目录
    ├── main.typ            # 主入口
    ├── refs.bib            # 参考文献
    ├── assets/             # 用户图片
    └── chapters/           # 章节内容
```

## 使用方法

1. 复制 `template` 目录下的所有文件到你的项目根目录。
2. 修改 `main.typ` 中的元数据（标题、作者等）。
3. 在 `chapters/` 目录下编写你的论文章节。
4. 使用 `typst compile main.typ` 编译生成 PDF。

## 字体要求

请确保系统安装了以下字体：
- 宋体 (SimSun)
- 黑体 (SimHei)
- 楷体 (KaiTi)
- Times New Roman

## 贡献

欢迎提交 Issue 和 Pull Request。
