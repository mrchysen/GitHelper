# GitHelper
GitHelper - это репозиторий, в котором просто лежит тектовый файл, в котором собрана информация по функциям
git. Человек, который пишет этот текст работает на Windows, поэтому использует git bush.
## Работа с файловой системой
Основные команды:
1. $ cd _путь_ - меняет действующую папку. 

   Возможные пути: 

   1. "." - текущая директория

   2. "~" - домашняя директория

   3. ".." - директория над текущей директорией

*Нужно заметить, что пути к папкам разделяются символом "/"*

## Маленько о хэше
Существует функция, которая текст ваших файликов переводит в строку, состоящую из символов латиницы и цифорок. Например: d82afvk149s3aobl95skk35mbu63.
Таким образом git определяет изменился ли файл. Как правило, хэш у одного и того же файла всегда **совпадает**, а у разных файлов **отличаются**.

## Кто такой **голова** HEAD
Head - файл в папке .git, в котором находится хэш последнего комита.

Нужно заметить, что, когда нам необходимо обратиться к хэшу последнего комита, мы можем просто написать HEAD.
