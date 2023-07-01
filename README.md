import java.util.*;
public class linearSearch {
    public static int lineearSearch( int numbers[] , int key){
        int i ;

        for( i = 0; i < numbers.length; i++){
            if(numbers[i]==key){
                return i;
            }
        
        }
        return -1;


    }
    public static int getLargest(int numbers[] ,  int largest){
        for( int i =  0; i < numbers.length; i++ ){
            if( numbers[i] > largest)
            
            {
                largest = numbers[i];
            }
        }
        return largest;

    }
    public static void main(String[] args) {
        int numbers[] = {10,20,50,80,45,70,56};
        int largest = Integer.MIN_VALUE;
        int biggest =  getLargest(numbers,largest);       
         System.out.println("The largest val is :" + biggest);
    }
    
}
# linearsearch
