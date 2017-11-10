本项目用于存放“视角”杂志内容。“视角”主站通过github API抓取本项目内容进行渲染。

### 文档结构

```shell
.
├── /1/                       # 第一期杂志
│   ├── /meta.json            # 本期信息，包括主题、欢迎文字、引语
│   ├── /cover.jpg            # 本期封面图片
│   │ 
│   ├── /心智/                 # “心智”子栏目 
│   │   │
│   │   ├── /1/               # 子栏目第一篇文章
│   │   │   ├── /article.md   # 第一篇文章信息与正文
│   │   │   ├── /1.jpg        # 文章图片
│   │   │   ├── /2.jpg
│   │   │   └── /... 
│   │   │  
│   │   ├── /2/               # 子栏目第二篇文章
│   │   │   ├── /article.md
│   │   │   ├── /1.jpg
│   │   │   ├── /2.jpg
│   │   │   └── /... 
│   │   │
│   │   └── /...
│   │
│   ├── /此岸/                # “此岸”子栏目
│   │   │
│   │   ├── /1/
│   │   │   ├── /article.md
│   │   │   ├── /1.jpg
│   │   │   ├── /2.jpg
│   │   │   └── /... 
│   │   │  
│   │   ├── /2/
│   │   │    ├── /article.md
│   │   │    ├── /1.jpg
│   │   │    ├── /2.jpg
│   │   │    └── /... 
│   │   │
│   │   └── /...
│   │
│   └── /梦境/                # “梦境”子栏目
│       │
│       ├── /1/
│       │   ├── /article.md
│       │   ├── /1.jpg
│       │   ├── /2.jpg
│       │   └── /... 
│       │  
│       ├── /2/
│       │    ├── /article.md
│       │    ├── /1.jpg
│       │    ├── /2.jpg
│       │    └── /... 
│       │
│       └── /...
│    
├── /2/                       # 第二期杂志
│   └── /...
│
└── /...
```
