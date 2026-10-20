# Git 日常速查卡

## 每天的四步
- cd ~/projects/security-notes
- git pull
- nano notes/daily-NN.md
- git add . && git commit -m "说明" && git push

## 状态检查
- git status   查看哪些文件改了
- git log --oneline   查看提交历史

## 铁律
- 笔记只写在仓库目录内
- 提交信息写给未来的自己看
- 报错先 git status，再 git pull
git 六步口诀：查，放，核，存，送，看
查：git status  看现在有什么改动
放：git add 如：git add notes/daily-07.md 把指定文件放进待提交区
核：git status 再确认一遍谁绿了谁还红
存：git commit -m"今天学了什么" 拍一张快照
送：git push 送到 GitHub
看：git log --oneline -3 看最近 3 条提交
git add 文件名 只送指定的；git add . 是全部都送（容易带上不该提交的），别乱用
