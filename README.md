## Тема проекта. Государственные деньги для НКО

## Оглавление  
[1. Описание и цель проекта](./README.md#Описание-и-цель-проекта)  
[2. Постановка задачи](./README.md#Постановка-задачи)    
[3. Структура проекта](./README.md#Структура-проекта)  
[4. Как установить проект](./README.md#Как-установить-проект)    
[5. Ссылка на датасет](./README.md#Ссылка-на-датасет)  

### Описание и цель проекта    
НКО хотят повысить свои шансы на получение грантов/госконтрактов от государства. Для этого им важно понять, что именно может повлиять на это. Результаты исследования можно использовать для того, чтобы подсказывать НКО, как повысить шансы на финансовую поддержку.
Цель — спрогнозировать вероятность получения грантов/госконтрактов от государства для организации в зависимости от её характеристик:
* от региона регистрации организации;
* от возраста организации;
* от экономической деятельности организации; 
* от организационно-правовой формы (ОПФ/ОКОПФ);
* от формы НКО;
* от наличия записей организации в соц.сетях (её публичности).

### Постановка задачи
В нашем распоряжении есть дамп данных обо всех НКО России (актуален на 26.08.2021), в котором
содержится информация о получении государственных грантов,
госконтрактов и субсидий, регионе и дате регистрации, а также ОКВЭД
(классификатор экономической деятельности).

Необходимо проверить, есть ли зависимость вероятности получения
грантов/госконтрактов от государства от региона регистрации, возраста, экономической деятельности, а так же, от организационно-правовой формы, от формы НКО и от наличия записей организации в соц.сетях (её публичности).

### Структура проекта
1. Сбор данных
2. 
2.1. Анализ и обработка данных   
2.2. Визуализация данных   
2.3. Кодирование признаков   
2.4. Решение задачи классификации   
2.5. Подготовка модели к продакшену   

### Как установить проект
Выполнить следующие команды в терминале:
1. git clone https://github.com/NadezdaNN/Money_for_NCO.git
2. pip install -r requirements.txt

### Ссылка на датасет
https://drive.google.com/file/d/1T9Hf1MMogOZl8r3KZGfuCbFjbB_SACdz/view?usp=sharing

https://drive.google.com/file/d/1KAHgf-v_zVJ2--KWWn1167jwx0JPnETN/view?usp=sharing
