# Аналитическая лаба №2 (Azure)

# Команда "Шизика фу"

* Долгов Константин - капитан
* Теребов Максим
* Сарычев Сергей

Вариант работы: 2

# Цель работы

&emsp; Знакомство с облачными сервисами. Понимание уровней абстракции над инфраструктурой в облаке. Формирование понимания типов потребления сервисов в сервисной-модели. Сопоставление сервисов между разными провайдерами. Оценка возможностей миграции на отечественные сервисы.

# Дано

1. Слепок данных биллинга от провайдера после небольшой обработки в виде SQL-параметров. Символ % в начале/конце означает, что перед/после него может стоять любой набор символов.
2. Google с документациями провайдера

# Ход работы

&emsp; Была дана следующая таблица:

<img width="1035" alt="image" src="https://github.com/Kostik2302/clouds/assets/113085945/a7bc31ed-f5ce-4ffc-be8c-0b4e0fbb80dc">

## Описание встретившихся сервисов

### Data Management (Azure managed databases)

&emsp; Azure managed databases - это полностью управляемая служба баз данных, которая позволяет пользователям сосредоточиться на разработке приложений, а не на управлении инфраструктурой баз данных. Служба включает в себя автоматическое резервное копирование, масштабирование, мониторинг и безотказность.

### Machine Learning Studio

&emsp; Machine Learning Studio - это интегрированная среда разработки, которая позволяет специалистам по данным и разработчикам создавать, развертывать и управлять машинными моделями. Служба включает в себя набор инструментов и шаблонов, которые упрощают процесс создания моделей машинного обучения.

### Azure Bastion

&emsp; Azure Bastion - это полностью управляемая служба, которая обеспечивает безопасный доступ к виртуальным машинам. Служба позволяет подключаться к виртуальным машинам через RDP или SSH без необходимости открывать общедоступные порты.

### Azure API Management

&emsp; Azure API Management - это служба управления API, которая позволяет организациям создавать, развертывать, защищать и монетизировать свои API. Служба включает в себя набор инструментов и функций, которые упрощают управление API и обеспечивают их безопасность.

### Azure Monitor

&emsp; Azure Monitor - это сервис мониторинга и управления, который позволяет собирать и анализировать данные телеметрии из облачных и гибридных сред. Служба помогает повысить производительность и доступность ресурсов, а также выявить проблемы до того, как они повлияют на работу приложений.

### Azure Backup

&emsp; Azure Backup - это централизованная облачная служба резервного копирования, которая позволяет защитить данные из различных источников, включая виртуальные машины, базы данных и общие папки. Служба включает в себя автоматическое резервное копирование, шифрование и восстановление данных.

### Azure Business Intelligence (Business intelligence)

&emsp; Azure Business Intelligence - это набор инструментов и услуг, которые позволяют компаниям анализировать данные и получать ценные инсайты для принятия бизнес-решений. Служба включает в себя инструменты для сбора, хранения, анализа и визуализации данных.

### Virtual Machines Licenses (Azure Virtual Machines)

&emsp; Azure Virtual Machines Licenses - это услуга, которая позволяет пользователям приобретать лицензии на программное обеспечение Microsoft для использования на виртуальных машинах Azure. Служба позволяет пользователям сэкономить на стоимости лицензий на программное обеспечение.

### Azure Compute Hours (Azure Compute)

&emsp; Azure Compute Hours - это услуга, которая позволяет пользователям оплачивать вычислительные ресурсы Azure по часам. Служба позволяет пользователям оптимизировать затраты на вычислительные ресурсы.

&emsp; Результат заполнения таблицы:

<img width="1418" alt="image" src="https://github.com/Kostik2302/clouds/assets/113085945/30ba85fe-d3a6-4674-a295-77b6bf2527b1">

## Отечественные аналоги

&emsp; В качестве сервиса-аналога был выбран Yandex Cloud, на оффициальном сайте которого есть [таблица с аналогами соответствующих сервисов Microsoft Azure](https://cloud.yandex.ru/docs/overview/platform-comparison/azure). Некоторые аналоги не представлены на сайте и были найдены отдельно.

| Microsoft Azure | Yandex Cloud |
| --- | --- |
| Data Manager | Yandex DataSphere |
| Machine Learning Studio | Yandex DataSphere |
| Azure Bastion | частично Yandex Compute Cloud |
| Azure API Manager | Yandex Cloud API Gateway |
| Azure Monitor | Yandex Monitoring |
| Azure Backup | Yandex Cloud Backup |
| Azure Business Analytics | Yandex Cloud DataLens |
| Asure Virtual Machines Licenses | Yandex Compute Cloud |
| Azure Virtual Machines | Yandex Compute Cloud |

# Выводы

&emsp; В ходе работы были изчучены сервисы Microsoft Azure с использованием информации из официальной документации. Была построена таблица, содержащая подробную информацию о сервисах Microsoft Azure согласно модели ATUM. Были рассмотрены отечественные аналоги в виде сервисов Yandex Cloud и сделан вывод о возможности перехода на них, хоть и не полноценного и бесшовного из-за отсутствия некоторых аналогов.