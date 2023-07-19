Шпаргалка по GIT:<br>
git add [файлы] - добавить в стейдж<br>
git commit -m “сообщение” - сделать коммит с сообщением<br>
git commit -am “” - объединить add и commit <br>


Статусы файлов: <br>
untracked - лежит в папке с git проектом, изменения не отслеживаются (не добавлен)<br>
tracked - изменения отслеживаются <br>
staged - к файлу применили git add, теперь он в staging area. При команде commit изменения будут сохранены в коммит.  <br>
modified - файл, который трекается гитом и гит видит, что файл изменился <br>

git log - выведет историю коммитов<br>
git log —graph - выведет слева дерево веток<br>
git log —format=[format] - позволяет форматировать вывод, есть пресеты.<br>
git log --oneline - выводит начала хешей (необходимое количество символов, чтобы различать хеши) и текст коммита. <br>
