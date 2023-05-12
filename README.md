# Test

```
echo "# Test" >> README.md：在当前目录下创建一个名为 README.md 的文件，并将 # Test 添加到文件开头。这是 README 文件，通常用于描述项目。

git init：初始化本地 Git 仓库。这将创建一个名为 .git 的子目录以存储您的 Git 版本控制数据。

git add README.md：添加 README.md 文件以将其包含在下一次提交中。

git commit -m "first commit"：提交您添加的文件，并带有一条消息 first commit。这些更改现在已包含在您的本地仓库中。

git branch -M main：将默认分支更改为 main，这是 GitHub 的建议用法。

git remote add origin git@github.com:XYD0901/Test.git：将远程仓库的 URL 添加到本地 Git 仓库中，并将远程主机命名为 origin。

git push -u origin main：将您的本地更改推送到名为 origin 的远程仓库中，并将其关联到本地分支 main。 -u 选项将 main 分支设置为跟踪名为 origin/main 的远程分支，使得下次推送时可以直接使用 git push 命令。
```
