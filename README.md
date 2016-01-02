# soapui_util

My SoapUI Version : Redy! API 1.5.0 - SoapUI NG (PRO)

<Groovy Script>
* Make_Excel_TestCase  
 - Made out of the test results to Excel(.xlsx)
 - required library : apache poi(Excel)
 - This script is sample. Change to fit into style.
```
String excelPath;  // output file path(.xlsx)
boolean disableFlag;   // diable item is not make
String[] columnHeaders;  // TestCase columnHeaders
private void writeTC(TestStep step, String projectName, String suiteName, String  caseName) // fit TestCase columnHeaders
private void init() // fit TestCase columnHeaders
```
