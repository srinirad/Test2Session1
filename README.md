<br> 1.	Write a program to find the area of a triangle using following function signatures.
		<br> void input(float *base, float *height);
		<br> void find_area(float base , float height, float *area);
		<br> void output(float base, float height, float area);
		<br> input:
		<br> 1
		<br> 2
		<br> output:
		<br> the area of the traingle with base 1.000000 and height 2.000000 is 1.000000

<br> 2.	Write a program to find if a triangle is scalene. A triangle is a scalene traingle if all the
three sides of the triangle are not equal to each other.

	<br> int input_side()
	<br> int check_scalene(int a, int b, int c)
	<br> void output(int a, int b, int c, int isscalene)


<br> 3.	Write a program find whether a number is a composite number. A Composite number has a factor other than
1 and itself
	<br> int input_number();
	<br> int is_composite(int n);
	<br> void output(int n, int composite);
	<br> input: 
	<br> 8
	<br> output:
	<br> 8 is a composite number.

<br> 4.	Write a program to find Sum of composite number in an array of numbers different containing numbers entered by the user.
	<br> int input_array_size();
	<br> void input_array(int n, int a[n]);
	<br> int sum_composite_numbers(int n, int a[n]);
	<br> void out_put(int sum);
	<br> input:
	<br> 1 2 7 8 12
	<br> output:
	<br> 20
<br> 5. Write a program to find gcd (hcf) of two numbers.
	<br> int input();
	<br> int gcd(int a, int b);
	<br> void output(int a, int b, int gcd);
input:
12 16
output
4
	
<br> 6.	Write a program to reverse a string.
	<br> void input_string(char *a);
	<br> char *str_reverse(char *a);
	<br> void output(char *a,char *reversea);
	<br> input:
	<br> hello 
	<br> output:
	<br> olleh
	
<br> 7. Write a program to find the area of a triangle
	<br> struct _triangle
	<br> {
	<br> 	float base,altitude,area;
	<br> };
	<brtypedef _triangle Triangle
	<br> Triangle input_triangle(); 
	<br> void find_area(Traingle *t);
	<br> void output(Triangle t);
	<br> input:
	<br> 2 3
	<br> output:
	<br> The area of triangle wwith base = 2.000000 and altitude = 3.000000 is 3.000000

<br> 8. Write a program to find the triangle with smallest area in n given triangles.
	<br> struct _triangle
	<br> {
	<br> 	float base,altitude,area;
	<br> };
	<br> typedef _triangle Triangle
	<br> int input_n();
	<br> Triangle input_triangle(); 
	<br> void input_n_triangles(int n, triangle t[n]);
	<br> void find_area(Triangle *t);
	<br> void find_areas_n(int n, Triangle t[n]);
	<br> Triangle find_smallest_triangle(int n, Triangle t[n]);  
	<br> void output(int n, Triangle t[n], Triangle smallest);
	<br> void 
	<br> input:
	<br> 2 3
	<br> 4 6
	<br> the smallest of triangles with base and height
	<br> 2,3 and
        <br> 4,6
	<br> is
        <br> triangle with base 2.000000, 3.000000 is 3.000000
	<br> The area of triangle wwith base = 2.000000 and altitude = 3.000000 is 3.000000
	
