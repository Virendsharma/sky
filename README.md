 # Virendra Sharma Technical Assesment for QA Role - SKY
 
**Maven**: I have created a Maven project from scratch and added all required depencdencies for the project.
All the Dependencies for Cucumber, Selenium, WebDriver manager, Junits and reports are added.
**Framework followed**: The test suite is in BDD framework using cucumber and junit adhering to all BDD best practices.
**Project structure** It has src---main---java and src---test---java. Under src---main---java I have created 3 packages -- Base, PageObjects and Utils. 
Under src---test---java I have created StepDef, Testrunner and resources. 
Under resources i have created Feature and enviroment.properties.
1)**Base**--I have created a class name called BasePage where all the page objects were initialised in this particular class.
2)**pageObjects**--I have created a package name called pageObjects where all locater are in header and function in body for each web page under test.
3)**utils**--I have created utils package. Under this I have initialised WebDriver and created usable utilities like navigateToUrl, closeDriver, getPageTitle and getUrl.
Under **src--test--java** --- As I have used cucumber BDD the different components like feature, steps and runner packages are maintained. 
1)**feature files** are maintained under **src--test--resources** where all the scenarios are converted into BDD using gherkin language.
2)**steps** has StepDefination class it has selenium code whatever the steps are there in feature file for each and every step there is a mapping. 
3)**Hooks** Hooks class is maintained under steps package.Driver intialisation, Screen shots and teardown methods with @before and @after are maintained in this class. 
**Process for TestExecution**---**TestRunner** TestRunner package has TestRunner class where tests are executable from this class.It contains the location of feature file,steps and cucumber reports this was called inside the plugin.
**Reports**---Whenever the testcases are failed cucumber html report is generated under the target folder--cucumber html report--index.html 





