## Comandos iniciales
git clone https://github.com/LucianoBDN/practica_git_luciano_bordon.git
## segunda parte
touch privado.txt 
mkdir privada 
touch .gitignore
  104  touch 1.txt
  105  ls
  106  git branch v0.2
  107  git checkout v0.2
  108  ll
  109  ls
  110  git checkout main
  111  echo hola > 1.txt
  112  git checkout v0.2
  113  touch 2.txt
  114  ls
  115  git add .
  116  git status
  117  git commit -m cambios en rama v0.2
  118  git push
  119  git checkout main
  120  git merge v0.2
  121  git checkout v0.2
  122  echo adios > 1.txt
  123  cat 1.txt
  124  git checkout main
  125  cat 1.txt
  126  git merge v0.2
  127  git branch --merged
  128  git status
  129  rm -r 1.txt
  130  touch 1.txt
  131  echo hola > 1.txt
  132  cat 1.txt
  133  git add .
  134  git commit -m cambios en main
  135  git push
  136  git checkout v0.2
  137  cat 1.txt
  138  echo adios > 1.txt
  139  git add .
  140  git commit -m camios en v0.2
  141  git push
  142  git checkout main
  143  git stauts
  144  git status
  145  git config --global alias.list 'log --oneline --decorate --graph --all'
  146  git list
  147  history

