# Constructor-and-accessing-methods-//Program to access all the constructors

class Code{

   void m3(){

        System.out.println("I am m3 constructor");

    }

    void m2(){

        System.out.println("I am m2 constructor");

       m3();

    }

    void m1(){

        System.out.println("I am m1 constructor");

       m2();

    }

    public static void main(String... args){

        new Code().m1();

    }

}

/*

I am m1 constructor

I am m2 constructor

I am m3 constructor

 */
