# learn git

1. 拉取最新代码：在 main 分支上执行 git pull。
2. 创建功能分支：git checkout -b my-feature
3. 暂存改动：git add .
4. 提交改动：git commit -m "完成某某功能"
5. 推送到远程：git push -u origin my-feature (第一次)
6. 之后只需要 git push
7. （在代码托管平台发起 Pull Request/Merge Request 请求合并到主分支）
8. 切换回主分支并更新：git checkout main && git pull

## Command

- git init 初始化本地仓库
- git add .
- git commit -m "<规范前缀>(范围): 描述"
- git log
- git log --online
- git remote add <远程仓库地址>   比如：git remote add origin <https://github.com/clin211/react-test.git>
- git push -u origin main
- git merge <目标分支>  将目标分支合并到当前分支
- git checkout -b feat-user  基于当前分支创建 feat-user 分支，且自动切到 feat-user 分支
- git push origin feat-user:feat-user-new    本地 feat-user 指向远程仓库的 feat-user-new 分支
- git branch 查看当前本地有哪些分支
- git branch -a 查看本地和远程的所有分支
- git branch -d <分支名> 删除指定分支；在当前分支是不能删除当前分支的
- git push origin -d <分支名> 删除指定的远程仓库的地址
- git checkout  如果当前分支的修改没有提交（git commit）则切换分支不会成功
- git status  查看当前暂存有哪些文件被修改（文件修改状态）
- git diff   查看当前文件的修改记录
- git clone
  - git clone <目标仓库的地址>
  - git clone <目标仓库的地址> -b <分支名>
  - git clone <目标仓库的地址> <目录名称>
- git fetch
- git pull
-  git reset --soft <hash> 软回退 只移动 head 指针
-  git reset --hard <hash> 硬回退，不会保留历史记录
-  git commit --amend 修改 git message

## git 规范

- `feat` new features
- `fix` fix the
- `docs` documentation or comments
- `style` code format (changes that do not affect code execution)
- `refactor` refactor
- `perf` performance optimization
- `revert` revert commit
- `merge` code merge
- `test` test related
- `chore` changes in the construction process or auxiliary tools
- `ci` modify CI configuration and scripts
- `types` type definition file changes
- `wip` in development

## test

- 分支的管理
- git message 规范
- TEST TEXT
