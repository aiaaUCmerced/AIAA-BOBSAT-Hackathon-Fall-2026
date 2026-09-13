As part of your presentation, Bobcat Ballistics requires that the analysts create a Day in the Life chart depicting the nominal operations of the satellite in a 24-hour window. 

---

For this deliverable, the analysts will need to calculate and display the following values over a day of operation:
1. Power consumption and generation. You can use [this resource](https://universitynanosat.org/downloads/resources/mission-concept-program-workshops/5%20UNP_NASA%20Power%20Systems%20Workshop%20Presentation.pdf) as a baseline for particular values, starting from slide 60. You can understand Standby Mode as allowing the satellite to recharge; modify the Radio Tx to 0% duty cycle and CDH to 50% duty cycle. You can understand Experiment Mode as the image generation and processing; modify Radio Tx to 0% duty cycle. Finally, you should add a Downlink Mode that has the same duty cycles as Standby mode except it has 100% Duty cycle on the Radio Tx. 
2. Data downlink rate. You can find baselines for frequency band and data rate [here](https://universitynanosat.org/downloads/resources/mission-concept-program-workshops/7%20UNP%20Communications%20Workshop%20Presentation.pdf). You can assume that the satellite will use an S or X band antenna. You can also assume that the satellite will make 16 orbits per day, with 3 of those orbits containing a 15 minute window where the satellite can enter Downlink Mode.
3. Data generation rate. Using the specifications from the [HyperScape50](https://simera-sense.com/products/hyperscape50/), you can assume that the imager creates a 4096x4096 image in 60 seconds. Don't worry about how much data can be stored, you'll be limited by downlink capacity. 
4. The day in the life chart should display a 24 hour timeline with each of the different operational modes throughout the day. You should also display the total amount of images that you can generate and transmit per day while never dropping below 25% battery at any point in the day. 

---

For further consideration, the analysts could include:
1. Trade-off study between static solar panels and deployable solar panels.
2. Power consumption, generation, and storage plots over time
3. Trade-off study for implementing more than a single ground station

---
Bobcat ballistics is providing the following resources for the analysts' consideration:

[UNP mission design resources](https://universitynanosat.org/resources/mission-concept-program-workshops) - All of the resources that the above slides came from

[Information from NASA on cubesats](https://s3vi.ndc.nasa.gov/ssri-kb/static/resources/nasa_csli_cubesat_101_508.pdf) - This includes interesting info on Day in the Life testing (section 6.9.1). 
