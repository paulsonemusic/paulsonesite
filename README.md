# Paul Sone 3.9
Откройте index.html двойным щелчком. Сервер не нужен.

- links.js — адреса соцсетей, общие для кнопок и страниц-перенаправлений.
- settings.js — тексты, цвета, email, donate, image (например portrait.png), звук (например sounds/click.mp3). Файлы кладите рядом с index.html или в соответствующую папку.
- gallery/ — фотографии любых пропорций. Добавьте имена в массив gallery/photos.js, например window.photos = ['one.jpg', 'two.jpg'];. Браузер не умеет автоматически перечислять файлы папки на статическом хостинге. Пока список пуст, видны заглушки.
- Для нового редиректа скопируйте папку youtube, переименуйте её, измените ключ в её index.html и добавьте соответствующий ключ в links.js.
- GitHub Pages: загрузите содержимое этой папки (включая .nojekyll и CNAME) в корень репозитория, Settings → Pages → Deploy from a branch → main / root. Настройте custom domain paulsone.com и DNS у вашего DNS-провайдера по инструкции GitHub. Включите HTTPS после проверки DNS.
- Редиректы выполняются JavaScript, не HTTP 301. GitHub Pages может добавить завершающий слеш.
- Пасхалки: пять нажатий на PAUL SONE переключают тему и вращают логотип; Do not press показывает случайную фразу и вращается, либо играет заданный звук; ◐ переключает тему. Карусель листается только вручную: кнопками и свайпом. Анимации учитывают reduced motion.
- Почта, донат, портрет и аудио не предоставлены, соответствующие настройки пусты.

## Version 3.3
Gallery tiles crop to squares; click to see the full image, Escape to close. Music playlist: sounds/pumpkin.mp3, energetic.mp3, rap-restored.mp3; pumpkin and rap-restored are supplied audio files. Browser autoplay may require a click. Music toggle is in the header. Favicon files are included.

## Version 3.4
Rap track re-encoded with silent gap removed. Footer collaboration / PR email is editable via footerEmail in settings.js.
