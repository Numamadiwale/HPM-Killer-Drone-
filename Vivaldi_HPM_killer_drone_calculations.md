**Freq required min = 30 Ghz**

**Freq required max = 60 Ghz**



**l0** = 3x10^8 / 30x 10^9 = 1x10^-2 m or **0.01 m**

**l0/2**= 5x10^-3 or **0.005 m**

**wap**= l0/2= **0.005m**

* since Wap here only for well for 30 Ghz , we take **2l0 = 10mm**





**using online slot antenna calculator we get:**



**inputs**:



operating frequency = 30 Ghz



Relative permittivity (Rogers  3003) = 2.2



**Outputs :**

**slot length**, meters = 0.005 , **increasing to 10 mm** to be longer than the aperture width



**slot width** , meters = 0.0033 , too high impedance , since it is Vivaldi , we reduce it to a standard **0.4 mm as we reach the**



**distance between slot and GND plane , meters = 0.00053**





solving for **Taper rate** , we get:



**R**= ln(Wap/W slot)/L



we get = **0.321**



**Circular back cavity** (Rcav) needs to be calculated to ensure the radiation goes only one way and doesn't affect the drone's communication antenna





we have to calculate **lg** (lambda g) = c/(fc x sqrt(permittivity coefficient of Rogers5880)



we take centre frequency, **fc** as 45 Ghz



**Er= 2.2**



and get , **lg**= 3x10^8/ (45 x 10^9 x sqrt(2.2)) = 0.0044 ~~ **4.4 mm**



**Rcav = lg/4**



so we get, **Rcav**= 0.0044 / 4 = 0.0011 or **1.1 mm**



Next is to calculate the radial stub for the microstrip feedline which is the quarter of our wavelength so it is



**Lstub** ( Microstrip transition feed ) = lg/4 = **1.1 mm**



**Feed line needs to steadily narrow down from 1.5 mm to 0.6mm by the time it reaches the feed point**





**Feedline dimensions are 1.5, 21.5 and 0.5 mm respectively in x,y and z**

