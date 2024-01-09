<h1 align="center" style="border-botom: none">
  <b>
  🐍 EIOPA RFR (Risk free curve) test 🐍
 </b>
</h1>

</br>

Every month, EIOPA releases their technical information on the risk free rate term structure that (re)insurers need to use to calculate their technical provisions. This test recalculates the risk-free curve using the parameters that are claimed to be used.

## This example
In this example, we look at the EIOPA risk free rate publication for each month starting from December 2021 onward. The publication can be found [EIOPA RFR website](https://www.eiopa.europa.eu/tools-and-data/risk-free-interest-rate-term-structures_en).

## Smith&Wilson algorithm

The implementation of the SW algorithm is a slight modification to the original OSM implementation. The original implementation can be found in different languages on the OSM's GitHub repository:
-  [Python](https://github.com/open-source-modelling/insurance_python/tree/main/Smith%26Wilson)
-  [Matlab](https://github.com/open-source-modelling/insurance_matlab/tree/main/Smith%26Wilson)
-  [JavaScript](https://github.com/open-source-modelling/insurance_javascript/tree/main/Smith-Wilson)

| Date                     | Repository                          |
| -------------------------| ----------------------------------- |
| 31 August 2023           | [August 2023 repository]            |
| 31 July 2023             | [July 2023 repository]              |
| 30 June 2023             | [June 2023 repository]              |
| 31 May 2023              | [May 2023 repository]               |
| 30 April 2023            | [April 2023 repository]             |
| 31 March 2023            | [March 2023 repository]             |
| 28 February 2023         | [February 2023 repository]          |
| 31 January 2023          | [January 2023 repository]           |
| 31 December 2022         | [December 2022 repository]          |
| 30 November 2022         | [November 2022 repository]          |
| 31 October 2022          | [October 2022 repository]           |
| 30 September 2022        | [September 2022 repository]         |
| 31 August 2022           | [August 2022 repository]            |
| 31 July 2022             | [July 2022 repository]              |
| 30 June 2022             | [June 2022 repository]              |
| 31 May 2022              | [May 2022 repository]               |
| 30 April 2022            | [April 2022 repository]             |
| 31 March 2022            | [March 2022 repository]             |
| 28 February 2022         | [February 2022 repository]          |
| 31 January 2022          | [Jenuary 2022 repository]           |
| 31 December 2021         | [December 2021 repository]          |

[August 2023 repository]: https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/23_August
[July 2023 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/23_July
[June 2023 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/23_June
[May 2023 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/23_May
[April 2023 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/23_April
[March 2023 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/23_March
[February 2023 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/23_February
[January 2023 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/23_January
[December 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_December
[November 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_November
[October 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_October
[September 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_September
[August 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_August
[July 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_July
[June 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_June
[May 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_May
[April 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_April
[March 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_March
[February 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_February
[Jenuary 2022 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/22_January
[December 2021 repository]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test/21_December

Queries and suggestions; gregor@osmodelling.com

## 🚀 Getting started
Before using Jupyter Notebook, it is recommanded to instal Anaconda. One of the sources that could be usefull to do that is: 

https://docs.anaconda.com/free/anaconda/install/index.html

After making sure that Anaconda is installed, select the monthly submission of interest. For example, the April 2023 submission is here: [April 2023 repository].

For starters, there are a few examples of reports already available for a preview in pdf form ready for downloading. 
An example for United Kingdom using the RFR curve without the Volatility Adjustment (VA) is named 23_APRIL_NOVA_UK.pdf

Other examples include:
 - Italy
 - Slovenia
 - Turkey
 - United Kingdom

all with and without Volatility Adjustment.

To run the report for your own country/curve, download the following files in the same folder:
 - Curves_VA.csv
 - Curves_no_VA.csv
 - EIOPA RISK FREE CURVE APRIL 23 RECALCULATION.ipynb
 - Param_VA.csv
 - Param_no_VA.csv

Open the Jupyter Notebook EIOPA RISK FREE CURVE APRIL 23 RECALCULATION

Select the correct set of input files. Either with or without VA by commenting the unnecessary set of names. For example, in the picture bellow the curves with VA are selected:
![image](https://github.com/open-source-modelling/insurance_jupyter/assets/95974474/7054fdac-f325-4e30-8a2b-2939d2b40ac4)

Select the country of interest by midifying the variable country. For example in the picture bellow, United Kingdom is selected
![image](https://github.com/open-source-modelling/insurance_jupyter/assets/95974474/6f3b1dec-0eb5-4828-a95c-5af7a113a313)

Run the workbook.

The result of the test is available at the bottom of the workbook.

A visual representation of residuals is also included in the workbook:
![image](https://github.com/open-source-modelling/insurance_jupyter/assets/95974474/410c5fe2-a4f4-4e85-8336-879380a1794c)


For first time users, a usefull ling isthe Jupyter Notebook Beginer Guide:

https://jupyter-notebook-beginner-guide.readthedocs.io/
