package com.javarush.task.task03.task0315;

/* 
Каждый охотник желает знать…
*/

public class Solution {
    public static void main(String[] args) {
        Red red =  new Red();
        Orange orange  = new Orange();
        Yellow yellow = new Yellow();
        Green green = new Green();
        Blue blue = new Blue();
        Indigo indigo = new Indigo();
        Violet violet = new Violet();//напишите тут ваш код

    }

    public static class Red {
        public Red() {
            System.out.print("Red");
        }
    }

    public static class Orange {
        public Orange() {
            System.out.print("Orange");
        }
    }

    public static class Yellow {
        public Yellow() {
            System.out.print("Yellow");
        }
    }

    public static class Green {
        public Green() {
            System.out.print("Green");
        }
    }

    public static class Blue {
        public Blue() {
            System.out.print("Blue");
        }
    }

    public static class Indigo {
        public Indigo() {
            System.out.print("Indigo");
        }
    }

    public static class Violet {
        public Violet() {
            System.out.print("Violet");
        }
    }
}
