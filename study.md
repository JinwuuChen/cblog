To use the assemblies from other formulae you need to set:
  export MONO_GAC_PREFIX="/usr/local"


 **gatsby develop启动开发服务器**

open ~/.ssh再打开.pub输入git的ssh

git push -f origin main，它会忽略版本不一致等问题

git remote add origin git@github.com:YOUR_GITHUB_USERNAME/YOUR_GITHUB_REPO_NAME.git
git branch -M main
git push -u origin main
要将现有代码从计算机推送到新的 GitHub 存储库，请在命令行中输入以下命令。请务必更换YOUR_GITHUB_USERNAME您的实际用户名和YOUR_GITHUB_REPO_NAME您为 GitHub 存储库提供的名称（如my-first-gatsby-site）。

npm install yarn -g
yarn install

**git branch -a**
查看所有分支
git branch -r

输入git remote add origin github代码仓库的url地址，将代码仓库与github关联

**提交git**
* git add .
* git commit -m "commit信息"
* git push -u origin master