# Project_Electronics_Adjustable-Output-Voltage-Regulator-using-7805
Fixed-Output voltage regulator is an important component in most electronic appliances. Fixed voltage regulation is important for microcontrollers and microprocessors. For microcontroller applications, 5V fixed voltage regulators are used. Normally 7805 voltage regulator is used in such applications. 7805 comes under 78xx series.


# Component:

9V Battery.

Breadboard.

Wires.

7805               Voltage Regulator

Input Voltage  -  9V, 1A supply from an SMPS

R1            420 Ohms

R2            0 - 200 Ohm Variable  

Capacitors    0.33 micro Farad at input side and 0.1 micro Farad at output side.

# Circuit connection steps:


![TsIQv61405271880](https://user-images.githubusercontent.com/56201060/123808628-97319f00-d8f9-11eb-9160-88a1d3fc151a.jpg)

7805 is capable of handling an input voltage from 7.5V to 25V.

I gave an input voltage of 9V from an SMPS.

A 0.33 micro Farad capacitor is connected across the input and a 0.1 micro Farad capacitor is connected across the output.

R1 is fixed and R2 is variable. 

I kept R1 at 420 Ohms. Similarly a 0 - 200 Ohm variable resistor is used as R2.

Output voltage is normally measured using a multimeter.


Vo        -  Output Voltage

Vxx       -  Nominal output voltage ( Output to Common ) of fixed regulator. Vxx is 5V for 7805, 8V for 7808 and 12V for 7812.

Io        -  Output Current.


![Adjustable Output Voltage Regulator using 7805](https://user-images.githubusercontent.com/56201060/123807461-8896b800-d8f8-11eb-8a10-e714fcc452e7.png)



# Procedure:

Initially, keep the resistance R2 at minimum position ( 0 Ohm ).Then Vo = Vxx. That is, output voltage will be equal to nominal output voltage ( 5V for 7805 ).

Now put R2 at maximum position ( 200 Ohms ). Then measure the output voltage using a multimeter.

I got an output voltage of 8.14V. Calculation can be summarised as given below.

Vo     =    8.14V 

Vxx    =    5.07V 

R1     =    420 Ohms

R2     =    200 Ohms

Substituting these values in the above formula, we will get Io. Io will be same for a particular load, at different voltages. Using this value of  Io, Vxx and R1, we can 

calculate the value of  resistance R2 to be used for a desired value of Vo. Vo measured for various values of R2 using multimeter is given below.


![Gb3TTf1405277672](https://user-images.githubusercontent.com/56201060/123808594-913bbe00-d8f9-11eb-83c0-8c7c33fea36b.jpg)


From the table, it is clear that, Vo increase with increase in R2. So we will get a variable output voltage from 5.07V to 8.14V.

An increase in the value of resistances above the values given in the table didn't give me an expected result. 


# Simulation:

https://www.tinkercad.com/things/aCfXfFMp1wx


                                                  /* END */




