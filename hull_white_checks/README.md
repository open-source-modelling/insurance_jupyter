<h1 align="center" style="border-botom: none">
  <b>
  🐍 Hull-White economic scenario generator checks  🐍
 </b>
</h1>

</br>

The Hull-White model is a very popular choice when modeling interest rates. The simulated risk-free curve is one of the principal inputs into such economic scenario generator. This notebook has 4 sections. The first section uses the EIOPA RFR calibration to produce the yield curve. In the second section, this yield curve is used to produce a number of stochastic scenarios using a HW model. The third section checks how close is the average interest rate from ESG to the term structure provided as input. The final section calculates the closed form variance and compares it to the simulated variance.
