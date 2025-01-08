# We use our domail name
### This is some 

`OLED_ShowCHinese(18,0,1);`
```int main(void)
 {	
	uint16_t Counter;
	delay_init();	    	//延时函数初始化,通过Systick中断实现1ms延时功能  
	OLED_Init();//OLED初始化  
	OLED_Clear();//清屏
 

  while (1)
  {	
		OLED_ShowNum(52,6,Counter,3,16);
		Counter++;
		delay_ms(1000);
  }
 }```

![捕获 - 副本](https://github.com/user-attachments/assets/070d2133-df09-42ae-a5d4-d3385e58300f)
