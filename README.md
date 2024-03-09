# one_Led_one_button
#Embedded_Software_Enginner 


#include <reg51.h>


 
sbit LED=P1^0;
sbit Switch=P2^7;
 
 void main(){
	 LED=1;
	 Switch=1;
	 
	 while(1){
		 if(Switch==0){
			 LED=0;
		 }else{
			 LED=1;
		 }
    }
	 }
 
	 
	
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
