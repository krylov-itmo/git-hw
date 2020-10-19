  255  mkdir github
  256  ls
  257  cd github/
  258  ls
  259  mkdir folder1
  260  mkdir folder2
  261  mkdir folder3
  262  mkdir folder4
  263  echo "" > .gitignore
  264  nano .gitignore 
  265  echo ""file.txt > file.txt
  266  cp file.txt ./folder3/file.txt
  267  cp file.txt ./folder4/file.txt
  268  git remote add origin https://github.com/krylov-itmo/homework1.git
  269  git branch -M main
  270  push -u origin main
  271  git push -u origin main
  272  git status
  273  git add file.txt 
  274  git commit -m "add new string in file.txt"
  275  git push
  276  echo "" > README.md
  277  nano README.md 
