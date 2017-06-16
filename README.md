# TestTask_Shop
Магазин проката спортивных товаров

Исходные данные:
1.	В качестве класса, хранящего единицу товара, используйте класс SportEquipment. (Если необходимо, расширьте иерархию спортивного снаряжения).
public class SportEquipment {
	private Category category;
	private String title;
	private int price;

}
2.	При формировании данных о товарах, которые пользователь взял в прокат, используйте класс RentUnit.
public class RentUnit {
	private SportEquipment[] units;

}
3.	Для хранения всех товаров, доступных для проката в магазине, используйте класс Shop.
public class Shop {
	private Map<SportEquipment, Integer> goods;
// Map-value - количество определенного товара
}
4.	При запуске приложения инициализируйте объект класса Shop данными из файла.

5.	Напишите код, позволяющий взять клиенту до 3-х единиц из проката. 
- Учтите необходимость хранения магазином информации об отданных в прокат товарах. 
- Учтите необходимость поиска требуемой еденицы в магазине.
6.	Реализуйте возможность вывода на консоль отчета о товарах, которые были отданы в прокат, и о товарах, которые сейчас находятся в магазине.
