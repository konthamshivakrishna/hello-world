# hello-world
Testing Repositiry
public class FirefoxBrowserLaunchDemo {

    public static void main(String[] args) {
        
        //Creating a driver object referencing WebDriver interface
        WebDriver driver;
        
        //Setting webdriver.gecko.driver property
        System.setProperty("webdriver.gecko.driver", pathToGeckoDriver + "\\geckodriver.exe");
        
        //Instantiating driver object and launching browser
        driver = new FirefoxDriver();
        
        //Using get() method to open a webpage
        driver.get("http://artoftesting.com");
        
        //Closing the browser
        driver.quit();
 
    }
 
}
