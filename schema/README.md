# Схема публичного каталога

`catalog/manifest.json` использует схему `zx-arcade-public-catalog/1`.

Поля `availability` и `publication` у каждой строки здесь равны `unavailable` и `unpublished`. `downloadable` и `offline` равны `false`. Это описание состава, а не адрес файла.

Пример в `example-manifest.json` вымышленный: `POP-EXAMPLE` не игра из пилота и не обещает файл.

`legal_status=unknown` не записывается как `allowed`. Статус `allowedzxart` сам по себе не разрешает выкладку на GitHub.
