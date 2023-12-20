# Теоретическое задание №2

# Команда "Шизика фу"

* Долгов Константин - капитан
* Теребов Максим
* Сарычев Сергей

Вариант работы: 2

# Формулировка

Для чего введен термин Infrastructure as a Code? Какие выгоды это несет с точки зрения
автоматизации, безопасности? Предложите набор компонентов, которые нужно использовать при развертывании инфраструктуры как кода.

# Ответ

Введение термина "infrastructure as Code" (IaC) связано со стремлением трансформировать подход к управлению инфраструктурой, обеспечивая ее управление через программный код вместо традиционных методов. Термин (IaC) означает подход к управлению и развертыванию инфраструктуры, при котором инфраструктура описывается и управляется с использованием кода, а не через ручное вмешательство.

## Выгоды IaC:

* Автоматизация: Основной выгодой IaC является возможность автоматизировать процессы создания, масштабирования и управления инфраструктурой. Это ускоряет развертывание, снижает вероятность ошибок и повышает эффективность.

* Безопасность: IaC способствует повышению безопасности, поскольку инфраструктура описывается в виде кода и может быть подвергнута проверке на уязвимости. Код может быть аудитирован на соответствие политикам безопасности, что снижает риск нарушений безопасности.

## Компоненты для развертывания IaC:

* Облачные провайдеры: Использование популярных облачных платформ, таких как Amazon Web Services (AWS), Microsoft Azure или Google Cloud Platform (GCP), обеспечивает удобное управление и автоматизацию развертывания.

* Оркестраторы контейнеров: Использование инструментов типа Kubernetes, Docker Swarm или Apache Mesos для автоматизации развертывания и управления контейнерами на кластерах.

* Инструменты управления конфигурацией: Применение средств вроде Ansible, Puppet, Chef или Terraform, которые позволяют описывать инфраструктуру в виде кода и автоматически управлять ресурсами.

* Системы контроля версий: Использование систем контроля версий, например, Git, для управления версиями кода и совместного использования репозиториев инфраструктуры.

* Системы мониторинга и журналирования: Внедрение инструментов, таких как Prometheus, ELK Stack или Grafana, для отслеживания состояния инфраструктуры и анализа логов, что повышает надежность и обнаружение проблем.

* Системы управления и развертывания ПО: Применение средств типа Jenkins, Travis CI или GitLab CI/CD для автоматизации процессов развертывания и интеграции изменений в инфраструктуре как коде.