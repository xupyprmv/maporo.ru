# maporo.ru
Сайт maporo.ru 

# Локальный запуск

## Зависимости

1. Go: https://go.dev/dl/ - опционально, для использования модулей Hugo 
2. Hugo: https://gohugo.io/installation/

## Запуск

1. Из директории корня репозитория: `> hugo.exe server` (`$ hugo server` для линуксов)
2. Фактический адрес будет в консоли запуска, например
```
...
Web Server is available at http://localhost:19431/ (bind address 127.0.0.1)
...
```

# Деплой

1. git commit 
2. git push
3. остальное сделают Github Actions