# TrianglePattern.java
This is the Program to print Hollow Triangle as shown below:

![image](https://user-images.githubusercontent.com/84003405/118480569-0b402b00-b730-11eb-9b38-645b8955e938.png)

For this i am declaring 4 variables. Such as i,j,k and rows=5 as I want 5 rows triangle.
Now, we have to write an nested for loop

     for(i=1;i<=rows;i++)
		{
			for(j=i;j<rows;j++)
			{
				System.out.print(" ");
			}
			for(k=1;k<=(2*i-1);k++)
			{
				if(k==1||i==rows||k==(2*i-1))
				{
					System.out.print("*");
				}
				else
				{
					System.out.print(" ");
				}
			}
			System.out.println("");
    
SO, this will be the logic for the Output
