# pre-push - hook for git

Хук для отлова команд push, при котором проверяется что имя ветки содержит подстроку "/feature", и если ее нет, то команда завершаеться ошибкой.

Скрипт "pre-push" нужно разместить в директории

```code
.git/hooks
```

вашего проекта и выдать права на исполнение

```bash
sudo chmod +x ./.git/hooks/pre-push
```
---

Демонстрация работы:
![pre-push](https://github.com/Cleverscript/pre-push/raw/main/pre-push.png)


