# RU Шаблон резюме

Создавайте своё резюме в формате markdown и получайте html и pdf версии. Markdown будет отлично смотреться на github, а html и pdf версии будут полезны при отправке резюме на вакансии.

## Установка

Форкните, затем склонируйте репозиторий и установите зависимости:

```bash
npm install
```

## Использование

Внесите свои данные в файл `README.md` (в корне репозитория) и запустите сборку:

```bash
npm run compile
```

Этот скрипт сгенерирует файл `index.html` и `cv.pdf` в корне репозитория.

Также можете редактировать файлы `src/print.css` и `src/style.css`, `src/template.html` для изменения внешнего вида резюме.

В конце отправьте ваши изменения на github. Не забудьте настроить github pages для вашего репозитория, чтобы получить ссылку на веб и pdf версии вашего резюме.

# EN Resume Template

Create your resume in markdown format and get HTML and PDF versions. Markdown will look great on GitHub, while HTML and PDF versions will be useful when submitting your resume for job applications.

## Installation

Fork, then clone the repository and install dependencies:

```bash
npm install
```

## Usage

Enter your details in the README.md file (at the root of the repository) and run the build:

```bash
npm run compile
```

This script will generate the index.html and cv.pdf files in the root of the repository.

You can also edit the src/print.css, src/style.css, and src/template.html files to customize the appearance of your resume.

Finally, push your changes to GitHub. Don't forget to set up GitHub Pages for your repository to get a link to the web and PDF versions of your resume.
