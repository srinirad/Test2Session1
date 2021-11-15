0.	Write a program to Print your name
1.	Write a program to Add two numbers
Expressions, Functions
3.	Add two number using 4 functions
	a.	Pass by value
	b.	Pass by reference
3.	Write a program to Compare 3 numbers using 4 functions
	a.	Pass by value	     //int cmp(int a, int b, int c) -> int input ()
	b.	Pass by reference //void cmp(int a, int b, int c, int *large); -> void input (int *a, int *b)
4.	Write a program to find Sum of n numbers
	a.	Sum of n numbers 
	int input_n();
	int sum_n(int n);
	void output(int n, int sum);
	input: 
	5
	output:
	1+2+3+4+5 is 15
	
	b.	Using while loop? -> square root
	Function Prototypes:
5.	Write a program to find Sum of n different number entered by the user
	int input_array_size();
	void input_array(int n, int a[n]);
	int sum_n_arrays(int n, int a[n]);
	void out_put(int n, int a[n], int sum);
	input:
	1 7 11
	output:
	1+7+11 is 19
6. 	Write a program to find the square root of a number.
	float input();
	float my_sqrt(float n);
	void output(float n, float sqrt_result);
7.	Write a program to Compare two strings
	void input_two_string(char *a, char *b);
	int strcmp(char *a, char *b);
	void output(char *a, char *b, int result);
	input:
	hello 
	world
	output:
	hello is greater than world
	
9.	Write a program to find Sum of two complex numbers
	struct _complex
	{
		float real,imaginary;
	};
	typedef _complex Complex;
	
	Complex input_complex(); 
	Complex add(Complex a, Complex b);
	void output(Complex a, Complex b, Complex c);
	input:
	2 3
	4 5
	output:
	2 + 3i + 4 + 5i is 6 + 8i

8.	Write a program to find Sum of n complex numbers

	struct _complex
	{
		float real,imaginary;
	};
	typedef _complex Complex;
	int get_n();
	Complex input_complex();
	void input_n_complex(int n, Complex c[n]);
	Complex add(Complex a, Complex b);
	Complex add_n_complex(int n, Complex c[n]);
	void output(int n, Complex c[n], Complex result);
	input:
	2
	2 3
	4 5
	output:
	2 + 3i 
	+ 4 + 5i 
	is 
	6 + 8i


