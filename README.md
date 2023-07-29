# selenium
Selenium Practice

import dev.failsafe.internal.util.Assert;

public class ACM_login{
	public static void main(String [] args) {


	
		WebDriver driver = new ChromeDriver();
		driver.get("https://www.w3schools.com/java/default.asp");
		
		WebElement Java = driver.findElement(By.xpath("//*[@id=\"main\"]/div[3]/h2"));
		 
		Assertion Assert = new Assertion();
	
		Assert.assertEquals(true,Java.isDisplayed()); 
		
		
		 
	
		}
	
	}
