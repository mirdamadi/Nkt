# Nkt factor
In situ tests are one the most reliable tests that can capture the soil properties as in the location. The benefit of measuring parameters in place is the positive side of the in-situ test compare to lab testing which needs high-quality samples and issues with change of features due to extraction from the depth. However, the limitation is to correlate the measured parameters in the field with engineering features such as strength and stiffness. Since the development of in-situ tools, there are many calibration methods developed. Most of these plots or equations are based on the empirical relationship between in-situ and lab testing. Due to the limitation of human imagination the plots are limited to 2D correlation with consideration of few variables. By use of Artificial Intelligence (AI) and specifically Machine Learning (ML) algorithms we can overcome this limitation and generate models in higher degrees.

The most adopted in-situ test in offshore site investigation is cone penetrometer test (CPT). The idea is to push a cone and measure the tip and shaft resistance and sometimes pore water pressure. The challenge is to estimate the soil properties from the CPT data which is a complex process based on theoretical solutions. Therefore, the most common approaches rely on empirical correlation. One of the most famous relationships for clay is the undrained shear strength (su) correlated to net cone resistance (qnet). The ratio is called Nkt and equal to:

Nkt=qnet/su. 

where,

su: undrained shear strength
qnet=qt-σ0v
qt: Total cone resistance = qc+u2(1-α)
σ0v: in-situ total vertical stress
qc: measured cone resistance
u2: pore pressure measured behind the cone
α: area ratio of the cone

The Nkt varies between 5 to 29 for different soil type and different su (compression, extension or direct simple shear). One approach to estimate the Nkt value is to compare the in-situ results with lab test at the same location and depth. This approach sometimes is not possible due to the limitation of lab testing or distance between boreholes and CPT location. As a result, engineers usually choose a range of let say 10 to 20 and develop a high and low estimate su profile (considering other uncertainties). This method sometimes ends in a wide range of strength which causes a highly over-conservative design and most importantly without knowing the level of confidence for each limit. There are some developed correlations for Nkt based on either plastic index (PI) or pore pressure parameter (Bq) that do not have enough accuracy.

In this study multivariant regression analysis as one machine learning techniques is developed on a database to generate a predictive model for Nkt based on in-situ measurement. 
