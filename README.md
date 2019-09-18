package sample;

public class LargestNumber {
    public static void main(String[] args) {
    int[] array = {28,4,14,5,23,56,3,57};
    int val=array[0];

    for(int i=0; i<array.length; i++){
        if(array[i]>val){
            val=array[i];
            }
         }
        System.out.println("Largest number in this array is : " + val);
    }
}
