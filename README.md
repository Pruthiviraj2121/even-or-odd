package com.company;

import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("enetr a number: ");
        int x = sc.nextInt();5

        if(x % 2==0){
           System.out.println(x +" is even");}
        else{
           System.out.println(x +" is odd");}

    }
}
