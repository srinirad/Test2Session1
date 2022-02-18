<br> 1.	Write a program to find the distance between two points
		<br> void input(float \*x1, float \*y1, float \*x2, float \*y2);
		<br> void find_distance(float x1, float y1, float x2, float y2, float *area);
		<br> void output(float x1, float y1,float x2, float y2, float area);
		<br> input:
		<br> 1 1 2 2
		<br> output:
		<br> the distance between point (1.000000,1.000000) and (2.000000,2.000000) is  with 1.4142

<br> 2.	Write a program to whether the three lines form a triangle.
	<br> void input(float \*x1, float \*y1, float \*x2, float \*y2);
	<br> int is_triangle(float x1, float y1, float x2, float y2,float x3, float y3)
	<br> void output(float x1, float y1, float x2, float y2,float x3, float y3)


<br> 3.	Write a program find whether a given number is a prime number. 
	<br> int input_number();
	<br> int is_prime(int n);
	<br> void output(int n, int is_prime);
	<br> input: 
	<br> 3
	<br> output:
	<br> 3 is a prime number.

<br> 4.	Write a program to find nth number in fibonacci sequence.
        <br> Fibonacci sequence consists of 0,1,1,2,3,5,8,13,21........
	<br> int input();
	<br> int find_fibo(int n);
	<br> void output(int n, int fibo);

<br> 5. Write a program to find all the prime numbers between erotosthenes sieve method.
	<br> int input_array_size();
	<br> void init_array(int n, int a[n];
	<br> void erotosthenes_sieve(int n, int a[n]);
	<br> void out_put(int n, int a[n]);
	<br> input:
	<br> 100
	<br> output:
	<br> 2,3,7,11,13,19,23,29,31,...

	
<br> 6.	Write a program to find the index of a substring of a string.
	<br> void input_string(char *a);
	<br> int str_reverse(char *string, char *substring);
	<br> void output(char *string, char *substrint, int index);
	<br> input:
	<br> helloworldhello
	<br> world
	<br> output:
	<br> The index of world in helloworldhello is 5
	
<br> 7. Write a program to find the length of a line.
        <br> struct _point {
	<br>	float x,y;
	<br> };
        <br> typedef struct _point Point;
	<br> struct _line
	<br> {
	<br>	Point p1,p2;
	<br>	float distance;
	<br> };
	<br> typedef struct _line Line
	<br> Point input_point();	
	<br> Line input_line(); 
	<br> void find_length(Line \*l);
	<br> void output(Line l);
	<br> input:
	<br> 0 0 
	<br> 1 1
	<br> output:
	<br> The a

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
	
