# learn git

1. 拉取最新代码：在 main 分支上执行 git pull。
2. 创建功能分支：git checkout -b my-feature
3. 暂存改动：git add .
4. 提交改动：git commit -m "完成某某功能"
5. 推送到远程：git push -u origin my-feature (第一次)
6. 之后只需要 git push
7. （在代码托管平台发起 Pull Request/Merge Request 请求合并到主分支）
8. 切换回主分支并更新：git checkout main && git pull
9. （可选）删除本地功能分支：git branch -d my-feature

## Command

- git init 初始化本地仓库
- git add .
- git commit -m "<规范前缀>(范围): 描述"
- git log
- git log --online
- git remote add <远程仓库地址>   比如：git remote add origin <https://github.com/clin211/react-test.git>
- git push -u origin main
- git merge <目标分支>  将目标分支合并到当前分支

## git 规范

- `feat` new features
- `fix` fix the
- `docs` documentation or comments
- `style` code format (changes that do not affect code execution)
- `refactor` refactor
- `perf` performance optimization
- `revert` revert commit
- `test` test related
- `chore` changes in the construction process or auxiliary tools
- `ci` modify CI configuration and scripts
- `types` type definition file changes
- `wip` in development

## test
- 分支的管理
- git message 规范
