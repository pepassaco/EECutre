# EECutre
Electroencephalography made cheap and easy

Project base on the INA163 instrumentation amplifier for the readout of encephalographic signals

## Materials needed

- The designed PCB (schematics in this repo)
- Electrodes (highly recommended use of either silver or gold-plated electrodes)
- 3,5mm male to male audio cable
- A PC running Matlab (Maybe python in a future, who knows) with 3,5mm mic input

## PCB construction

Just solder the SMD components as shown in the schematic. It is highly recommended to use a stencil with solder paste. Nevertheless, the components are big enough (0603) for allowing a painless hand-soldering experience. 

## Usage

**IMPORTANT:** for safety issues, it is recommended to run this program from a laptop computer not connected to the plug of your house. I mean, this is as risky as wearing some wired headsets, but everyone warns about this online, so here I am. I'm not responsible for anything, u know.

#### Connection of electrodes

The connection of the electrodes can be carried out in multiple different ways. It will all depend on how many electrodes you have and what signals you want to measure. Moreover, since we are using differential amplifiers, the signal will be measured between the difference of two point, so that there will be no absolute ground. This way, you will have to decide what electrode to compare with which one in order to see the signal you are looking for. See the following great video in order to understand the different usual montages: 

[EEG Montages](https://www.youtube.com/watch?v=AcW97nMLGEs)

As a first approach, using two electrodes for measuring the left and right halfs of the frontal lobe and a third electrode as a wirtual ground behind your ear can be a good solution for measuring alfa waves and eye blinks. 

#### The PCB

The PCB is powered though two batteries (between 7V and 12V each) so that the operational amplifiers can work with both positive and negative voltages.

Connect the electrodes to the PCB and the PCB to the audio input of your laptop. Beware that this board is extremely noise sensitive, so stay away from low-frequency EMI sources. Also, always power it through batteries, since the 50Hz/60Hz of a power supply can dirty the ignal output

#### The software

Cuando tenga tiempo escribo algo wapo, primero tengo que mriar si funciona
