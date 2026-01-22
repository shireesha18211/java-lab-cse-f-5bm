<img width="456" height="243" alt="Screenshot 2026-01-22 at 2 25 59 PM" src="https://github.com/user-attachments/assets/17617d4c-22e1-451a-b5f0-228a31a62f6a" /><img width="456" height="243" alt="Screenshot 2026-01-22 at 2 25 59 PM" src="https://github.com/user-attachments/assets/6cb3655d-437e-49ef-a816-1b791c08becf" /># experiment2
## TITLE: 2a.) Implement class mechanism in java 
```
class myclass {
void displaymessage() {
System.out.println("welcome to java");
}
int add (int a, int b) {
return a+b;
}
public static void main(String[] args) {
myclass obj = new myclass();
obj.displaymessage();
int result = obj.add(10, 20);
System.out.println("sum: " + result);
}
}
```
# output
<img width="1161" height="479" alt="2a output" src="https://github.com/user-attachments/assets/b054bf48-2b62-490b-91b9-77672713cb8c" />


# experiment 2b
## TITLE: 2b.) java program implement method overloading
```
class OverloadExample {
int add(int a, int b) {
return (a + b);
}
double add(double a, double b) {
return a + b;
}
int add(int a, int b, int c) {
return a + b + c;
}
public static void main(String[] args) {

OverloadExample obj = new OverloadExample();
int sum1 = obj.add(10, 20);
double sum2 = obj.add(5.5, 6.5);
int sum3 = obj.add(10, 20, 30);
System.out.println("Result of adding two integers: " + sum1);
System.out.println("Result of adding two double values: " + sum2);
System.out.println("Result of adding three integers: " + sum3);
}
}
```
# output
<img width="1438" height="403" alt="2b output" src="https://github.com/user-attachments/assets/f3a658b0-9a6e-4d64-a12c-01b26c557aa6" />



