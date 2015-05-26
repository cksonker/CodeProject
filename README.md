# CodeProject
This is sample practice project
/**
 * 
 */
package com.onemobility;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.firefox.FirefoxDriver;
import com.onemobility.ValidateLoginTest;

/**
 * @author Samurai
 *
 */

public class LoginPageRedirectionTest{
	
	 public static void main(String[] args) throws Exception {
	        WebDriver driver = new FirefoxDriver();
	        driver.get("https://ap15.1memm.com");
	        ValidateLoginTest valLogTest = new ValidateLoginTest();
	        valLogTest.validateLogin(driver);
	 }

}

