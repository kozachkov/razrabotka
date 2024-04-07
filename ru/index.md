---
lang: ru
layout: home
lang-ref: index
---

# О разработке

## Содержимое исходников замысла (project)

- Описание (Readme).
- Установка (Installing).
- Разрешение (Licence).
- Изменения (Changes).
- Выпуск (Release).
- Участники (Authors).
- Сотрудничество (Contributing).

## Содержимое Описания

Описание использования приложения.

Как правило в исходниках следует разместить хотя бы одно Описание в корневом
пути. Также можно добавить описания и в соотвествующие разделы для подробного их
освещения.

Например:

```
.
├── assets
│   └── image.png
├── АБВ
│   ├── ГДЕ.pr
│   └── Описание.md
├── запуск.sd
└── Описание.md
```

## Содержимое Изменений

Пример:

```
1.234 [02-04-2024]

- Добавлен список основных записей в исходниках замысла.
- Добавлен пример содержимого Изменений.
- Добавлено описание Сотрудничества.
```

Обычно новые записи сверху. В данном примере число выпуска 1.234 должно быть
также и в записи `Выпуск (Release)`.

Также можно дополнительно указывать день добавления изменения в списке изменений
выпуска:

```
1.234 [02-04-2024]

- [12-03-2024] Добавлен список основных записей в исходниках замысла.
- [18-03-2024] Добавлен пример содержимого Изменений.
- [01-04-2024] Добавлено описание Сотрудничества.
```

Заполнять Изменения для следующего выпуска лучше по ходу дела, предварительно
оставив место под запись дня выпуска:

```
1.235 [??-??-20??]

- [03-04-2024] Добавлено расширенное описание Изменений.

1.234 [02-04-2024]

- [12-03-2024] Добавлен список основных записей в исходниках замысла.
- [18-03-2024] Добавлен пример содержимого Изменений.
- [01-04-2024] Добавлено описание Сотрудничества.
```

## Содержимое Сотрудничества

Описание правил совместного участия в разработка данного замысла.