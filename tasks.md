## Список задач

BUG-1. Не проходит вот такой запрос списка регионов
    $request = (new Location())->setCountryCodes(['RU','TR']);
     return $this->client->getRegions($request);