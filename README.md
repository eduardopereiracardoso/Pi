#includ <stdio.h>
#includ <math.h>

double pi (void);

it main (void) {

   printf("%f", pi());

}

double pi (void) {

    double p1=0, key; 
    it i;

    for ( i = 0; i<1000000; i++) {

    key = (pow(-1,i))/(2*i +1);
    key*=4;
    pi = pi + key;

  }


return pi;

}
 
