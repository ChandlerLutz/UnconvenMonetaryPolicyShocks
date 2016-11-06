# Data: Unconventional Monetary Policy Shocks

Event Study Data measuring unconventional monetary policy shocks 
from Lutz (2015):

Lutz, Chandler. "The impact of conventional and unconventional
monetary policy on investor sentiment." *Journal of Banking & Finance*
61 (2015): 89-105.

See http://dx.doi.org/10.1016/j.jbankfin.2015.08.019

# Data Description 

Monetary policy shocks are measured from the first principal component
of the front-month futures contracts on the 2-, 10-, and 30-year
Treasuries either 15 minutes before to 105 minutes after (Wright 2012)
or 10 minutes before to 20 minutes (Glick and Leduc (2013) after each
monetary policy event. Monetary shocks are standardized to have
variance equal to 1 and so that positive values indicate monetary
easing. 

* `time` The monetary policy event date. These include FOMC meeting
  and major speeches by the Fed Chair. These dates cover QE1, QE2,
  QE3, and the taper period (48 events in total)
* `Wright.15.105` Unconvetional monetary policy shocks measured 15
  minutes before to 105 minutes after each monetary policy event (see
  Wright (2012))
* `GlickLeduc.10.20` Unconventional monetary policy shocks measure 10
  minutes before to 20 minutes after each monetary policy event (see
  Glick and Leduc (2013))
  

