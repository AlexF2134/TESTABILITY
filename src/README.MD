# Задание 1. Мили - модернизация (обязательное к выполнению)
### класс Main.java
    public class Main {

    public static void main(String[] args) {
        int ticketPrice = 2_000;
        int milePrice = 20;

        int bonus = (ticketPrice / milePrice);
        System.out.println(bonus);
    }
    }

### класс BonusMilesService

    public class BonusMilesService {
    public int calculate(int price) {
        int cost = 20;
        int miles = (price / cost);
        return miles;
    }
    }
