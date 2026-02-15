# Ручное тестирование API сервиса Яндекс Прилавок

Яндекс Прилавок - продуктовый онлайн - магазин. 

Пользователь может выбрать продукты как из общего списка продуктов, так и из заранее собранных наборов ("Под ситуацию", "Приготовь блюдо"). Так же можно создавать собственные наборы. Сервис работает с курьерской службой (8 вариантов доставки). Продукты магазина находятся в 4 разных складких отделениях, каждое со своим набором продуктов.

# Задачи:
Протестировать новые функциональности в API онлайн - магазина: 
- возможность добавлять продукты в набор
- возможность проверить, есть ли доставка курьерской службой "Привезём быстро" и сколько она стоит
- возможность получить список продуктов, которые добавили в корзину
- возможность добавлять продукты в корзину
- возможность удалять корзину

# Стек:
<div align="left">
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman"/>
  <img src="https://img.shields.io/badge/API_Doc-009688?style=for-the-badge&logo=readthedocs&logoColor=white" alt="API Doc"/>
  <img src="https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white" alt="Google Sheets"/>
</div>

# Артефакты тестирования:

| Документ | Ссылка |
|----------|--------|
| **Чек-лист** | [![Google Sheets](https://img.shields.io/badge/Чек--лист-34A853?style=for-the-badge&logo=google-sheets)](https://docs.google.com/spreadsheets/d/1j71DLfWUbzkSHwQ9wG7kxS_Ob44fiDAKNbkha3h0wXg/edit#gid=2006427015) |
| **Баг-репорты** | [![Google Sheets](https://img.shields.io/badge/Баг--репорты-FF6C37?style=for-the-badge&logo=google-sheets)](https://docs.google.com/spreadsheets/d/1j71DLfWUbzkSHwQ9wG7kxS_Ob44fiDAKNbkha3h0wXg/edit#gid=1831872143) |

# Результаты:

| Показатель | Значение |
|------------|----------|
| **Всего запросов** | 110 |
| **Найдено багов** | 36 |

# Полный отчет о тестировании
[![Отчет о тестировании](https://img.shields.io/badge/Отчет_о_тестировании-Google_Docs-4285F4?style=for-the-badge&logo=google-docs&logoColor=white)](https://docs.google.com/document/d/1FB26roP4mid7f6t3yHoM4vJZCBYPeHDks9GSRAr0ZUA/edit?usp=sharing)

**Содержание отчета:**
- Чек-лист: 110 тест-кейсов
- Найдено багов: 36
- Время тестирования: 5 часов
- Детальный список дефектов с ID (БН-1...БУ-36)
- Выводы и рекомендации
- **Статус:** Функциональность не готова к релизу
