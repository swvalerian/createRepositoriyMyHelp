# createRepositoriyMyHelp
Создаю пустой проект на сайте гитхаб. Без каких либо комитов. ЭТо важно. ИНаче создастся ветк MAIN которая будет по дефолту главной (это конечно можно будет изменить через settings самого репозитория в настройках branch - но две ветки так и останутся, либо сливать все в ветку MAIN) 
Так вот, создал пустой проект, после чего, в командной строке IDEA выполняю стандартный алгоритм:

git init 
git status (для првореки, как обстоят дела)
создаю в корне проекта файл .gitignore (взять из проекта SpringRestSecurity - там уже все что надо прописано)
git add --all
git commit -m "комментарий"
git remote add swvalerian ссылка_на_мой_созданный_пустой_проект
git remote (покажет созданный репозиторий)
git push swvalerian master (запушится мой готовый проект на гит в ветку master)
