# PAL-1 Digital Complex Sound Generator

The PAL-1 Digital Complex Sound Generator is an expansion board for the PAL-1
system<sup>1</sup>, based on the Texas Instruments SN76489 digital complex 
sound generator<sup>2</sup> and was inspired by a Circuit Cellar project<sup>3
</sup>. 

The SN76489 DCSG provides three programmable tone generators and one noise 
generator. Each tone generator has a frequency synthesis and attenuation 
section. The noise generator supports a noise source and attenuator. The three 
tone generators and the noise source are mixed and passed to an output buffer. 
As the SN76489 output pin drives a maximum of 10mA, the board includes a 
simple amplifier circuit to allow a speaker to be connected.

## References
1. Liu Ganning, ‘PAL-1 Microcomputer User Manual’, 2020 <http://pal.aibs.ws/assets/PAL_en.pdf> [accessed 21 July 2022].
2. The Engineering Staff of TEXAS INSTRUMENTS Semiconductor Group, ‘SN76489AN’ (TEXAS INSTRUMENTS, N.D.)
3. Ciarcia, Steve, ‘Add Programmable Sound Effects to Your Computer’, Byte, 7.7 (1982), 60–72
