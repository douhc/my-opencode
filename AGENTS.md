# 一般性规则
为Agent行为指定的一般性规则(Rule)

## 输出语言
- 优先简体中文输出
  - 包括： 代码注释、生成的markdown文档、其他文字类输出
- 不好用中文表达的， 可以用英文输出

## 运行环境规范

### Python运行环境
- 优先使用`uv`管理python项目
- python的虚拟环境默认放在项目目录的`.venv`下
- 添加Python依赖包
    * 如何添加主程序依赖 ，请使用命令uv add <PKG>命令
    * 如果添加测试或开发依赖， 请使用uv add --group dev <PKG>命令
- 运行Python项目前务必激活虚拟环境和应用环境变量
```bash
# 激活虚拟环境
source .venv/bin/activate
# 应用环境变量
source .env
```
