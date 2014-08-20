Edison Analog-to-Digital Conversion Expansion Card
==================================================

This card adds ADC functionality to the Edison's I<sup>2</sup>C bus. The ADS1015 ADC from TI provides a single 12-bit delta-sigma convertor with an analog multiplexer. It can be configured as a four-channel single-ended device or as a two-channel differential device.

The board has jumpers to allow selection of the I<sup>2</sup>C slave address among four different options, allowing up to four of these cards to be stacked under one Edison. The sampling rate is not sufficient for audio capture, at 2.2kHz, but it should be adequate for most control applications.
