# even-and-odd-digits-of-n-number
public class OddEvenInArrayExample{  
public static void main(String args[]){  
int a[]={2,3,7,6,9,8};  
System.out.println("Odd Numbers:");  
for(int i=0;i<a.length;i++){  
if(a[i]%2!=0){  
System.out.println(a[i]);  
}  
}  
System.out.println("Even Numbers:");  
for(int i=0;i<a.length;i++){  
if(a[i]%2==0){  
System.out.println(a[i]);  
}  
}  
}}
