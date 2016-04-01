# Gradient-Boosted Trees with Mllib
Gradient-Boosted Trees (GBTs) are a type of ensemble classification algorithm that uses decision trees to build a predictive model.  GBTs can take numeric or categorical input variables and can classify a binary target variable or predict a numeric target with regression.  

Learn more about this implementation [from the MLlib Documentation][4]

![Stream](https://raw.githubusercontent.com/IBMPredictiveAnalytics/Gradient_Boosted_Trees_with_MLlib/master/screenshots/stream.png)


---
Requirements
----
-	SPSS Modeler v18.0 or later
- [Python 2.7 Anaconda Distribution](https://www.continuum.io/downloads)

More information here: [IBM Predictive Extensions][2]

---
Installation Instructions
----

#### Initial one-time set-up for PySpark Extensions

If using v18.0 of SPSS Modeler, navigate to the options.cfg file (Windows default path: C:\Program Files\IBM\SPSS\Modeler\18.0\config).  Open this file in a text editor and paste the following text at the bottom of the document:

  eas_pyspark_python_path, "*C:/Users/IBM_ADMIN/Anaconda/python.exe*"

  -   The italicized path should be replaced with the path to your python.exe from your Anaconda installation.

#### Extension Hub Installation
1. Go to the Extension menu in Modeler and click "Extension Hub"
2. In the search bar, type the name of this extension and press enter
3. Check the box next to "Get extension" and click OK at the bottom of the screen
4. The extension will install and a pop-up will show what palette it was installed to

#### Manual Installation
1.	[Save the .mpe file][3] to your computer
2.	In Modeler, click the Extensions menu, then click Install Local Extension Bundle
3.	Navigate to where the .mpe was saved and click open
4.	The extension will install and a pop-up will show what palette it was installed

---
License
----

[Apache 2.0][1]

---
Contributors
----
- Nial McCarrol - ([www.mccaroll.net](http://www.mccarroll.net/))
- Greg Filla ([gdfilla](https://twitter.com/gdfilla))


[1]: http://www.apache.org/licenses/LICENSE-2.0.html
[2]:https://developer.ibm.com/predictiveanalytics/downloads
[3]:https://github.com/IBMPredictiveAnalytics/Gradient_Boosted_Trees_with_MLlib/releases/download/1.0.0/GradientBoostedTreeswithMLlib.mpe
[4]:http://spark.apache.org/docs/latest/mllib-ensembles.html#gradient-boosted-trees-gbts
