# phpunit-webdriver

the power of webdriver reveals when you want to click elements, fill forms, drag and drop elements, etc. That’s why we will write a test that demonstrates some of this features.
<hr>
But how can control the browser? Should we move the mouse in order to click on element? Well, not exactly. WebDriver allows us to locate element on page by its ID, class name, element name, CSS, or XPath. Let’s list all possible locator types, taken from WebDriverBy class:
#
<hr>
. WebDriverBy::className() - searches for element by its CSS class. <br>
. WebDriverBy::cssSelector() - searches for element by its CSS selector (like jQuery).<br>
. WebDriverBy::id() - searches for element by its id.<br>
. WebDriverBy::linkText() - searches for a link whose visible text equals to the value provided.<br>
. WebDriverBy::partialLinkText() - same as above, but link partly contain the value.<br>
. WebDriverBy::tagName() - search for element by its tag name.<br>
. WebDriverBy::xpath() - search for element by xpath. The most complex, yet, most powerful way for element location.<br>
. To find element we should use webDriver->findElement method, with locator specified with  WebDriverBy.<br>
