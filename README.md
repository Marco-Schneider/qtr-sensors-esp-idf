# Esp-idf component for the Pololu QTR Reflectance Sensors

This an adaption of the Pololu QTRSensors arduino library to work under the esp-idf framework. This was a quick implementation to handle a project necessity and further improvements will be provided along the time

I've had some problems trying to run the esp-idf framework on Windows 10, mainly linking and compiling errors, in this sense everything that you see here was built using Ubuntu 20.05 LTS, however it should work just fine as it is on Windows as well

## Installation

You can mannualy install this component:
1. Download the .zip file of this repository
2. Extract the contents of the .zip file into your project's components folder
3. Rename components folder from qtr-sensors-esp-idf to QTRSensors

Alternatively, you can clone this repository into your project's components folder. However, you may want to take a look at the concept of <a href="https://www.atlassian.com/git/tutorials/git-submodule">git submodules</a> if you proceed with this approach:

1. Open terminal window on your project's components folder and run the following command:
```
git clone https://github.com/Marco-Schneider/qtr-sensors-esp-idf
```


