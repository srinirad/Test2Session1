<br> 1.	Write a program to find the distance between two points
		<br> void input(float \*x1, float \*y1, float \*x2, float \*y2);
		<br> void find_distance(float x1, float y1, float x2, float y2, float *area);
		<br> void output(float x1, float y1,float x2, float y2, float area);
		<br> input:
		<br> 1 1 2 2
		<br> output:
		<br> the distance between point (1.000000,1.000000) and (2.000000,2.000000) is  with 1.4142

<br> 2.	Write a program to find whether the three points form a triangle.
	<br> void input_triangle(float \*x1, float \*y1, float \*x2, float \*y2, float \*x3, float \*y3);
	<br> int is_triangle(float x1, float y1, float x2, float y2,float x3, float y3)
	<br> void output(float x1, float y1, float x2, float y2,float x3, float y3, int istriangle)


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
	<br> int str_reverse(char \*string, char \*substring);
	<br> void output(char \*string, char \*substring, int index);
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
	
<br> 8. Write a program to find the permeter of a polygon
	<br> struct _point {
	<br>	float x,y;
	<br> };
        <br> typedef struct _point Point;
	<br> struct _line
	<br> {
	<br>	Point p1,p2;
	<br>	float distance;
	<br> };
	<br> struct _line Line;
	<br> struct _polygon {
        <br>   int n;
	<br>   Line l[100];
	<br>   float perimenter;
	<br> }
	<br> int input_n();
	<br> int input_polygon( int n, Polygon \*p);
	<br> Line input_line();
	<br> void input_n_lines(int n, Line l[n]);
	<br> void find_perimeter(Polygon \*p);
	<br> void output(Polygon p);

