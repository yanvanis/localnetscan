! ВНИМАНИЕ !

ДАННАЯ ПРОГРАММА СКАНИРУЕТ IP АДРЕС/АДРЕСА ТОЛЬКО В ЛОКАЛЬНОЙ СЕТИ, В КОТОРОМ НАХОДИТСЯ САМА ПРОГРАММА

--------------------

Localnetscan - данная программа проверяет существование устройства по IP в локальной сети. Программа выводит таблицу с IP и MAC адресами отвеченных устройств. Также можно указать диапозон IP, тогда получится сканер локальной сети :). Обязательно вместе с .exe или .py файлом должен быть файл localnetscan-config.json, иначе ничего работать не будет. Но если данного файла нету рядом с программой, то программа сама его создаст. В файле конфигурации 3 пункта:                                                                 
{                                                                                              
    "timeout": [время в секундах], <- отвечает за время ожидания ответа устройства/устройств.  
    "writeDataInJson": true/false, <- отвечает за запись выходных данных в json файл.          
    "logo": true/false <- отвечает за вывод логотипа после запуска программы.                  
}                                                                                              

В поле, где просят указать IP, можно ввести help, тогда вызовется справка. (простите за корявое описание (если оно таковым и яляется)
