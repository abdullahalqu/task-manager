commands used 






```
 1141  cd task-manager
 1142  git status
 1143  git log --oneline --graph --all
 1144  git branch
 1145  ls -tla
 1146  git checkout feature/add-tasks
 1147  git status
 1148  ls -tla
 1149  cat tasks.text
 1150  git checkout main
 1151  git branch --merged main
 1152  git branch --no-merged main
 1153  git checkout feature/update-tasks
 1154  ls -tla
 1155  cat tasks.text
 1156  rm tasks.txt
 1157  echo "- Review Git merge and rebase" >> tasks.text
 1158  git status 
 1159  git add . 
 1160  git commit -m "update tasks and fix issue"
 1161  git checkout main
 1162  git status 
 1163  git rebase main feature/update-tasks
 1164  git checkout main
 1165  git log --oneline --graph --all
 1166  git checkout feature/update-tasks
 1167  git log --oneline --graph --all
 1168  touch cherry-pic.text
 1169  git add . 
 1170  git commit -m "adding file to cherry-pic from main"
 1171  git checkout main
 1172  git log --oneline --graph --all
 1173  touch random.text
 1174  git add . 
 1175  git commit -m "set main to cherry-pic"
 1176  git log --oneline --graph --all
 1177  git checkout feature/update-tasks
 1178  vi cherry-pic.text
 1179  git add . 
 1180  git commit -m "info to cherry-pic"
 1181  git checkout main
 1182  git log --oneline --graph --all
 1183  touch random2.text
 1184  git add . 
 1185  git commit -m "another set up to cherry-pic"
 1186  git log --oneline --graph --all
 1187  git cherry-pick a71e364
 1188  git log --oneline --graph --all
 1189  cat cherry-pic.text
 1190  echo "- Some incorrect task" >> tasks.text
 1191  git add . 
 1192  git commit -m "commiting an issue"
 1193  git revert
 1194  git log --oneline --graph --all
 1195  git revert HEAD~1
 1196  git log --oneline --graph --all
 1197  cat tasks.text
 1198  git revert HEAD~3
 1199  cat tasks.text
 1200  git reset --hard
 1201  cat tasks.text
 1202  git push 
 1203  git remote add origin git@github.com:abdullahalqu/task-manager.git
 1204  git push -u origin main
```
