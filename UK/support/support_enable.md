Створити опори
====

### **Опис**

3D-принтери, що використовують технологію друку розплавленим пластиком працюють, розміщуючи частину розплавленого пластику в зазначених місцях. Якщо цей пластик не підтримувати, він провисне вниз. Тому нависаючі частини моделі зазвичай потребують підтримки додатковою опорною конструкцією, яка буде видалена та викинута після завершення друку.

Цей параметр дає змогу створювати опорні структури для підтримки моделі під час її друку.

![Marking the model red where support is needed](../images/support_enable_prepare_mode.png)
![Support structure (in cyan) to support the model during printing](../images/support_enable.png)

### **Вплив**

Друку підтримок займає значну кількість часу та матеріалів. Крім того, після завершення друку опору потрібно буде зламати або відрізати від моделі. Це має тенденцію залишати сліди на поверхні моделі.

Однак у деяких ситуаціях підтримка все одно необхідна. Наприклад, якщо модель має частину, спрямовану вниз у бік робочого столу, інакше ця деталь просто висітиме в повітрі без підтримки.

Проєктування для запобігання використання підтримок
----

Попри те, що підтримки іноді необхідні, однак їх варто уникати за можливості. Існує багато методів, щоб запобігти використанню підтримок.

* Помістіть свою модель на робочий стіл, а не змушуйте її парити в повітрі.
* Розташуйте свою модель так, щоб у повітрі не було пласких поверхонь.
* Наскільки це можливо, уникайте створення виступів.