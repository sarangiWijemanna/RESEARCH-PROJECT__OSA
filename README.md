# Optical Spectrum Analyzer (OSA) And Optical Power Meter (OPM) Design 📈📡🧮

## Project Overview

Fiber optic networks use pulses of light to transmit digital information over long distances. Compared to traditional copper wire networks, fiber optic networks have several advantages, including higher bandwidth, faster data transmission rates, and better resistance to electromagnetic interference.

WDM (Wavelength Division Multiplexing) technology is often used in fiber optic networks to increase their capacity. WDM allows multiple streams of data to be transmitted over a single fiber by separating the different wavelengths of light used to transmit the data. This enables multiple signals to be transmitted simultaneously over the same fiber, increasing the overall capacity and efficiency of the network.

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Wavelength Division Multiplexing.png" alt="icon"/>
            </a>
          <br><small><i>Figure 1 : Wavelength Division Multiplexing</i></small>
        </td>  
    </tr>
</table>

High-speed data transmission is another key feature of fiber optic networks. The high bandwidth of fiber optic cables allows for faster data transmission rates than traditional copper wire networks, making fiber optic networks ideal for applications such as streaming video, online gaming, and cloud computing.

### Introduction of Optical Spectrum Analyzer

An Optical Spectrum Analyzer (OSA) is an important tool in the field of optical communication that is used to measure and display the ```distribution of power``` of an optical source over a ```specified wavelength span```. 

> Observations :

- The spectral characteristics of an optical signal, including its center ```wavelength```, ```bandwidth```, and ```power levels``` at different wavelengths.
- Channel Failure
- OSNR 
- Channel Separation

> OSAs are used in a variety of applications, including:

- Fiber optic communications
- Laser characterization
- Spectroscopy
- They are especially useful in the design and testing of optical components, such as fiber Bragg gratings and optical filters, as well as in the troubleshooting of optical systems.

### Problem Statements

> Diagnosed the Problems 1: 

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Analysis 1.png" alt="icon"/>
            </a>
          <br><small><i>Figure 2 : Analysis 1</i></small>
        </td>  
    </tr>
</table>


> Diagnosed the Problems 2: 

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Analysis 2.png" alt="icon"/>
            </a>
          <br><small><i>Figure 3 : Analysis 2</i></small>
        </td>  
    </tr>
</table>


## Project Scope

One of the scope of this project is to design a ```Filter Control Program``` that can communicate with the optical tunable filter using GPIB interface and plot the optical spectrum within the C & L band using LabVIEW. 

```LabVIEW Programming``` ```Instrument Controlling``` ```Insertion Loss of filter (IL)```


> The program should be able to perform the following tasks:

- Establish communication between the computer and the optical tunable filter via GPIB interface. 

- Control the parameters of the optical tunable filter such as wavelength, bandwidth, and attenuation. 

- Retrieve the optical spectrum data from the optical tunable filter. 

- Process the optical spectrum data to remove noise and other unwanted signals. 

- Plot the processed optical spectrum data using LabVIEW within the C & L band. 

- The project aims to provide a user-friendly and efficient way to control the optical tunable filter and visualize the optical spectrum within the C & L band using LabVIEW. 

<br>

Another scope of this project is to design an ```Optical Power Meter``` that can detect peak powers when the optical filter is varying with the wavelength or frequency within the C & L band. 

```TIA Circuit``` ```P (nm) vs V (A)``` ```P (nm) , V (A), IL```

> The project should be able to perform the following tasks:

- Detect the power of the incoming optical signal within the C & L band.

- Detect the peak power of the optical signal as the optical filter varies with wavelength or frequency.

- Display the peak power values on a graphical user interface.

- Allow the user to select the wavelength or frequency range to monitor and display the corresponding peak power values.

- Provide the ability to save and export the peak power values for further analysis.

- The project aims to provide a reliable and accurate way to monitor and measure peak powers within the C & L band as the optical filter varies with wavelength or frequency. 


## Project Prototypes

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Enclosure Design 1.png" alt="icon"/>
            </a>
          <br><small><i>Figure 4 : Enclosure Design OPM Version 1</i></small>
        </td>  
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Enclosure Design 2.png" alt="icon"/>
            </a>
          <br><small><i>Figure 5 : Enclosure Design for OPM Version 2</i></small>
        </td> 
    </tr>
</table>


## Project Achievements Beyond the Scope

- Accomplished the ```0.13 nm``` resolution by cascading the two JDSU TB9 optical grating filter via GPIB interface.

- Designed LabVIEW program for acquiring optical power measurements from Agilent Lightwave Power sensor via GPIB interface. 

- Improved the LabVIEW user interface.

- Designed the portable device for the optical power meter circuit (3D Printing).


## Observation : 

> Within the Scope :

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Project Setup for Design 1 .png" alt="icon"/>
            </a>
          <br><small><i>Figure 6 : Actual setup of the OpticaSa Spectrum Analyzer Design 1 </i></small>
        </td>  
    </tr>
</table>

> Beyond the Scope :

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Project Setup for Design 2.png" alt="icon"/>
            </a>
          <br><small><i>Figure 7 : Actual setup of the OpticaSa Spectrum Analyzer Design 2 </i></small>
        </td>  
    </tr>
</table>


### Data Visualization :

> Within the Scope : 

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="DA 1.png" alt="icon"/>
            </a>
          <br><small><i>Figure 9 : Final Outcome (GUI DESIGN) of the Project Prototype Design Version 1 using LabView Program </i></small>
        </td>  
    </tr>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="DA 2.png" alt="icon"/>
            </a>
          <br><small><i>Figure 10 : Optical Spectrum on the JDSU MTS 6000A OSA and Agilent Network Analyzer </i></small>
        </td>  
    </tr>
</table>


> Beyond the Scope : 

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="DA 3.png" alt="icon"/>
            </a>
          <br><small><i>Figure 11 : (GUI DESIGN) Optical Spectrum Using Portable Power Meter (version 2) at Cascading Two TB9 Optical Filters </i></small>
        </td>  
    </tr>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="DA 4.png" alt="icon"/>
            </a>
          <br><small><i>Figure 12 : Optical Spectrum on the JDSU T-BRED 6000A OSA </i></small>
        </td>  
    </tr>
</table>


### Comparison Between the OPM Versions and OSAs

> Comparison between the Project Prototype Versions, exiting 81634A power Sensor and Existing OSA :

<table>
    <tr>
        <td align="center">   
             <a href="#macropower-tech">
                <img align="center" src="Comparison.png" alt="icon"/>
            </a>
          <br><small><i>Figure 8 : Comparison between the Project Prototype Versions </i></small>
        </td>  
    </tr>
</table>