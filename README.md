# LocacatorsErrors_JS
https://docs.google.com/spreadsheets/d/1x2mwodQNhiS3vL5xeYL1rC5IAwLQVHuj1Gb53y89Buc/edit#gid=0



Verification of information output the locators errors, technology - JavaScript			
# TA locator is invalid.
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocacatorsErrors_JavaScript.git""
2. Run ""node test/specs/initialLocatorWithInvalidTAname.js"""	
* Expected error: TrueAutomation locator ta-Name contains unsupported characters. Please make sure to use only letters, numbers, colon and underscore symbols in locator names.	
* Actual error: TrueAutomation locator ta-Name contains unsupported characters. Please make sure to use only letters, numbers, colon and underscore symbols in locator names.
# Element was not found on the page by initial locator.	"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocacatorsErrors_JavaScript.git""
2. Run ""node test/specs/initialLocatorNotExistOnUsePage.js"""	
* Expected error: NOT_FOUND	
* Actual error: Element was not found on the page. Element 'Practike:Frame:iframe' with such locator is not on this page and could not be detected by TrueAutomation.
# Initial locator is invalid.	"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocacatorsErrors_JavaScript.git""
2. Run ""node test/specs/taLocatorWithInvalidInitialLocator.js"""	"

1) Expected error: Unable to locate element { using: ""css selector"", selector: "".RveJvd snByac"" }
2) Expected error: Unable to locate element { using: ""css selector"", selector: ""//identifierId"" }
3) Expected error: Unable to locate element { using: ""xpath"", selector: ""span[@class='RveJvd snByac']"" }
4) Expected error: Unable to locate element { using: ""link text"", selector: ""//Справка"" }
5) Expected error: Unable to locate element { using: ""css selector"", selector: ""//RveJvd snByac"" }
6) Expected error: Unable to locate element { using: ""css selector"", selector: ""//identifier"" }
7) Expected error: Unable to locate element { using: ""partial link text"", selector: ""//Справка"" }"	"

1) Actual error: Unable to locate element { using: ""css selector"", selector: "".RveJvd snByac"" }
2) Actual error: Unable to locate element { using: ""css selector"", selector: ""*[id=""\/\/identifierId""]"" }
3) Actual error: Unable to locate element { using: ""xpath"", selector: ""span[@class='RveJvd snByac']"" }
4) Actual error: Unable to locate element { using: ""link text"", selector: ""//Справка"" }
5) Actual error: Unable to locate element { using: ""css selector"", selector: "".\/\/RveJvd.snByac"" }
6) Actual error: Unable to locate element { using: ""css selector"", selector: ""*[name=""\/\/identifier""]"" }
7) Actual error: Unable to locate element { using: ""partial link text"", selector: ""//Справка"" }"
# Element was not found on the page by TA locator.	"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocacatorsErrors_JavaScript.git""
2. Run ""node test/specs/taLocatorInDatabase.js"""	
 * Expected error: NOT_FOUND	
 * Actual error: Element was not found on the page. Element 'Translate:Rus1' with such locator is not on this page and could not be detected by TrueAutomation.
# TA locator was not found in database.	"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocacatorsErrors_JavaScript.git""
2. Run ""node test/specs/taLocatorNotInDatabase.js"""	
  * Expected error: NOT_FOUND	
  * Actual error:  There is no such TA Locator in the objects repository. Element 'SmartLocator:Not_in_the_database' was not found in the objects repository of 'TestTA' project.
