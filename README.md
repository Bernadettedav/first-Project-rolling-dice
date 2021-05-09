# first-Project-rolling-dice
package com.company;

import java.util.Random;

public class Main {

    public static void main(String[] args) {
        diceReturn();
    }
    public static void diceReturn() {
        Random myRandom = new Random();
        int myResult = myRandom.nextInt (7) ;
        System.out.println(myResult);
    }
}

