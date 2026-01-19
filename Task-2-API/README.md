# Задание 2: Проектирование API для экрана магазинов-партнеров

## REST API запрос

**Метод:** `GET`  
**URL:** `https://api.petrushka.zelenaya.ru/api/partner-stores`  
**Заголовки:**
- `Accept: application/json`

## Пример ответа API (JSON)

```json
{
  "stores": [
    {
      "id": "metro",
      "name": "METRO",
      "description": "Ближайшая доставка сегодня 21:00-23:00",
      "url": "https://www.metro-cc.ru"
    },
    {
      "id": "auchan",
      "name": "Ашан",
      "description": "Ближайшая доставка сегодня 18:00-20:00",
      "url": "https://www.auchan.ru"
    },
    {
      "id": "vkusvill",
      "name": "ВкусВилл",
      "description": "Быстрая доставка от 20 до 60 минут",
      "url": "https://vkusvill.ru"
    },
    {
      "id": "victoria",
      "name": "ВИКТОРИЯ",
      "description": "Ближайшая доставка сегодня 17:00-19:00",
      "url": "https://www.victoria-group.ru"
    }
  ]
}
