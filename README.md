# Program-Menyederhanakan-Pecahan
    #include<stdio.h>
    using namespace std;
    int pecahan();
    int main()
    {pecahan();}

    int pecahan ()
    {
        int a,b,l,t;
        printf ( "Masukkan pembilang: ");
        scanf ("%d", &a);
        printf( "Masukkan penyebut: ");
        scanf ("%d", &b);
        t = a/b;
        l = a%b;
        if (a%b == 0)
        printf ("Bilangan (%d/%d) \ndisederhanakan menjadi %d",a,b,t);
        else if (a%b != 0)
            printf ("Bilangan (%d/%d) \ndisederhanakan menjadi (%d %d/%d)",a,b,t,l,b);
    }
   ![img](https://raw.githubusercontent.com/BambangPriam/Program-Menyederhanakan-Pecahan/master/Menyederhanakan%20Pecahan.png)
