# fb-
fb automate 
package com.fb;
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import java.util.Scanner;

public class FbloginUser {

	public static void main(String[] args) throws InterruptedException 
	
	{
		
	
	
          WebDriver Driver=new ChromeDriver();
		
		Driver.get("https://www.facebook.com");
		
		Driver.findElement(By.name("email")).sendKeys("0000000");
        Driver.findElement(By.id("pass")).sendKeys("888888888");
	
	    Driver.findElement(By.name("login")).click();
		
	    
		
		
		
		
		
	}

}
package com.fb;
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import java.util.Scanner;

public class FbloginUser {

	public static void main(String[] args) throws InterruptedException 
	
	{
		
	
	
          WebDriver Driver=new ChromeDriver();
		
		Driver.get("https://www.facebook.com");
		
		Driver.findElement(By.name("email")).sendKeys("0000000");
        Driver.findElement(By.id("pass")).sendKeys("888888888");
	
	    Driver.findElement(By.name("login")).click();
		
	    
		
		
		
		
		
	}

}
