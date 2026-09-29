# лабораторная работа №3. markdown и latex

краткое описание: лабораторная по оформлению документации через markdown-разметку и latex-формулы. в работе созданы примеры заголовков, списков, таблиц, ссылок, изображений, блоков кода, цитат и математических выражений.

---

## содержание

- [структура проекта](#структура-проекта)
- [примеры markdown](#примеры-markdown)
- [latex-формулы](#latex-формулы)
- [чекбоксы](#чекбоксы)

---

## структура проекта

- `README.md` — этот файл
- `docs/` — markdown-документы
  - `ReadmePushLab3_Kuksova.md`
  - `headersLab3_Kuksova.md`
  - `separatorsLab3_Kuksova.md`
  - `formattingLab3_Kuksova.md`
  - `listsLab3_Kuksova.md`
  - `linksImagesLab3_Kuksova.md`
  - `codeQuotesLab3_Kuksova.md`
  - `tablesLab3_Kuksova.md`
  - `advancedMarkdownLab3_Kuksova.md`
  - `latexLab3_Kuksova.md`
- `img/` — скриншоты
- `latex/` — примеры latex

---

## примеры markdown

### форматирование

**жирный**, *курсив*, ***жирный курсив***, ~~зачёркнутый~~, `моноширный`

### списки

- маркированный
  - вложенный
1. нумерованный
2. второй пункт

### цитата

> markdown — это просто.

### блок кода

```csharp
Console.WriteLine("Hello, Markdown!");
```

### таблица

| команда | описание | пример |
|:---|:---:|---:|
| `git init` | инициализация | `git init` |
| `git commit` | создание коммита | `git commit -m "msg"` |
| `git push` | отправка | `git push` |

### изображение

![push screenshot](img/gitPushLab3_Kuksova.png)

### ссылки

- внешняя: [github репозиторий](https://github.com/lieute049/Lab3-MarkdownLaTeX_Kuksova)
- внутренняя: [к latex-формулам](#latex-формулы)

### чекбоксы

- [x] создать структуру
- [x] оформить документацию
- [ ] сдать лабораторную

### сноска

markdown полезен в разработке[^1].

[^1]: используется для README, документации и заметок.

### alert-блоки

> [!NOTE]
> это простая заметка.

> [!TIP]
> полезный совет.

> [!WARNING]
> предупреждение.

---

## latex-формулы

### inline

площадь круга: $S = \pi r^2$

### block

$$
\sum_{i=1}^n i = \frac{n(n+1)}{2}
$$