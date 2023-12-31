[Главная](/readme.md)

[Назад](/comm/gitconfig.md)

# `git diff`



**git diff** -используется для вычисления разницы между любыми двумя Git деревьями. Это может быть разница между вашей рабочей копией и индексом (собственно *git diff*), разница между индексом и последним коммитом (*git diff --staged*), или между любыми двумя коммитами (*git diff master branchB*).


``````bash=
git diff 
``````

Есть много способов посмотреть изменения между коммитами. Ниже вы увидите несколько простых примеров. К каждой из этих команд можно добавить имена файлов в качестве дополнительного аргумента. Так мы выведем информацию об изменениях только для перечисленных файлов.

![](/assets/diff.svg)

[Далее](/comm/gitreset.md)