# Employee-class-and-object-
Assignment 

Namespace Employeetest
{
  class employee
  {
    public string FirstName ( get;set; )
    public string LastName ( get;set; )
    privae decimal salary;
    
    //constructor 
     Public Employee (sting FirstName, string lastname,deciml salary)
     {
       First Name= First name;
       last Name= last name;
       salary= salary;
       
     }
     Public decimal salary
     {
       get( return-salary; )
       set
       {
         If( value > = 0 )
         salary = value;
       }
     }
   }
}




#include<iostream>  
  
using namespace std; 
  
class program 
{
  static void Main (string []orgs)
  {
    Employee. Employee 1 = new employee("Olumide",(decimal)1000);
    Employee. Employee 2 = new Employee("Seun",(decimal)2000);
    console.Writeline ("Employee 1 Firstname"{0}".,employee1.FirstName);
    Console.WriteLine ("Employee 1 salary:(0:C)".,Employee1.salary);
    
    console.Writeline ("Employee 2 Firstname"{0}",employee2.FirstName);
    Console.WriteLine ("Employee 2 salary:(0:C)",Employee2.salary);
    
    console 'Readline'(); 
  }
}
