Expressions:

1. Write a program to find length distance between two points.

Expressions and Functions:

2. Write a program to find the weight of the camel given height, length and stomach radius.
weight = pi * stomach_raduius^3 * sqrt(height * length). using four functions and following function signatures. 5 marks

float input_radius();
float input_heigth();
float input_length();
float find_weight(float radius, float height, float length);
void output(float radius, float height, float length, float weight);
and int main()

Expression, Functions and Structures.

3. Write a program to find the weight of the camel given height, length and stomach radius.
weight = pi * stomach_raduius^3 * sqrt(height * length). using four functions and following function signatures. 5 marks
struct camel {
	float radius, height, length,weight;
};
typedef struct camel Camel;
Camel input(); /* do not take weight as input from the user */
float find_weight(Camel c); /* pass by value */
or 
void find_weight(Camel *c); /*passing address variable */
void output(Camel c);
and int main()

 if then else statements

4. When a camel is 

a) sick its stomach_radius is less than height and less than length.
b) happy its height is less than length and less than stomach_radius.
c) tense its length is less than height and stomach_radius.

Write a program to find whether a camel is sick, happy, or tense.
With functions and structure - 5 marks. 

Loops and sequences

5) Write a program to find borga^x given x.
The formula for finding borga^x

1 + x/3! + x^2/5! + x^3/7! .....

stop when the next term is less 0.000001, With four functions - 5 marks.


Array processing
With functions - 5 marks.
use following function prototypes.
void input(int n, int a[n]);
float odd_average(int n, int a[n]);
void output(int n, int a[n]); /* print all the elements of the array and then the average */
and main.

Strings
Write a program to find if the name of the camel is a nice name.
Camels name is nice if it has at least 2 vowels and 2 consonants in it.
with four functions - 5 marks. 


Array of Structures

Write program to find the weight of a truck load of n camels. 
Take input 
a)  truck weight and
b)  height, radius and length of n camels
and compute the total truck weight. ( Truck weight + weight of the camels)
With functions - 5 marks.

Call functions from earlier programs where required.
float input_truck_weight();
int input_no_camels();
void input_camel_details(int n, Camel c[n]);
float comput_total_weight(int n, Camel c[n], float truck_weight);
void ouput(float total_truck_weight);
and 
int main()
