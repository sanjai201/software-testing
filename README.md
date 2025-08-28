// Cast the WebDriver instance to JavascriptExecutor
        JavascriptExecutor js = (JavascriptExecutor) driver;
    // Execute JavaScript to scroll to the bottom of the page
        js.executeScript("window.scrollTo(0, document.body.scrollHeight)");
    

	JavascriptExecutor js = (JavascriptExecutor) driver;
		js.executeScript("arguments[0].scrollIntoView", element);
		Thread.sleep(4000);
