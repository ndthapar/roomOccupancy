# roomOccupancy

Perceptron Learning Linear and Polynomial Classifier


Script takes input data from: https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+

---- Data Description ----

Source:

Luis Candanedo, luismiguel.candanedoibarra '@' umons.ac.be, UMONS.


Data Set Information:

Three data sets are submitted, for training and testing. Ground-truth occupancy was obtained from time stamped pictures that were taken every minute.


Attribute Information:

date time year-month-day hour:minute:second
Temperature, in Celsius
Relative Humidity, %
Light, in Lux
CO2, in ppm
Humidity Ratio, Derived quantity from temperature and relative humidity, in kgwater-vapor/kg-air
Occupancy, 0 or 1, 0 for not occupied, 1 for occupied status


Relevant Papers:

Accurate occupancy detection of an office room from light, temperature, humidity and CO2 measurements using statistical learning models. Luis M. Candanedo, VÃ©ronique Feldheim. Energy and Buildings. Volume 112, 15 January 2016, Pages 28-39.
 

---- Code Description ---- 

The following script takes data related to the occupancy of a room and implements classification into either Occupied or Unoccupied classes. Two attributes, Light (Lux) and CO2 (ppm) were chosen as inputs. 

The linear classifier used was taken from the sklearn machine learning library. 

The polynomial classifier was implemented from scratch using the perceptron learning formula.



