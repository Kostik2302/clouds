# Лабораторная работа №3
Задание: Cделать, чтобы после пуша в ваш репозиторий автоматически собирался докер образ и результат его сборки сохранялся куда-нибудь. (например, если результат - текстовый файлик, он должен автоматически сохраниться на локальную машину, в ваш репозиторий или на ваш сервер).

1) Для удобной работы создаем [отдельный репозиторий](https://github.com/Kostik2302/lab03_rep.git), в котором и будет выполняться задание
   
2) Создаем файл .yml в дирректории .github/workflows, с помощью которого и будет осуществляться пуш сборки на Docker Hub после пуша в репозитории.

   <p align="center">
     <img width="484" alt="image" src="https://github.com/Kostik2302/clouds/assets/113085945/7d75ae86-7a95-4dd5-89b5-e1a309784ea1">
   </p>
   
   Чтобы войтив аккаунт репозитория Docker Hub с нашего репозитория были сгенерированы секреты LOGIN (внезапно логин) и PASSWORD (в него мы кладем токен с Docker Hub).

   <p align="center">
     <img width="787" alt="image" src="https://github.com/Kostik2302/clouds/assets/113085945/9581f594-9adb-4a5a-8dc1-02106ece6722">
   </p>

   <p align="center">
     <img width="1018" alt="image" src="https://github.com/Kostik2302/clouds/assets/113085945/2fa4a6f3-1c0d-4881-a16c-db69a846e8aa">
    </p>
   
3) Добавляем великолепный код "print(14)" (teor.py) и dockerfile, и после пуша видим, что сборка осуществилась и выгрузилась в Docker Hub

   <p align="center">
     <img width="1159" alt="image" src="https://github.com/Kostik2302/clouds/assets/113085945/8f908fa5-e62d-431f-8822-656a04734b75">
   </p>

   <p align="center">
     <img width="714" alt="image" src="https://github.com/Kostik2302/clouds/assets/113085945/1e88cb87-d457-4811-a582-07017b8f9339">
   </p>



