# Vitali Kamarouski

## **Contact info:**
**Name:** Vitali Kamarouski<br>
**e-mail:** eratnik@gmail.com<br>
**Phone:** +375 (29) 3677519<br>
**GitHub:** [Vitali Kamarouski](https://github.com/eratnik)<br>
---
## **About me:**
I'm a 34 old, I work to tender management specialist in an oil company. I like to learn something new so I decided to learn the frontend. At my work i had an experience to SAP, Directum, data analysis and act as a lecturer.<br>
**Skills:** java (basic), Git/GitHub, html (basic), css (basic).<br>
**Education:** Francysk Skaryna Homiel State University, major - jurisprudence, and now I learn stage 0 The Rolling Scope School.<br>
**Languages:**
Russian - native speaker.<br>
French - A2.<br>
English - A0 (A1 in process…).<br>
----
### Code example: 
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
        System.out.println("Длина массива составляет " + array.length);
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