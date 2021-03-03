public class Main{ 

public static void main(int[]a,int total){

int temp;

for(int i = 0;i < total;i++)

    {
    
        for(int j = i + 1;j < total; j++)
        
        {
        
            if(a[i] > a[j])
            
            {
            
                temp = a[i];
                
                a[i] = a[j];
                
                a[j] = temp;
                
            }
            
        }
       
        
    }
    
    return a[total - 1];
    
}

public static void main(String args[]) {

    int a[] = {1,2,3,9,2,8};
   
    int b[] = {44,69,88,73,15,90,200};
    
    System.out.println("Largest number is:"+getLargest(a,6));
    
    system.out.println("Largest number is:"+getLargest(b,7));
    
}
    
