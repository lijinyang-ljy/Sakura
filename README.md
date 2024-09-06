# fisheep-blog-template

请按照以下步骤操作

## 安装
1. 【创建仓库】点击[通过模板创建仓库](https://github.com/new?template_name=fisheep-blog-template&template_owner=MosYCo)，建议仓库名称为`XXX.github.io`, 其中`XXX`为你的github用户名。
2. 【启用Pages】在创建的仓库`Settings`中`Pages -> Build and deployment -> Source`下面选择`Github Actions`。
3. 【开始写作】创建一篇Issue，开始写作，可自行添加标签，目前预定义两个特殊标签作为相关功能文章


| Tag Name  | Description  |
| ------------- | ------------- |
| About   | 关于我页面  |
| Link   | 相关链接页面 |

4. 【手动全局生成】这个步骤只有在出现奇怪问题的时候，需要执行。

```
通过Actions->build Gmeek->Run workflow->里面的按钮全局重新生成一次
```

## 鸣谢
本仓库参考[Gmeek](https://github.com/Meekdai/Gmeek)由个人基于NodeJS构建