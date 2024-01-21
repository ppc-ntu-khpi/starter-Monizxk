## Завдання 1. Створення та запуск першої програми (сорочки)
 Код програми
```java
public class Shirt {
  public int shirtID = 35; // стандартне значення номера моделі сорочки
  public String description = "круто, класно, модно"; // стандартний опис сорочки
  // коди кольорів: R=червоний, B=синій, G=зелений, U=невідомо
  public String colorCode = "red";
  public double price = 12.5; // стандартна вартість сорочки
  public int quantityInStock = 50; // стандартна кількість на складі
  
  // цей метод просто виводить всю інформацію про сорочку на екран
  public void displayShirtInformation() {
    System.out.println("Shirt ID: " + shirtID);
    System.out.println("Shirt description:" + description);
    System.out.println("Color Code: " + colorCode);
    System.out.println("Shirt price: $" + price);
    System.out.println("Quantity in stock: " + quantityInStock);
  } // кінець методу displayShirtInformation
} // кінець опису класу
```
Результат

![](/Solution/task1.png)