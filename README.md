# employee
employee details
package employee;
 class EmployeeDet{
	 int yr;
	 String name;
	 String address;
	 void insert(int i, String string, String string2) 
	 {
		 yr=i;
		name=string;
		address=string2;
	
	} 
	 void display() {
	              System.out.println(name+"     "+yr+"                  "+address);
	 }
 }
 public class Employee1{
	 public static void main(String[] args){
		 EmployeeDet e1=new EmployeeDet();
		 EmployeeDet e2=new EmployeeDet();
		 EmployeeDet e3=new EmployeeDet();
		 System.out.println("name"+"     "+"year of joining "+"      "+"address");
		 e1.insert(1994,"Robert","64-C WallStreet");
		 e2.insert(2000,"Sam ","68-D WallStreet");
		 e3.insert(1999,"John","23B-WallStreet");
		 e1.display();
		 e2.display();
		 e3.display();
	 }
	 }
		 




