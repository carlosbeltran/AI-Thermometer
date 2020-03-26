# FAQ

## Is this a custom dataset? What camera is used for testing.

We are testing the first versions of the software with a public dataset distributed by FLIR. The dataset is oriented at ADAS systems and to our bes knowledge the used camera is a FLIR IR Tau2.

## What is the need for the green reference point? How is being used?

The used images contain uncalibrated temperature values. The green point should provide a theoretic ground truth known temperature that is used as workaround to estimate the human temperature. We are working at integrating radiometric calibrated thermal images that will provide directly the temperature of the are of interest. 

## Is it learning from any annotations?

The current code doesn't include yet machine learning. However, this is a very interesting possibility that we are willing to investigate further.

## Did OpenPose work out of the box on the thermal images?

Well, not really. We had to pre-process images in a way OpenPose could provide an output. 

## Any measure of how accurate the resulting temperatures are?

The foreseen integration of radiometric capable cameras will provide the accuracy of such cameras. However, take into account that the measured temperature will be always influenced by a number of ambient factors. 
