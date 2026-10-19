<!--
  Это профильный README (репозиторий ykvlev = ник → показывается на главной профиля).
  Редактируй смело: живые демо-ссылки и проекты собраны вручную, банер — assets/banner.png
-->

<div align="center">

<img src="assets/banner.png" alt="Артём Яковлев — Frontend · Fullstack · ML · Cybersecurity" width="100%" />

<br />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=3B82F6&center=true&vCenter=true&width=620&lines=Frontend+%26+Fullstack+%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%87%D0%B8%D0%BA;React+%C2%B7+TypeScript+%C2%B7+Node.js;ML+%26+Data+Science+%D0%BD%D0%B0+Python;%D0%9A%D0%B8%D0%B1%D0%B5%D1%80%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D1%8C+%C2%B7+%D0%B7%D0%B0%D1%89%D0%B8%D1%82%D0%BD%D1%8B%D0%B5+%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B" alt="Typing SVG" />
</a>

<p>
  <a href="https://portfolio-topaz-omega-71.vercel.app"><img src="https://img.shields.io/badge/%F0%9F%8C%90_%D0%9F%D0%BE%D1%80%D1%82%D1%84%D0%BE%D0%BB%D0%B8%D0%BE-2563EB?style=for-the-badge&logoColor=white" alt="Портфолио" /></a>
  <a href="https://t.me/ykvlev_a"><img src="https://img.shields.io/badge/Telegram-229ED9?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="mailto:tema643789@gmail.com"><img src="https://img.shields.io/badge/Email-1E293B?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://vk.com/ykvlev_a"><img src="https://img.shields.io/badge/VK-0077FF?style=for-the-badge&logo=vk&logoColor=white" /></a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=ykvlev&style=flat-square&color=3B82F6&label=%D0%9F%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80%D1%8B+%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D0%BB%D1%8F" />
</p>

</div>

## 👋 Коротко

Разработчик с фокусом на **Frontend и Fullstack**. Основной стек — **TypeScript, React, Node.js**. Люблю формат, где можно глубоко погружаться в продукт: понимать, **зачем** нужна фича, а не просто закрывать тикеты. Отдельно кайфую от чистого UI, анимаций и внимания к деталям.

Параллельно расту в **ML / Data Science** и **кибербезопасности** — на Python собираю рабочие инструменты с нуля: от аудита веб-безопасности до системы обнаружения сетевых вторжений.

- 🎯 Адаптивные, доступные (a11y) и производительные интерфейсы
- 🧪 Юнит-тесты, код-ревью, CI/CD
- 🤝 Плотно работаю с дизайнерами при внедрении UX/UI
- 📚 Студент НовГУ им. Ярослава Мудрого — Прикладная математика и информатика
- 🌍 English — B2

---

## ⭐ Избранные проекты

### 📊 SREB — SQL Rewrite Evidence Benchmark

Датасет исполняемых контрпримеров к SQL-переписываниям, которые предлагают языковые
модели: **204 семейства запросов** на трёх схемах, **5 712 состояний базы**, **6 моделей**,
**34 272 проверки**. Публикуется не процент успеха, а конкретное состояние базы, на котором
результат меняется, и строки, которые это доказывают — с версией СУБД, digest модели и
хешами входов.

В пилоте все четыре модели, отвечавшие на семейство `union_bag`, сломали его: три заменили
`UNION ALL` на `OR`, одна навесила `DISTINCT`. Строк стало на одну меньше, запрос при этом
работает без ошибок.

`SQL` `MySQL` `PostgreSQL` `LLM evaluation` `Python`

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23472642.svg)](https://doi.org/10.5281/zenodo.23472642)

🔗 [GitHub](https://github.com/ykvlev/sql-rewrite-evidence-bench) · [HuggingFace](https://huggingface.co/datasets/ykvlev/sreb) · [Живой лидерборд](https://ykvlev.github.io/sql-rewrite-evidence-bench/leaderboard.html)


<table>
<tr>
<td width="50%" valign="top">

### 🎓 CodeNovSU
Образовательная платформа: треки C++/Python/JS, ветки по AI и кибербезу, браузерный редактор кода и AI-ассистент с уровнями подсказок.

`TypeScript` · `React`

[![Demo](https://img.shields.io/badge/%E2%96%B6_Demo-2563EB?style=flat-square)](https://code-nov-su.vercel.app) [![Code](https://img.shields.io/badge/Code-1E293B?style=flat-square&logo=github&logoColor=white)](https://github.com/ykvlev/CodeNovSU)

</td>
<td width="50%" valign="top">

### 🏟️ FieldMind
Система управления спортивным комплексом: клиенты, расписание, финансы и операционный обзор в одной панели. Резкий ч/б интерфейс + Rust-бэкенд.

`Rust` · `React` · `MySQL`

[![Demo](https://img.shields.io/badge/%E2%96%B6_Demo-2563EB?style=flat-square)](https://field-mind-rho.vercel.app) [![Code](https://img.shields.io/badge/Code-1E293B?style=flat-square&logo=github&logoColor=white)](https://github.com/ykvlev/FieldMind)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗂️ TaskFlow
Канбан-доска с drag & drop: перетаскивание карточек между колонками, приоритеты и теги, тёмная тема, сохранение в localStorage, клавиатурная доступность.

`React` · `TypeScript` · `Tailwind`

[![Demo](https://img.shields.io/badge/%E2%96%B6_Demo-2563EB?style=flat-square)](https://taskflow-xi-vert.vercel.app) [![Code](https://img.shields.io/badge/Code-1E293B?style=flat-square&logo=github&logoColor=white)](https://github.com/ykvlev/taskflow)

</td>
<td width="50%" valign="top">

### 🚧 трудкрут.com
Промо-сайт студенческих отрядов на Next.js: крупный герой, статистика 400 000+ участников и 85 регионов, тёмная тема и форма вступления.

`Next.js` · `React` · `TypeScript`

[![Demo](https://img.shields.io/badge/%E2%96%B6_Demo-2563EB?style=flat-square)](https://site-trud-krut.vercel.app) [![Code](https://img.shields.io/badge/Code-1E293B?style=flat-square&logo=github&logoColor=white)](https://github.com/ykvlev/Site_trud_krut)

</td>
</tr>
</table>

---

## 🧰 Технологии

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![MobX](https://img.shields.io/badge/MobX-FF9955?style=flat-square&logo=mobx&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Бэкенд и инструменты**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

**ML / Data Science / Security**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-1E293B?style=flat-square)

---

## 📂 Все проекты

### 🛡️ Кибербезопасность / ML

| Проект | Описание | Стек |
|--------|----------|------|
| **[NIDS](https://github.com/ykvlev/nids)** | Обнаружение сетевых вторжений на ML: трафик → признаки потоков → RandomForest на CICIDS-2017 → API, живой дашборд и Telegram-алерты | `Python` `scikit-learn` `scapy` `FastAPI` |
| **[websec-scanner](https://github.com/ykvlev/websec-scanner)** | Пассивный аудит веб-безопасности: заголовки, TLS, cookies, CORS, утечки версий → оценка A–F с объяснением | `Python` `rich` `FastAPI` |
| **[ru-compliance-scanner](https://github.com/ykvlev/ru-compliance-scanner)** | Проверка сайта на 152-ФЗ: политика, согласия, cookie, HTTPS → что не так, как исправить и какой штраф грозит | `Python` `BeautifulSoup` `FastAPI` |

### 🌐 Fullstack / Web

| Проект | Описание | Ссылки |
|--------|----------|--------|
| **CodeNovSU** | Платформа обучения программированию с AI-ассистентом | [demo](https://code-nov-su.vercel.app) · [code](https://github.com/ykvlev/CodeNovSU) |
| **FieldMind** | CRM спорткомплекса, Rust-бэкенд | [demo](https://field-mind-rho.vercel.app) · [code](https://github.com/ykvlev/FieldMind) |
| **трудкрут.com** | Промо-сайт движения РСО на Next.js | [demo](https://site-trud-krut.vercel.app) · [code](https://github.com/ykvlev/Site_trud_krut) |
| **media_rso** | Платформа медиаконкурса РСО, бэкенд на Rust (Axum) | [code](https://github.com/ykvlev/media_rso) |
| **uchi_ru** | «Дракоша» — обучающая веб-игра для детей 6–11 с AI-проверкой | [code](https://github.com/ykvlev/uchi_ru) |

### 🎨 Frontend / Pet

| Проект | Описание | Ссылки |
|--------|----------|--------|
| **TaskFlow** | Канбан-доска с drag & drop, приоритетами и тёмной темой | [demo](https://taskflow-xi-vert.vercel.app) · [code](https://github.com/ykvlev/taskflow) |
| **chess** | Промо-лендинг шахматного клуба на чистом HTML/CSS/JS | [code](https://github.com/ykvlev/chess) |
| **todo-bot** | Telegram-менеджер задач: дедлайны, повторы, напоминания, экспорт CSV | [code](https://github.com/ykvlev/todo-bot) |

---

## 🔭 Сейчас работаю над

Циклом **фронтенд-пет-проектов** — собираю аккуратные, продуманные интерфейсы и складываю их в [портфолио](https://portfolio-topaz-omega-71.vercel.app) (последний — **[TaskFlow](https://taskflow-xi-vert.vercel.app)**). Параллельно — инструменты по **кибербезопасности и ML** на Python.

---

## 📊 Статистика GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=ykvlev&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&icon_color=3B82F6&title_color=3B82F6" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ykvlev&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&title_color=3B82F6" />

<br />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ykvlev&theme=tokyonight&hide_border=true&ring=3B82F6&fire=3B82F6&currStreakLabel=3B82F6" />

<br />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ykvlev&theme=react-dark&bg_color=0D1117&color=3B82F6&line=3B82F6&point=FFFFFF&area=true&hide_border=true" alt="График активности" width="98%" />

<br />

<img src="https://github-profile-trophy.vercel.app/?username=ykvlev&theme=algolia&no-frame=true&no-bg=true&margin-w=4&column=7" alt="Трофеи" />

</div>

---

## 🐍 Граф контрибуций

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ykvlev/ykvlev/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ykvlev/ykvlev/output/github-snake.svg" />
  <img alt="Змейка съедает мой граф контрибуций" src="https://raw.githubusercontent.com/ykvlev/ykvlev/output/github-snake.svg" width="98%" />
</picture>

</div>

---

## 🎓 Образование

**Новгородский государственный университет им. Ярослава Мудрого** — Великий Новгород
*Прикладная математика и информатика (09.02.07), выпуск 2028*

---

<div align="center">

### 📫 Связаться

[![Telegram](https://img.shields.io/badge/Telegram-%40ykvlev__a-229ED9?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/ykvlev_a)
[![VK](https://img.shields.io/badge/VK-ykvlev__a-0077FF?style=for-the-badge&logo=vk&logoColor=white)](https://vk.com/ykvlev_a)
[![Email](https://img.shields.io/badge/Email-tema643789-1E293B?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tema643789@gmail.com)

<i>Открыт к интересным задачам и стажировкам 🚀</i>

</div>
