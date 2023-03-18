# sem_2_labs

## TASK №1
```
<div class="body">
        <div class="body__head">
          <div class="body__hair"></div>
        </div>
        <div class="body__arms">
          <div class="body__arms-left"></div>
            <div class="arms-left__finger"></div>
          <div class="body__arms-right"></div>
            <div class="arms-right__finger"></div>
        </div>
        <div class="body__legs">
          <div class="body__legs-shoes"></div>
            <div class="body__legs-shoes_color_black"></div>
          <div class="body__legs-pants"></div>
            <div class="body__legs-pants_color_blue"></div>
        </div>
      </div>
```

## FORM
```
h2.description+form.form>(label.form__label+select.form__select[name="input"]>option.option$*3)*2+(label.form__label+input.form__input[type="text"  name="input"])*3+button.form__button[type="submit"]
```
![FROM](./pic/form.png)

## HEADER
```
header.header>(a.header__link>img.header__pic)+nav.header__navigation>ul.header__navigation_list>(li.navigation__item>a.navigation__link)*6
```
![Снимок экрана 2023-03-04 133808](https://user-images.githubusercontent.com/113594587/222895433-53d29a36-a1bd-47eb-aa00-682ecae9924c.png)

## CARD
```
h2.cards__heading+ul.cards>(li.card>(p.card__description)*2+button.card__button+img.card__pic)*3
```
![Снимок экрана 2023-03-04 134117](https://user-images.githubusercontent.com/113594587/222895484-8c43b2c1-ea5c-4566-ad27-ec2e972aac4a.png)

## FOOTER
```
footer.footer>(ul.footer__list>li.footer__logo+li.footer__contacts+li.footer__mail)+p.footer__policy
```
![Снимок экрана 2023-03-04 134128](https://user-images.githubusercontent.com/113594587/222895480-19ad920f-22ca-47ef-a187-0c7a5c3a309d.png)
