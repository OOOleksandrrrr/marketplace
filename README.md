```text
marketplace/
├── arcgis/                  # 6 процессов ArcGIS: BPMN + PNG
├── skyfi/                   # 6 процессов SkyFi: BPMN + PNG
├── skywatch/                # 6 процессов SkyWatch: BPMN + PNG
├── up42/                    # 6 процессов UP42: BPMN + PNG, отдельный анализ
├── bpmn.pptx                # презентация со схемами процессов
├── comparison_table.xlsx    # сравнительная таблица сервисов
├── service.txt              # краткие описания сервисов и процессов
└── idea.txt                 # идея интеллектуального поиска снимков
```

### ArcGIS

| № | Процесс | BPMN | Превью |
|---:|---|---|---|
| 1 | Поиск и подключение снимков | [01_discover_imagery.bpmn](arcgis/01_discover_imagery.bpmn) | [PNG](arcgis/01_discover_imagery.png) |
| 2 | Публикация растровых данных | [02_publish_imagery.bpmn](arcgis/02_publish_imagery.bpmn) | [PNG](arcgis/02_publish_imagery.png) |
| 3 | Растровый анализ | [03_raster_analysis.bpmn](arcgis/03_raster_analysis.bpmn) | [PNG](arcgis/03_raster_analysis.png) |
| 4 | Управление опубликованными изображениями | [04_manage_imagery.bpmn](arcgis/04_manage_imagery.bpmn) | [PNG](arcgis/04_manage_imagery.png) |
| 5 | Настройка общего доступа | [05_share_access.bpmn](arcgis/05_share_access.bpmn) | [PNG](arcgis/05_share_access.png) |
| 6 | Скачивание растров | [06_download_rasters.bpmn](arcgis/06_download_rasters.bpmn) | [PNG](arcgis/06_download_rasters.png) |

### SkyFi

| № | Процесс | BPMN | Превью |
|---:|---|---|---|
| 1 | Покупка архивного снимка | [01_archive_purchase.bpmn](skyfi/01_archive_purchase.bpmn) | [PNG](skyfi/01_archive_purchase.png) |
| 2 | Заказ новой съёмки | [02_new_tasking.bpmn](skyfi/02_new_tasking.bpmn) | [PNG](skyfi/02_new_tasking.png) |
| 3 | Заказ аналитического продукта | [03_analytics.bpmn](skyfi/03_analytics.bpmn) | [PNG](skyfi/03_analytics.png) |
| 4 | Отслеживание заказа и получение результата | [04_order_delivery.bpmn](skyfi/04_order_delivery.bpmn) | [PNG](skyfi/04_order_delivery.png) |
| 5 | Подключение STAC-каталога к ArcGIS | [05_arcgis_stac.bpmn](skyfi/05_arcgis_stac.bpmn) | [PNG](skyfi/05_arcgis_stac.png) |
| 6 | Просмотр данных через WMTS | [06_wmts_streaming.bpmn](skyfi/06_wmts_streaming.bpmn) | [PNG](skyfi/06_wmts_streaming.png) |

### SkyWatch EarthCache

| № | Процесс | BPMN | Превью |
|---:|---|---|---|
| 1 | Заказ архивных данных | [01_archive_order.bpmn](skywatch/01_archive_order.bpmn) | [PNG](skywatch/01_archive_order.png) |
| 2 | Заказ новой съёмки | [02_tasking.bpmn](skywatch/02_tasking.bpmn) | [PNG](skywatch/02_tasking.png) |
| 3 | Управление заказами и результатами | [03_orders_results.bpmn](skywatch/03_orders_results.bpmn) | [PNG](skywatch/03_orders_results.png) |
| 4 | Просмотр через DirectView и WMTS | [04_directview_wmts.bpmn](skywatch/04_directview_wmts.bpmn) | [PNG](skywatch/04_directview_wmts.png) |
| 5 | Проекты и оплата | [05_projects_billing.bpmn](skywatch/05_projects_billing.bpmn) | [PNG](skywatch/05_projects_billing.png) |
| 6 | Роли и права доступа | [06_roles_access.bpmn](skywatch/06_roles_access.bpmn) | [PNG](skywatch/06_roles_access.png) |

### UP42

| № | Процесс | BPMN | Превью |
|---:|---|---|---|
| 1 | Заказ новой съёмки | [01_tasking.bpmn](up42/01_tasking.bpmn) | [PNG](up42/01_tasking.png) |
| 2 | Обработка данных | [02_processing.bpmn](up42/02_processing.bpmn) | [PNG](up42/02_processing.png) |
| 3 | Управление данными | [03_data_management.bpmn](up42/03_data_management.bpmn) | [PNG](up42/03_data_management.png) |
| 4 | Поиск данных в каталоге | [04_catalog_search.bpmn](up42/04_catalog_search.bpmn) | [PNG](up42/04_catalog_search.png) |
| 5 | Управление заказом и получение результатов | [05_order_results.bpmn](up42/05_order_results.bpmn) | [PNG](up42/05_order_results.png) |
| 6 | Доступ к коллекциям и принятие EULA | [06_access_eula.bpmn](up42/06_access_eula.bpmn) | [PNG](up42/06_access_eula.png) |

Подробный текстовый разбор UP42 находится в файле [UP42_process_analysis.docx](up42/UP42_process_analysis.docx).

## Как открыть материалы

1. Для быстрого просмотра схем откройте соответствующий файл `.png` прямо на GitHub.
2. Для редактирования скачайте файл `.bpmn` и откройте его в [Camunda Modeler](https://camunda.com/download/modeler/): **File → Open File**.
3. Общий обзор процессов находится в [bpmn.pptx](bpmn.pptx).
4. Сравнение сервисов по критериям находится в [comparison_table.xlsx](comparison_table.xlsx).
5. Краткие пояснения к сервисам находятся в [service.txt](service.txt).