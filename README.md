# MD5-java
Implementation of MD5 hash algorithm on java


```java
/**
 * File: Main.java
 * Created on 29.12.2022, 8:51:58
 *
 * @author LWJGL2
 */
public class Main {

    public static void main(String[] args) throws Exception {
        String hash = new MD5().getHash(new FileInputStream(new File("time.dat")));
        System.out.println(hash);
    }
}
```
