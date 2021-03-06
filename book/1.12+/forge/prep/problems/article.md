# Решение проблем

В этой статье разбираются самые распростаненные ошибки, а также способы их решения.

## Ошибка "Use JAVA_HOME (not defined yet)"

Эта ошибка появляется, когда среда не может найти установленный JDK.

Решается проблема элементарно. Для начала, закройте окно импорта и вернитесь к стартовому окну IntelliJ и в правом нижнем
углу нажмите на кнопку "Configure", откройте вкладку "Project Defaults" и выберите пункт "Project Structure".

![Решение JAVA_HOME ошибки - 1](images/setup_gradle_1.png)

В открывшемся окне нажмите на кнопку "New...", которая находится рядом с красной надписью "<No SDK>" и выберите пункт JDK.

![Решение JAVA_HOME ошибки - 2](images/setup_gradle_2.png)

Теперь просто укажите путь к установленной JDK. В моем случае путь следующий `C:\Program Files\Java\jdk1.8.0_121`.

![Решение JAVA_HOME ошибки - 3](images/setup_gradle_3.png)