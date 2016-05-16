# Sports.ru Hockey API

## Лента

```
GET
http://www.sports.ru/stat/export/iphone/tag_lenta_with_filters.json
```

| Параметр | Значение |
|----------|-------------|
| tag_id[] | `1046527` |
| count | `20` |
| main_only | `1` |
| available_content_types[] | `news` |
| available_content_types[] | `article` |
| available_content_types[] | `blog` |
| available_content_types[] | `photo` |
| available_content_types[] | `photogallery` |
| available_content_types[] | `video` |
| available_content_types[] | `videogallery` |

## Новости

```
GET
http://www.sports.ru/stat/export/iphonetags/news.json
```

| Параметр | Значение |
|----------|-------------|
| tags | `1046527` |
| count | `20` |
| from | `0` |

## Состав

```
GET
http://www.sports.ru/stat/export/iphone/teamplayers.json
```

| Параметр | Значение |
|----------|-------------|
| tag | `1046527` |

## Статусы

```
GET
http://www.sports.ru/stat/export/iphone/status/tag.json
```

| Параметр | Значение |
|----------|-------------|
| tag_id | `1046527` |

## Матчи

```
GET
http://www.sports.ru/stat/export/iphone/team_full_calendar_seasons.json
```

| Параметр | Значение |
|----------|-------------|
| tag | `1046527` |
