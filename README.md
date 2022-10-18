# python-urban

## О работе
- Дмитриева Виктория Руслановна
- https://colab.research.google.com/drive/1ZTOwug-j2SWYcRsiAPZQLiSDe7aCWWWN#scrollTo=9Dpv_9sEzGV-
- Общее количество объектов культурного наследия, расположенных в Петроградском районе Санкт-Петербурга равно 749.  
- Самое большое количество объектов на улице - 52. Улица - Каменноостровский проспект.   

## Описание
Итоговый проект для расчета количества объктов культурного наследия для улиц в выбранном районе Санкт-Петербурга. 
1. Следует выбрать [район Санкт-Петербурга](https://wiki.openstreetmap.org/wiki/RU:%D0%A1%D0%B0%D0%BD%D0%BA%D1%82-%D0%9F%D0%B5%D1%82%D0%B5%D1%80%D0%B1%D1%83%D1%80%D0%B3/%D0%A0%D0%B0%D0%B9%D0%BE%D0%BD%D1%8B)
1. Выбрать улицы, которые входят в выбранный район.  
  Слой с улицами находится в [Google Drive](https://drive.google.com/file/d/1bUT1E-QSbG1vpSNM2dOG2-LEVXSrPdo3/view?usp=sharing)
1. Выбрать объекты культурного наследия выбранной территории.  
  Слой с объектами культурного наследия находится в репозитории github в файле kgiop_objects.geojson. 
1. Посчитать сколько объектов подадает в заданный буфер вокруг улицы.
1. Результат следует оформить в виде jupyter notebook в google colab.  
  В качестве исходного шаблона задания использовать [данный](https://colab.research.google.com/drive/1nAtzu1yjnkyxot-Hf6beXxoN3-zN9HZ_) файл
1. Загрузить на github итоговый слой с улицами выбранного района и расчитанным количеством объектов культурного наследия. 

## Приступая к работе 
1. Необходимо сделать себе репозиторий используя данный шаблон.  
  ![image](https://user-images.githubusercontent.com/14962819/178701128-479598b3-beda-4a5d-95d4-a169c896c5d9.png)
1. Далее сделать копию [jupyter notebook](https://colab.research.google.com/drive/1nAtzu1yjnkyxot-Hf6beXxoN3-zN9HZ_) к себе в гугл диск.
1. Установить права доступа к jupyter notebook с возможностью комментирования
  ![image](https://user-images.githubusercontent.com/14962819/178701259-c427b7ea-b145-42a8-84ef-1b5829621d6a.png)
1. В файле README.md добавить в разделе "О работе"
  - Указать свои ФИО
  - прикрепить ссылку на colab
1. После копирования исправить все комментарии начинающиеся с todo в jupyter notebook.  
  ![image](https://user-images.githubusercontent.com/14962819/178701711-0aadfb89-3989-453b-b196-c0ca064c801f.png)

## Будет оцениваться:
1. выполнение всех указанных заданий
1. соблюдение рекомендаций PEP8
1. выгрузка итогового слоя в личный репозиторий github
1. последовательность и структурированность 

## Дополнительно:
1. Сопровождение кода ячейчами с текстом, где описывается происходящие действия. Например:
  ![image](https://user-images.githubusercontent.com/14962819/178705338-b81a9d38-6897-4652-a6cd-64d54b1becd9.png)
1. Итоговый вывод в свободной форме о объектах культурного наследия в рассматриваемой территории.  
  Например:
  > ... общее количество объектов культурного наследия ... равно ... .  
  > Самое большое количесво объектов у улицы ...  
  > Топ 5 улиц ...  
  > Среднее количество объектов культурного наследия на одну улицу равно ...  
