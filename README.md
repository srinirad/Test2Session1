<br> 0.	Write a program to Print your name. using > 
<br>Expression
<br> 1.	Write a program to Add two numbers
<br> Functions
<br> 2.	Add two number using 4 function	using Pass by value
		<br>int input();
		<br> int add(int a, int b);
		<br> void output(int a, int b, int sum);
		<br> input:
		<br>1
		3r>Add two numbers using 4 functions and  2
		<br> output:
		<br> sum of 1+2 is 3
	
<br>3.	Add two numbers using 4 functions and Pass by reference
		<br> Pass by value
		<br> void input(int *a, int *b);
		<br> void add(int a, int b, int *sum);
		<br> void output(int a, int b, int sum);
		<br> input:
		<br> 1
		<br> 2
		<br> output:
		<br> sum of 1+2 is 3

<br> 5.	Write a program to Compare 3 numbers using 4 functions
	<br> a.	Pass by value	     //int cmp(int a, int b, int c) -> int input ()
	<br> b.	Pass by reference //void cmp(int a, int b, int c, int *large); -> void input (int *a, int *b)
<br> 6.	Write a program to find Sum of n numbers
	<br> a.	Sum of n numbers 
	<br> int input_n();
	<br> int sum_n(int n);
	<br> void output(int n, int sum);
	<br> input: 
	<br> 5
	<br> output:
	<br> 1+2+3+4+5 is 15
	Function Prototypes:
<br> 7.	Write a program to find Sum of n different number
entered by the user
	<br> int input_array_size();
	<br> void input_array(int n, int a[n]);
	<br> int sum_n_arrays(int n, int a[n]);
	<br> void out_put(int n, int a[n], int sum);
	<br> input:
	<br> 1 7 11
	<br> output:
	<br> 1+7+11 is 19
<br> 8. Write a program to find the square root of a number.
	<br> float input();
	<br> float my_sqrt(float n);
	<br> void output(float n, float sqrt_result);
	
<br> 9.	Write a program to Compare two strings
	<br> void input_two_string(char *a, char *b);
	<br> int strcmp(char *a, char *b);
	<br> void output(char *a, char *b, int result);
	<br> input:
	<br> hello 
	<br> world
	<br> output:
	<br> world is greater than hello
	
<br> 10. Write a program to find Sum of two complex numbers
<br> 	struct _complex
	<br> {
	<br> 	float real,imaginary;
	<br> };
	<brtypedef _complex Complex
	<br> Complex input_chellox(); 
	<br> Complex add(Complex a, Complex b);
	<br> void output(Complex a, Complex b, Complex c);
	<br> input:
	<br> 2 3
	<br> 4 5
	<br> output
	<br> 2 + 3i + 4 + 5i is 6 + 8i 
<br> 
<br> 11. Write a program to find Sum of n complex numb<br> ers
	<br> struct _co<br> mplex
	<br> {
		<br> float real,imaginary;
	<br> };
	<br> typedef _complex Complex;
	<br> int get_n();
	<br> Complex input_complex();
	<br> void input_n_complex(int n, Complex c[n]);
	<br> Complex add(Complex a, Complex b);
	<br> Complex add_n_complex(int n, Complex c[n]);
	<br> void output(int n, Complex c[n], Complex result);
<br> 	input:
	2
	<br> 2 + 3i 
	<br> 4 + 5i
	<br> 2 + 3i 
	<br> + 4 + 5i is 
	<br> 6 + 8i
	

