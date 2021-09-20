# Thrive_talk landing page
Implement landing page according to [Figma design](https://www.figma.com/file/aHd2rHMrnzDXhowLuIQjIyVQ/ThriveTalk-Landing-Page?node-id=0%3A1) - Use BEM and SCSS
- Large screens 2560px
- Full HD 1920px
- The design 1600px
- Notebook 1280px
- Tablet 1024
- Mobile (> 320px)

1. Implement the header with `nav`.
1. Implement `Helping you thrive in all areas of life` block.
1. Implement `Why Thrive?` block.
1. Implement `About us` block.
1. Implement `We can help you with` block with the card reused 3 times.
1. Implement block with 6 cards (`Physical Health`, `Mental Health`, `Nutrition`,
   `Gymnastics`, `Crossfit`, `Aerobics`).
1. Implement block with 6 text-cards (`Nutritional Plans`, `Weight Loss`, `Mental Peace`,
   `Home Training`, `Work/Life Balance`, `Cardio`).
1. Implement `You should also know` block.
1. Implement `Contact us` block.
1. Implement blocks: `Some info`, `Enfold health`, `Office hourse`.
1. Implement footer.


## HR important moments
- Скорость анимаций на всем лендинге одинаковая (например увеличение при наведении или выезд блоков при скроле)
- Placeholder в формах подсказывают что именно ввести, а если стоит валидация формы, то понятно в каком формате вводить номер телефона
- Убедитесь, что с мобильных выглядит все аккуратно и без горизонтальной прокрутки
- Добавьте favicon
- Добавьте мягкий скролл при клике на меню до соответствующих блоков страницы
- Все пункты в меню должны иметь hover-стили и вести на разные секции в лендинге
- Логотип должен увеличиваться при ховере
- Кнопка “contact us” должна вести на секцию “contact us”
- Все кнопки “get help now” должны менять цвет при ховере
- Когда открыт первый блок с заглавной страницей, не должны обрезаться кнопки "who i am", "what do i do". Их лучше расположить чуть выше, чтобы можно было сразу увидеть
С- тоит все шрифты сделать четко по макету (дизайнеры специально подбирали шрифты так, чтобы те между собой сочетались), свои шрифты лучше не дописывать)
- Для пользователя удобно, когда при клике на Address, он открывается в новой вкладке в гугл-картах. Это стоит доделать
- Кнопка Blog в верхнем меню должна быть кликабельной и вести на страницу "you should also know" (это не совсем блог, но логически максимально приближеный к нему блок, который есть в лендинге)
- Чтобы как-то оживить лендинг можно менять цвет цветных блоков при ховере


## Github flow
1. **Fork** the repo.
2. **Clone** the forked one. (The project link should have your name but not `mate-academy`)
3. Run `npm install` (or just `npm i`).
4. Run `npm start`.
5. Open one more terminal window for the next steps.
6. `git checkout -b develop` - to create new branch and switch on it.
7. Write you code in `src` folder.
8. Run `npm run lint` and fix code style errors.
9. Run `npm run deploy` to deploy your solution to `gh-pages`.
10. `git add . && git commit -m 'write a short description of the changes you made'` to save your changes.
11. `git push origin develop` - to send you code for PR.
12. Create a Pull Request (PR) from your branch `develop` to branch `master` of original repo.
13. Replace `<your_account>` with your Github username in the
  [DEMO LINK](https://<your_account>.github.io/Thrive_talk/).
14. Copy `DEMO LINK` to the PR description.

> To update you PR repeat steps 7-11.
