## Роблячи виконавця

Давайте додамо виконавця до вашої групи!

+ Додайте ще два спрайта на вашу сцену: виконавця та мікрофон.
    
    ![скріншот](images/band-singer-mic.png)

+ Перш ніж ваш виконавець зможе співати, вам потрібно додати звук вашому спрайту. Переконайтеся, що ви вибрали свого виконавця, потім натисніть вкладку Звуки та натисніть ** Вибрати звук із бібліотеки **:
    
    ![скріншот](images/band-import-sound.png)

+ Якщо натиснути кнопку ** Вокал ** на лівій стороні, ви зможете вибрати відповідний звук для вашого спрайту.
    
    ![скріншот](images/band-choose-sound.png)

+ Тепер, коли звук був доданий, ви можете додати цей код до свого виконавця:
    
    ```blocks
        коли клацаєте на спрайт
        відіграти звук [singer1 v] поки не завершиться
    ```

+ Натисніть на свою співачку і подивіться, що станеться. Вона співає?