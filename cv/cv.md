Dmitriy Yushkin

Contact Info
*Tashkent, Uzbekistan*
*telegram*: [@crusader]http://t.me/crusader
*e-mail:* [d.yushkin93@gmail.com](mailto:d.yushkin93@gmail.com)
[github](https://github.com/dyushkin93)

Summary
I am interested in beginning a career in front-end development. My current goal is to get enough skills of developing websites to start my career from junior front-end developer. For today I have some knowledge in math and computer sciences that should help me to learn faster.

Skills
I have basics skills in:
* C++
* HTML & CSS
* JavaScript
* Git
* OOP
* BEM

Code example
Here is my lates work in C++ at my University
```c++
//Программирование с использованием подпрограммы общего вида типа PROCEDURE
//Сортировка элементов матрицы и вывод их суммы
#include <iostream>
#include <math.h>
#include <iomanip>
using namespace std;
double sort(double **a,const int n, const int m);
double matr(double **a,const int n, const int m);  
int main()
{
	int n,m,c,d;
	cout<<"\nVvedite kol.strok i stol matritsy A ";
	cin>>n>>m;
	cout<<"n="<<n<<"  "<<"m="<<m;
	cout<<"\nVvedite kol.strok i stolb matritsy B ";
	cin>>c>>d;
	cout<<"c="<<c<<" d="<<d;
	int i,j;
	double **a=new double *[n];
	for (i=0; i<n; i++)
          a[i]= new double [m];
	double **b=new double *[c];
	for (i=0; i<c; i++)
          b[i]= new double [d];
	cout<<"\nVvedite matrisu A\n";
	for(i=0; i<n; i++)
		for(j=0; j<m; j++)
			cin>>a[i][j];
	cout<<"\nVvedite matrisu B\n";
	for(i=0; i<c; i++)
		for(j=0; j<d; j++)
			cin>>b[i][j];
	cout<<"\n\n";
	**a=sort(a,n,m);
	**b=sort(b,c,d);
	double suma=0,sumb=0;
	for(i=0;i<n;i++)
		suma+=a[i][m-1];
	for(i=0;i<c;i++)
		sumb+=b[i][d-1];
	matr(a,n,m);
	cout<<"\n\n";
	matr(b,c,d);
	cout<<"\nsumA="<<suma<<" sumB="<<sumb; 
	system("pause");
	return 0;
}
double sort(double **a, const int n, const int m)
{
	int c,i,j,x;
	for(i=0;i<n;i++)
		for(x=1; x<m; x++)
			for(j=0;j<m-x;j++)
				if (a[i][j]>a[i][j+1])
				{
					c=a[i][j];
					a[i][j]=a[i][j+1];
					a[i][j+1]=c;
				}
	return **a;
}
double matr(double **a,const int n,const int m)
{
	int i,j;
	for(i=0; i<n; i++)
	{
		for(j=0; j<m; j++)
			cout<<setw(4)<<a[i][j]<<"   ";
		cout<<endl;
	}
	return **a;
}
```
Experience
My first self-study project in web-development https://github.com/dyushkin93/rep_1 (not finished due to lack of motivation).

Education
* 2009-2012 2nd Academic lyceum under the Tashkent University of IT, junior programmer
* 2012-2016 I.M. Gubkin Russian State University of Oil and Gas, bachelor degree in Petroleum Engineering
* 2019 Auditor of the health and environmental management system ISO 45001, 14001


English
I used to learn English in lyceum and University. I used it while studying and continue on my current job.