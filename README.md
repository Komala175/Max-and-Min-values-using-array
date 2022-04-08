# Max-and-Min-values-using-array
  public class Demo{
	public static void main(String[] args) {
	    int a[] ={1,2,7,45,9,8,0,10,98};
	    int max=a[0];
	    int min =a[0];
	    for(int i=1;i<a.length;i++){
	        if(a[i]>max){
	            max=a[i];
	        }
	       
	        if (a[i]<min){
	            min=a[i];
	        }
	    }
		System.out.println("the maximum values is:"+max);
		System.out.println("The minimum values is:"+min);
	}
}
