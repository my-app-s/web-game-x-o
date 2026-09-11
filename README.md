# Tic-Tac-Toe vs AI

![Static Badge](https://img.shields.io/badge/HTML5-24214e?logo=HTML5)
![Static Badge](https://img.shields.io/badge/CSS3-24214e?logo=CSS)
![Static Badge](https://img.shields.io/badge/JavaScript-24214e?logo=JavaScript)
![Static Badge](https://img.shields.io/badge/JavaScript-24214e?logo=TailwindCSS)

> Status Github Actions
> 
> ![Status GitHub Pages](https://github.com/my-app-s/web-game-x-o/actions/workflows/deploy-page.yml/badge.svg)

Современная реализация классической игры «Крестики-нолики», написанная на чистом JavaScript и стилизованная с помощью **Tailwind CSS** с автоматической сборкой через **Tailwind CLI** и **GitHub Actions**. Игра работает полностью на стороне клиента и включает встроенный алгоритм искусственного интеллекта (ИИ) с настраиваемой сложностью.

## Особенности

* **Однофайловая архитектура (Single-File Component):** Логика, разметка и интерактивные элементы клиентской части сосредоточены в едином `index.html`.
* **Tailwind CSS Build Pipeline:** Использование официального **Tailwind CLI** в GitHub Actions для компиляции и минификации production-стилей перед деплоем.
* **Интеллектуальный ИИ и уровни сложности:** Переключение режимов от легкого (рандомные ходы) до хардкорного (непобедимый алгоритм Minimax).
* **Сохранение статистики:** Трекинг побед, поражений и ничьих в локальном хранилище браузера (`localStorage`).
* **Безопасность и чистота:** Изоляция данных на клиенте, отсутствие тяжелых зависимостей и сторонних NPM-пакетов.

## Автоматический деплой (CI/CD)

Проект настроен на непрерывную интеграцию и доставку с помощью **GitHub Actions**. При каждом пуше в ветку, затрагивающем `index.html`:

1. Скачивается актуальный бинарник **Tailwind CLI**.
2. Компилируется оптимизированный файл `output.css`.
3. Сборка упаковывается и публикуется на **GitHub Pages**.

## Быстрый старт и локальная разработка

1. Клонируйте репозиторий и откройте проект.
2. Для локальной компиляции стилей загрузите Tailwind CLI или подключите его через сборщик.
3. Откройте `index.html` в браузере, выберите уровень сложности и нажмите **Start Game**.

## Disclaimer & License

* **Short Disclaimer (EN)**: Materials are provided ***as is*** under the LICENSE file. No warranties. Authors are not liable for damages. No partnership or obligations created.
* **Short Disclaimer (RU)**: Материалы предоставляются ***как есть*** и регулируются файлом LICENSE. Гарантий нет. Автор(ы) не несут ответственности за убытки. Партнёрство или обязательства не создаются.
* **Full Disclaimer**: Read the full text in the DISCLAIMER (Available in EN/RU).
* **License**: This project is dual-licensed:
* **Open Source**: Licensed under the [GNU AGPLv3](https://www.google.com/search?q=./LICENSE).
* **Commercial**: A separate proprietary commercial license is required for proprietary, closed-source, or enterprise use that does not comply with AGPLv3 terms. Contact the copyright holder for commercial licensing.

## Author & Contacts

* **GitHub**: [@my-app-s](https://github.com/my-app-s)
* **LinkedIn**: [In/my-app-s](https://www.linkedin.com/in/my-app-s)
* **Mail**: [myapps.mre.dev@gmail.com](mailto:myapps.mre.dev@gmail.com)
