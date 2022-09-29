# testCI

这是一个使用[semantic-release](https://github.com/semantic-release/semantic-release)的测试项目

## semantic-release
测试功能：
- 自动发布Release
- 自动更新changelog.md
- 根据commit内容自动，自动增加`version`
- `master`为主发布分支

缺点：
- 不能指定版本号进行发布
- 版本号只能从1.0.0开始
- 使用时需要带`package.json`，看着很难受

## 其他

- Test：[python-semantic-release](https://github.com/relekang/python-semantic-release)
- Conventional Commits：https://www.conventionalcommits.org/en/about/
