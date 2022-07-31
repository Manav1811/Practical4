# Practical4
package part1;
import java.util.*;
public class Practical4 {
	
	    public static void main(String[] args) {
	        Scanner sc=new Scanner(System.in);

	        System.out.println("Enter no of testcase: ");
	        int t=sc.nextInt();

	        for(int i=0;i<t;i++)
	        {

	            System.out.println("Enter size of array : ");
	            int x=sc.nextInt();
	            int[] a = new int[x];

	            System.out.println("enter array : ");
	            for(int j=0;j<x;j++) {
	                a[j]=sc.nextInt();
	            }
	            int count=0;
	          for(int j=0;j<x-2;j++) {
	              if(a[j] == 1 ) {
	                  if(a[j+1] == 2){
	                      if(a[j+2]==3){
	                          count++;
	                      }
	                  }


	              }
	          }
	          if(count == 1)
	          {
	              System.out.println("true");
	          }
	          else {
	              System.out.println("false");
	          }
	        }

	    	//Created by Manav_21CE063.
	    }
	}


