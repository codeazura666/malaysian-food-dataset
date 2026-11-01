# Malaysian Food Dataset

Датасет фотографий малайзийских блюд. Каждое блюдо — отдельная папка (класс), файлы названы по блюду: `nasi_lemak/nasi_lemak_001.jpg`.

- **Блюд:** 21
- **Фото:** 648, JPEG, обычно 960–1280 px по длинной стороне
- **Проверка:** каждое фото просмотрено вручную; убраны логотипы, упаковки, вывески, люди без еды, фото с водяными знаками, коллажи и почти одинаковые кадры

## Скачать всё разом

[Скачать ZIP](https://github.com/codeazura666/malaysian-food-dataset/archive/refs/heads/main.zip)

## Блюда

| Папка | Блюдо | Фото |
|---|---|---|
| [nasi_lemak](nasi_lemak) | Nasi lemak — рис на кокосовом молоке с самбалом, анчоусами, арахисом и яйцом | 74 |
| [rendang](rendang) | Rendang — мясо, тушённое в кокосовом молоке со специями | 22 |
| [satay](satay) | Satay — шашлычки на шпажках с арахисовым соусом | 95 |
| [roti_canai](roti_canai) | Roti canai — слоёная лепёшка, подаётся с карри | 18 |
| [laksa](laksa) | Laksa — острый суп с лапшой | 63 |
| [char_kway_teow](char_kway_teow) | Char kway teow — жареная плоская рисовая лапша | 18 |
| [hainanese_chicken_rice](hainanese_chicken_rice) | Hainanese chicken rice — отварная курица с рисом на бульоне | 63 |
| [nasi_goreng](nasi_goreng) | Nasi goreng — жареный рис | 71 |
| [cendol](cendol) | Cendol — десерт: лёд, зелёное желе, кокосовое молоко, пальмовый сахар | 14 |
| [teh_tarik](teh_tarik) | Teh tarik — «тянутый» чай с молоком | 10 |
| [apam_balik](apam_balik) | Apam balik — толстый блин с арахисом и сахаром | 15 |
| [ais_kacang](ais_kacang) | Ais kacang — тёртый лёд с сиропом, фасолью и желе | 10 |
| [bak_kut_teh](bak_kut_teh) | Bak kut teh — суп из рёбрышек на травах | 13 |
| [ketupat](ketupat) | Ketupat — рис, сваренный в плетёнке из пальмовых листьев | 17 |
| [wonton_mee](wonton_mee) | Wonton mee — лапша с вонтонами | 59 |
| [murtabak](murtabak) | Murtabak — жареная лепёшка с мясом и яйцом | 17 |
| [mee_goreng](mee_goreng) | Mee goreng — жареная лапша | 16 |
| [otak_otak](otak_otak) | Otak-otak — рыбная паста, запечённая в листьях | 10 |
| [pisang_goreng](pisang_goreng) | Pisang goreng — бананы в кляре | 12 |
| [yong_tau_foo](yong_tau_foo) | Yong tau foo — тофу и овощи с рыбной начинкой | 14 |
| [claypot_chicken_rice](claypot_chicken_rice) | Claypot chicken rice — рис с курицей в глиняном горшке | 17 |

## Структура

```
<блюдо>/
  <блюдо>_001.jpg
  ...
CREDITS.csv   # класс, файл, источник, автор и лицензия каждого фото
```

## Источник и лицензии

Все фото взяты с [Wikimedia Commons](https://commons.wikimedia.org/) и распространяются под свободными лицензиями (CC0, Public domain, CC BY, CC BY-SA, GFDL). Автор, ссылка на оригинал и лицензия для каждого файла указаны в `CREDITS.csv`. При использовании фото под CC BY / CC BY-SA нужно указывать автора и лицензию.
