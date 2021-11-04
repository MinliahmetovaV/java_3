``` java
public class Main {
    public static void main(String[] args) {
        int current_account = 100;
        int translation = 11560;
        int bonus;
        if (translation >= 1000) {
            bonus = translation / 100;
        } else {
            bonus = 0;
        }
        int balance = current_account + translation + bonus;
        System.out.println(balance);
    }

}
```
![image](https://user-images.githubusercontent.com/89097241/140378788-8ece6572-2e84-436b-9fa3-73846c1d36e3.png)