# Nazar Hezretkuliev — personal site

Personal business-card site of a Python / Django developer.
English and Russian versions, downloadable CV (PDF).

## Files

- `index.html` — the whole site (styles and scripts are inside)
- `photo.jpg` — your photo (replace it with another photo under the same name)
- `cv/` — CV in PDF, English and Russian
- `.nojekyll` — tells GitHub Pages to publish the files as they are

## How to publish on GitHub Pages

1. Sign in at github.com (or create an account).
2. Click **New repository**.
   - Name: `YOUR-USERNAME.github.io` gives the short address `https://YOUR-USERNAME.github.io`.
     Any other name (for example `portfolio`) gives `https://YOUR-USERNAME.github.io/portfolio/`.
   - Visibility: **Public**.
3. In the new repository click **uploading an existing file**.
4. Unzip this archive and drag **the contents of the folder** (`index.html`, `photo.jpg`, `cv`, `.nojekyll`, `README.md`) into the browser window. Do not upload the zip itself.
5. Click **Commit changes**.
6. Open **Settings → Pages**. Under **Build and deployment** choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
7. After 1–2 minutes the address appears at the top of the Pages screen. Put it in your CV and your profiles.

## How to change things later

- Photo: upload a new `photo.jpg` to the repository (Add file → Upload files).
- Text: open `index.html` on GitHub, click the pencil icon, edit, **Commit changes**.
- CV: upload new PDFs into `cv/` with the same names.

---

# Персональный сайт — Назар Хезреткулиев

Сайт-визитка Python / Django разработчика. Русская и английская версии, резюме в PDF.

## Как выложить на GitHub Pages

1. Войдите на github.com (или зарегистрируйтесь).
2. Нажмите **New repository**.
   - Название `ВАШ-ЛОГИН.github.io` даст короткий адрес `https://ВАШ-ЛОГИН.github.io`.
     Любое другое название (например `portfolio`) даст адрес `https://ВАШ-ЛОГИН.github.io/portfolio/`.
   - Тип: **Public**.
3. В новом репозитории нажмите **uploading an existing file**.
4. Распакуйте архив и перетащите в окно браузера **содержимое папки** (`index.html`, `photo.jpg`, `cv`, `.nojekyll`, `README.md`). Сам zip загружать не нужно.
5. Нажмите **Commit changes**.
6. Откройте **Settings → Pages**. В разделе **Build and deployment** выберите **Deploy from a branch**, ветка **main**, папка **/ (root)**, нажмите **Save**.
7. Через 1–2 минуты вверху страницы Pages появится адрес сайта. Добавьте его в резюме и профили.

## Как менять потом

- Фото: загрузите новый `photo.jpg` в репозиторий (Add file → Upload files).
- Текст: откройте `index.html` на GitHub, нажмите значок карандаша, измените, **Commit changes**.
- Резюме: загрузите новые PDF в папку `cv/` с теми же именами.
