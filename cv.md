# Резюме соискателя работы на должность junior front-end

### Личные данные соискателя
![Фото](https://media-exp1.licdn.com/dms/image/C4E03AQHjDOGLOJMrVA/profile-displayphoto-shrink_800_800/0/1516783707631?e=1635984000&v=beta&t=Yt-AiXsNoIFgbDxNJyyCCAepfGTZMLl4cc-vb3jcxUY)
* **First name:** Vitali
* **Second name:** Kamarouski
* **e-mail:** eratnik@gmail.com
* **tel.:** +375293677519

**Краткая информация о себе:**
(ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении и способности быстро учиться и узнавать новое)
**Навыки** (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете)
**Примеры кода**
**Опыт работы:** Junior Dev может указать пройденные курсы и тренинги, перечислить учебные проекты, или проекты, выполненные на фрилансе с указанием использованных навыков и ссылками на исходный код.
**Образование:** юридический факультет ГГУ им.Ф.Скорины, специальность правовое обеспечение бизнеса, онлайн-обучение в The Rolling Scopes.
**Английский язык:** A0
```
public class Main {

    public static void main(String[] args) {
        int[] array = {3, 2, 1};
        int[] arrayTwo = {43, 32, 95, 7, 50, 96, 4, 45, 40, 68, 30, 85, 83, 75, 59, 2, 89, 76, 93, 12, 82, 9, 52, 49, 27, 3, 20, 26, 48};
        bubbleSort(arrayTwo);
    }
    static void bubbleSort (int[] array) {
        int comparisonsDone = 0; //количество сравнений
        int swampsDone = 0; //количество замен
        boolean sorted = false;
        while (!sorted) {
            sorted = true;
            for (int i = 0; i < array.length - 1; i++) {
                printArray(array);
                if (array[i] > array[i + 1]) {
                    int temp = array[i];
                    array[i] = array[i + 1];
                    array[i + 1] = temp;
                    swampsDone++;
                    sorted = false;
                    System.out.println("произведена замена " + array[i + 1] + " на " + array[i] + ", замена является " + swampsDone + " по счету");
                } else {
                    System.out.println("нет смысла меня местами элементы " + array[i] + " и " + array[i + 1]);
                }
                comparisonsDone++;
            }
        }
        System.out.println("Произведено " + comparisonsDone + " проверок" + " и " + swampsDone + " замен");
        System.out.println("Длинна массива составляет " + array.length);
    }
    static void printArray(int[] array) {
        for (int i = 0; i < array.length; i++) {
            System.out.print(array[i]);
            System.out.print(" ");
        }
        System.out.println();
    }
    }
    ```