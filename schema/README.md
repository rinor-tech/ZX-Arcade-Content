# Схема публичного каталога

catalog/manifest.json использует zx-arcade-public-catalog/1. Текущая content_version=pilot-206-v1-bruce-lee-1; исходная фиксированная pilot-206-v1 сохранена. Стабильные game_id и work_id идентифицируют произведение; variant_id и массив variants сохраняют издания, язык, модель и упорядоченные parts. auto_model=false: подпись файла не выбирает модель автоматически.

В каждом parts и covers.2d/covers.3d: ext, bytes, sha256, анонимный HTTPS url, origin и исторический legal_status. publication=owner-authorized фиксирует отдельное поручение владельца о публикации и не меняет unknown на allowed. content_kind=demo, метки ES/RU/unknown и provenance сохраняются.

Публикация: downloadable=true, distribution=github-release. offline=false в публичном документе: клиент определяет Offline только по своему проверенному кэшу. Реестр objects.json задаёт655 отдельных объектов, поэтому ленивое получение не требует общего архива. Фиксированная версия находится в catalog/versions/pilot-206-v1; текущий manifest обновлён только после полной HTTP/SHA-проверки.

example-manifest.json — исторический вымышленный пример POP-EXAMPLE, не реальная игра.
