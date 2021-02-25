TroikaDumper
=======
<img src="https://habrastorage.org/getpro/habr/post_images/eb6/453/bad/eb6453bad2e1549fcdc53e73f34bc6ef.png" align="left" width="120" alt="TroikaDumper logo" />
Приложение TroikaDumper позволяет читать, сохранять и восстанавливать записанное состояние памяти карты Тройка.
Для использования необходим телефон с **версией Android ≥ 4.4** и NFC чипом, **поддерживающим карты Mifare.**  
NFC чип должен быть произодства NXP [wikipedia.org/wiki/List_of_NFC-enabled_mobile_devices](https://en.wikipedia.org/wiki/List_of_NFC-enabled_mobile_devices)  
Чипы производства Broadcom и другие работать не будут. 
  
Неполный список поддерживаемых телефонов [supported_phones_list.txt](https://github.com/gshevtsov/TroikaDumper/blob/master/supported_phones_list.txt)

### Инструкция

1. Установите приложение скачав его по ссылке [TroikaDumper.apk](https://github.com/gshevtsov/TroikaDumper/releases/download/0.1/TroikaDumper-0.1.apk)

2. Запустите приложение и поднести карту Тройка.   
Должно отобразится состояние баланса, время последнего прохода и т. д.  
При считывании карты состояние памяти автоматически сохраняется и доступно в архиве (нижняя правая кнопка в виде папки)  

3. Для записи дампа памяти на карту выберите нужный дамп из архива и нажмите кнопку запись.  
Кнопка записи находится левее кнопки архива.

### Как избежать блокировки карты

1. Не оперируйте суммами баланса более 100 рублей

2. Никогда не проходите в метро два раза с одинаковым временем последнего прохода. После записи дампа обновите текущее время на карте используя валидатор в наземном транспорте.
То есть, перед каждым проходом в метро нужно выполнить списание через желтый валидатор в автобусе или трамвае. 


### Интерфейс программы 

![TroikdDumper интерфейс](http://i.imgur.com/GBIf1fW.png)

<!-- prove gshevtsov on 4PDA.ru -->

kotiki spasut mir korobka s karandashami
