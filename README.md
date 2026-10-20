# Libre VPN Configs

Автоматический сбор и проверка VPN-конфигов.

Обновление подписок каждые 3 часа.

- Обновлено: **2026-10-20 07:17:22 UTC**
- Всего конфигов в базе: **139139**
- Живых (прошли проверку): **1813**
- Уникальных хостов: **1101**
- Из автопарсеров: **15513**
- Подтверждено вручную пользователем: **57**

## Подписки

| Подписка | Конфигов | Протоколы | Описание | Ссылка |
|---|---|---|---|---|
| `special/anchor` | 151 | vless: 151 | VLESS+Reality по подтверждённым паттернам | [raw](https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/special/anchor) |
| `stable.txt` | 151 | vless: 151 | то же, что основная | [raw](https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/stable.txt) |
| `liber` | 289 | vless: 274, vmess: 15 | всё, без потолка | [raw](https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/liber) |
| `ru.txt` | 32 | vless: 32 | RU-выход отдельной подпиской | [raw](https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/ru.txt) |
| `vless.txt` | 151 | vless: 151 | по протоколу | [raw](https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/vless.txt) |
| `vmess.txt` | 151 | vless: 151 | по протоколу | [raw](https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/vmess.txt) |
| `trojan.txt` | 151 | vless: 151 | по протоколу | [raw](https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/trojan.txt) |
| `ss.txt` | 151 | vless: 151 | по протоколу | [raw](https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/ss.txt) |
| `hy2.txt` | 151 | vless: 151 | по протоколу | [raw](https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/hy2.txt) |

## Канал

- Поддержка и свежие подписки: **[t.me/IFakeNews](https://t.me/IFakeNews)**
- Веб-приложение: <https://fakeonomics.online>

## Как это работает

1. **Сбор** — берём готовые выходные файлы автопарсеров (VansFenix, mehrtat, kort0881, mahdibland, igareck) и дедуплицируем по идентичности (протокол + учётка + хост + порт + транспорт), а не по строке.
2. **Проверка** — каждый конфиг поднимается как xray/sing-box-клиент и через него идёт РЕАЛЬНЫЙ трафик: 128 КБ, пауза 3 секунды, ещё 128 КБ. Сервер, который «отработал и умер», отсеивается.
3. **Отбор** — в основную подписку попадают только VLESS+Reality, собранные по паттернам, подтверждённым пользователем на реальном мобильном.
4. **Стабильность** — конфиг должен пережить несколько замеров подряд (streak), иначе он не публикуется.
5. **Публикация** — раз в 3 часа, автоматически.

## Прочее

- Основная подписка: `special/anchor`
- Полный набор: `liber`
- Российские выходы: `ru.txt` (в основной их нет — в РФ они бесполезны)
