# Day 1: Data Types

**[Click here to view the problem description](https://www.hackerrank.com/challenges/30-data-types/problem)**

*@nishipalrana*

```
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {
	
    public static void main(String[] args) {
        int i = 4;
        double d = 4.0;
        String s = "HackerRank ";
		
        Scanner scan = new Scanner(System.in);

        int j=scan.nextInt();
        double e=scan.nextDouble();
        scan.nextLine();
        String str=scan.nextLine();

        System.out.println(i+j);
        System.out.println(d+e);
        System.out.println(s+str);
        scan.close();
    }
}
```
