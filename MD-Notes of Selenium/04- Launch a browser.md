**How to create a simple selenium project to launch a browser:**

1. Integrate Selenium with java Project.

1. In src folder create a package and create a class inside the package.

![](Aspose.Words.8d1b7c0f-bd39-4af6-9019-7c19ef769a5e.001.png)

1. Inside a class create a Main Method.

![](Aspose.Words.8d1b7c0f-bd39-4af6-9019-7c19ef769a5e.002.png)

1. Set the property of the browser and indicate the location of the browsers.

`    `Syntax : System.*setProperty*(key, value);

`  `Here System is a class & setProperty is a static method.

**Key** – “webdriver.chrome.driver” à Chrome Browser

**Key** – “webdriver.gecko.driver”  à Fire Fox Browser

**Key** – “webdriver.ie.driver”     à Internet Explorer

**Value** – Within double quotes copy and paste the location of the WebDriver file for corresponding browser.

1. WebDriver is an interface.

`  `Syntax : Interface ref = new classname();

`           `WebDriver driver  = new ChromeDriver();

1. Use a method called “get” to launch the URL

`     `WebDriver driver = new ChromeDriver();

`     `driver.get(“URL”);

![](Aspose.Words.8d1b7c0f-bd39-4af6-9019-7c19ef769a5e.003.png)


