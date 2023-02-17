# git-branching_bem
## Задание 1
* `голова`
  * `голова__волосы`
    * `волосы`
    * `волосы--длина_короткие`
    * `волосы--цвет_чёрный`
  * `голова__глаз`
    * `глаз`
    * `глаз--цвет_голубой`
    * `глаз`
    * `глаз--цвет_зелёный`
  * `голова__нос`
    * `нос`
    * `нос--размер_средний`
* `тело`
* `тело--размер-худое`
  * `тело__рука`
    * `рука`
    * `рука`
    * `рука--тема_с-часами`
* `ноги`

## Задание 2

### header 
  ![скриншот блока header](img/header_bem.png)

  header.header>.wrapper.header__container>(a.link.link--hover_off>img.header__logo)+nav.header__menu>ul.header__menu-list>(li.header__menu-item*4>a.link)+li.header__menu-item>a.link.link--hover_off>img.icon-cart

### форма
  ![скриншот блока form](img/form_bem.png)

  form.contact-form.contact-form--pink>(.contact-form__desc>p.contact-form__title+p.contact-form__text)+(fieldset.input-group>legend.input-group__header.hidden+(label.input-group__label.*4>span.hidden+input.input.contact-form__input.contact-form__input--size_md)+label.input-group__label>span.hidden+textarea.textarea.textarea--resize_off.contact-form__input.contact-form__input--size_lg)+button.btn.contact-form__btn

### карточка
  ![скриншот блока карточки](img/card_bem.png)

  .card.card--pink>(.card__header>.card__image)+.card__body>.card__title+p.card__text>a.link

### Вериткальный список
![скриншот блока списка](img/list.png)

  ul.vertical-list.vertical-list.vertical-list--theme_white>(li.vertical-list__item>(.vertical-list__item-desc.col>.col__title+p.col__text*3)+img.vertical-list__item-img)+(li.vertical-list__item>img.vertical-list__item-img+.vertical-list__item-desc.col>.col__title+p.col__text.col__text--color_grey*3+a.link.link_theme_button)+li.vertical-list__item>(.vertical-list__item-desc.col>.col__title+p.col__text*3)+img.vertical-list__item-img