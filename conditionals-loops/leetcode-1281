package com.mycompany.conditionalsloops;

public class Number1281 {
    public static void main(String[] args) {
        int n = 234;
        Number1281 n1281 = new Number1281();
        System.out.println(n1281.subtractProductAndSum(n));
    }
    
    public int subtractProductAndSum(int n) {
        int prod = product(n);
        int sum = sum(n);
        return (prod - sum);
    }
    
    public int product(int n) {
        if((n % 10) == n) {
            return n;
        }
        return (n % 10) * product(n / 10);
    }
    
    public int sum(int n) {
        if(n == 0) {
            return 0;
        }
        return (n % 10) + sum(n / 10);
    }
}
