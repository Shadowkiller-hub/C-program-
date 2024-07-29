Program1: program to display largest of 2 numbers


import java.io.*;

public class Lab1

{

public static void main (String []args) throws IOException

{

int x,y;

DataInputStream ds = new DataInputStream(System.in);

System.out.println("Enter X and Y value");

x = Integer.parseInt(ds.readLine());

y = Integer.parseInt(ds.readLine());

if(x > y)

System.out.println(" Largest is X with value "+x);

If(y>x)

System.out.println(" Largest is Y with value "+y);
}
}




