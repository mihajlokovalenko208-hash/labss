## Звіт з лабараторної роботи №3  ##

Після встановлення Node.JS я запустив командний рядок та вивів версію Node.JS і версію пакетного менеджера через команди node -v і npm -v.

![](media/Screenshot_2.png)

Далі я запустив Node-Red. Там я розмістив вузли і зробив розгортання.


![](media/Screenshot_1.png)
![](media/Screenshot_3.png)

Тут я налаштував вузол Inject на періодичне оновлення.

![](media/Screenshot_4.png)

Тут я налаштував вузол Inject на текстове повідомлення.

![](media/Screenshot_5.png)

Зробивши програму з використанням вузлів "Change", "Delay" та "Function", debug 1 виводив слова із затримкою в одну секунду. А debug 2 виводив Дату та час з проміжком у п'ять секунд.

![](media/Screenshot_18.png)
![](media/Screenshot_6.png)
![](media/Screenshot_7.png)

Далі я встановиви новий вузол "node-red-contrib-os", і зробив невеличку команду з використанням NetworkIntf

![](media/Screenshot_8.png)
![](media/Screenshot_9.png)

Тут я створив фрагмент коду для того щоб виводився тільки перелік MAC адрес для мережних карт.

![](media/Screenshot_10.png)

Експорт фрагменту потоку у форматі JSON.

![](media/Screenshot_11.png)
![](media/Screenshot_12.png)

Тут я створив папку "flowstartlab" для того щоб перенести туди файли "flows.json" та "flows_cred.json", після чого в мене Відкрився повністю порожній потік. А потім додавши вузол Inject (можна додати будь-який інший), у папці ".node-red" з'явився файл "flows.json".


![](media/Screenshot_13.png)
![](media/Screenshot_14.png)
![](media/Screenshot_15.png)

Далі я переніс файли з папки "flowstartlab" у папку ".node-red", після чого в мене повернулися мої потоки.


![](media/Screenshot_16.png)
![](media/Screenshot_17.png)
 - [Потоки](lab3.json)