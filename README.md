# lvzekun
//lvzekun 3/7/2016
package size;
import java.lang.*;

public class Size {
	public static void main(String []args){
		//生成随机数符号
		int i,j;
		for(i=0;i<30;i++)
		{
		String  s[]={"+","-","*","/"};
		int c=(int)(Math.random()*3);
		String d=s[c];
		
		
		
		int a=(int)(Math.random()*99);
		int b=(int)(Math.random()*99);
		
		//判断ab,分为整数，分数
		
		
		j=(int)(Math.random()*2)+1;
		if(j==1)//整数
		{
			if(c==3){
				if(b!=0)
				{System.out.println(a+d+b+"=");}
			}
			else 
			{System.out.println(a+d+b+"=");}
				
			
		}
		if(j==2)//真分数
		{
			int num1,num2;//充当分母
			num1=(int)(Math.random()*98)+1;
			num2=(int)(Math.random()*98)+1;
			if(c==3){
				if(b!=0)
				{   if(c==2)
				      {
					    System.out.println("("+a+"/"+num1+")"+d+"("+b+"/"+num2+")"+"=");
				      }
				    else
					     System.out.println(a+"/"+num1+d+b+"/"+num2+"=");
				}
					
			}
			else
			{if(c==2)
		      {
			    System.out.println("("+a+"/"+num1+")"+d+"("+b+"/"+num2+")"+"=");
		      }
		    else
			     System.out.println(a+"/"+num1+d+b+"/"+num2+"=");
			}
			
			
		}
		
			
		}
		
		
		}
		
		
	

	
	}

	


