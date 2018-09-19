siddhi-execution-unitconversion
======================================

The **siddhi-execution-unitconversion extension** is an extension to <a target="_blank" href="https://wso2.github.io/siddhi">Siddhi</a> that enables conversions of length, mass, time and volume units.

Find some useful links below:

* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-unitconversion">Source code</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-unitconversion/releases">Releases</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-unitconversion/issues">Issue tracker</a>

## Latest API Docs 

Latest API Docs is <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16">1.0.16</a>.

## How to use 

**Using the extension in <a target="_blank" href="https://github.com/wso2/product-sp">WSO2 Stream Processor</a>**

* You can use this extension in the latest <a target="_blank" href="https://github.com/wso2/product-sp/releases">WSO2 Stream Processor</a> that is a part of <a target="_blank" href="http://wso2.com/analytics?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">WSO2 Analytics</a> offering, with editor, debugger and simulation support. 

* This extension is shipped by default with WSO2 Stream Processor, if you wish to use an alternative version of this extension you can replace the component <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-unitconversion/releases">jar</a> that can be found in the `<STREAM_PROCESSOR_HOME>/lib` directory.

**Using the extension as a <a target="_blank" href="https://wso2.github.io/siddhi/documentation/running-as-a-java-library">java library</a>**

* This extension can be added as a maven dependency along with other Siddhi dependencies to your project.

```
     <dependency>
        <groupId>org.wso2.extension.siddhi.execution.unitconversion</groupId>
        <artifactId>siddhi-execution-unitconversion</artifactId>
        <version>x.x.x</version>
     </dependency>
```

## Jenkins Build Status

---

|  Branch | Build Status |
| :------ |:------------ | 
| master  | [![Build Status](https://wso2.org/jenkins/job/siddhi/job/siddhi-execution-unitconversion/badge/icon)](https://wso2.org/jenkins/job/siddhi/job/siddhi-execution-unitconversion/) |

---

## Features

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#mmtokm-function">MmTokm</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input megameters into kilometers</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#cmtoft-function">cmToft</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input centimeters into feet</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#cmtoin-function">cmToin</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input centimeters into inches</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#cmtokm-function">cmTokm</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input centimeters into kilometers</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#cmtom-function">cmTom</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input centimeters into meters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#cmtomi-function">cmTomi</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input centimeters into miles</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#cmtomm-function">cmTomm</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input centimeters into millimeters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#cmtonm-function">cmTonm</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input centimeters into nanometers</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#cmtoum-function">cmToum</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input centimeters into micrometers</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#cmtoyd-function">cmToyd</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input centimeters into yards</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#dtoh-function">dToh</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input days into hours</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#gtokg-function">gTokg</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input grams into kilograms</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#gtomg-function">gTomg</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input grams into milligrams</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#gtoug-function">gToug</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input grams into micrograms</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#htom-function">hTom</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input hours into minutes</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#htos-function">hTos</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input hours into seconds</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kgtolt-function">kgToLT</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilograms into imperial tons</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kgtost-function">kgToST</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilograms into US tons</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kgtog-function">kgTog</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilograms into grams</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kgtolb-function">kgTolb</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilograms into pounds</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kgtooz-function">kgTooz</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilograms into ounces</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kgtost-function">kgTost</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilograms into imperial stones</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kgtot-function">kgTot</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilograms into Tonnes</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kmtocm-function">kmTocm</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilometers into centimeters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kmtoft-function">kmToft</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilometers into feet</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kmtoin-function">kmToin</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilometers into inches</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kmtom-function">kmTom</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilometers into meters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kmtomi-function">kmTomi</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilometers into miles</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kmtomm-function">kmTomm</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilometers into millimeters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kmtonm-function">kmTonm</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilometers into nanometers</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kmtoum-function">kmToum</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilometers into micrometers</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#kmtoyd-function">kmToyd</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input kilometers into yards</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#ltom3-function">lTom3</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input liters into cubic meters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#ltoml-function">lToml</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input liters into milliliters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#m3tol-function">m3Tol</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input cubic meters into liters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#mtocm-function">mTocm</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input meters into centimeters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#mtoft-function">mToft</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input meters into feet</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#mtomm-function">mTomm</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input meters into millimeters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#mtos-function">mTos</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input minutes into seconds</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#mtoyd-function">mToyd</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input meters into yards</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#mitokm-function">miTokm</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input miles into kilometers</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#mltol-function">mlTol</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input milliliters into liters</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#stoms-function">sToms</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input seconds into milliseconds</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#stons-function">sTons</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input seconds into nanoseconds</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#stous-function">sTous</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input seconds into microseconds</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#ttog-function">tTog</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input Tonnes into grams</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#ttokg-function">tTokg</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input Tonnes into kilograms</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-unitconversion/api/1.0.16/#ytod-function">yTod</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#function">(Function)</a>*<br><div style="padding-left: 1em;"><p>Converts the input years into days</p></div>

## How to Contribute
 
  * Please report issues at <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-unitconversion/issues">GitHub Issue Tracker</a>.
  
  * Send your contributions as pull requests to <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-unitconversion/tree/master">master branch</a>. 
 
## Contact us 

 * Post your questions with the <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">"Siddhi"</a> tag in <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">Stackoverflow</a>. 
 
 * Siddhi developers can be contacted via the mailing lists:
 
    Developers List   : [dev@wso2.org](mailto:dev@wso2.org)
    
    Architecture List : [architecture@wso2.org](mailto:architecture@wso2.org)
 
## Support 

* We are committed to ensuring support for this extension in production. Our unique approach ensures that all support leverages our open development methodology and is provided by the very same engineers who build the technology. 

* For more details and to take advantage of this unique opportunity contact us via <a target="_blank" href="http://wso2.com/support?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">http://wso2.com/support/</a>. 
