      Sahil Mahendra Mangaonkar
      LinkedIn: https://www.linkedin.com/in/sahil-m-39a2671b0
      Tested on:  HP Probook 650 G1 (15.6-inch, 2014), Window 10

# 05 I2C Traffic:

### TODO:

- use your Lab 1 firefly code to generate ADPS9960 I2C traffic and display it on a lab oscilloscope
- take a screenshot of some portion of this exchange, and figure out/annotate what's happening based on the protocol documentation in the ADPS9960 datasheet 


## I2C Traffic

Since the SCL or clock signal drives communication between the nodes, I2C is a serial, synchronous communication protocol, as can be seen from the graphics above.

For a finer signal, the oscilloscope was set to digital mode (without the noise).

To view the digital signal on the oscilloscope, conventional probes and logic analyser probe cables were utilized.

The I2C traffic between the Adafruit QTPy RP2040 and the APDS9960 sensor is depicted in the gif.
