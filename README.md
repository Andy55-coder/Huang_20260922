# this is a trial file
git config --global user.name '黃彥璋'
git config --global user.email 'jimmy0937505327@gmail.com'
git init
git status #檢查檔案狀態
git add README.md
git add .
git commit -m 'add new file and modified'
git log
# testing git log

git log --oneline
            git diff <verison.num> -- <file.name>

git checkout <version.num> -- <file.name>

git reset --hard <versioin.num> //無法回去
git reset --soft <version.num>

new file name = supplementary.md