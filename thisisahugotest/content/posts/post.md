---
title: "first test Post"
date: 2021-07-25T21:20:59-07:00
---

This is some content


```java
import java.util.regex.Matcher;
import java.util.regex.Pattern;

public class RegexExamples {
    public static void main(String[]args) {
        Pattern p = Pattern.compile("\\d+");
        Matcher m = p.matcher("string1234more567string890");
        while(m.find()) {
            System.out.println(m.group());
        }
    }
}
```
