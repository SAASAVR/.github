# SAASAVR Main Page Ver 1.1
Welcome to Sensor Activated Acoustic Signal Acquisition, Visualisation, Recognition. [Youtube video](https://www.youtube.com/watch?v=FkJ5tvA459M)

This project was made by [Darius Fang]() [Landyn Pugh]() [Marco Romero]()
## Who we are
Equipment used for acoustic research and analysis is often very expensive and complex. This is the problem that our Sensor-activated acoustic Signal Acquisition, Visualization and Recognition Device, or SAAS, is attempting to solve. 

The proposal for this project, as given to us by our client, Dr. Huda of Industrial Automation at Nate was to create something that accomplishes this by being an Internet of things-like device that is portable, easy to use, and is able to effectively analyze recorded audio using machine learning tools. 
A brief description.

From this proposal, we are able to set up a few main goals for ourselves. The device must record audio, stream live audio data to a user interface, visualize audio data on that user interface, save the audio to a database, analyze audio using neural networks, and allow for user-controlled recording. 
### Component Documentation:
- [Firmware](https://github.com/SAASAVR/Firmware/blob/main/README.md)
- [Hardware](https://docs.google.com/document/d/1qsRrO2yIlogNYCMet9N72-EUuf6XB-Ce7WJqF0msMxc/edit)
- [Web Application](https://github.com/SAASAVR/Webapp)
- [ML Analysis](https://github.com/SAASAVR/Cloud-Analysis-Process)

## Demo
![image](https://github.com/SAASAVR/.github/blob/main/ResultPhotos/GLAMOUR%20%E2%9C%A8%E2%9C%A8/20230406_095052.jpg)

## What worked
#### Acquisition
- SAAS hardware can record audio and stream data wireless to a usuer inerface in real-time.
- Can save recorded audio to a database for future access.
#### Visualization
- UI can interact with other components of the system.
- Basic visualizations are provided.
#### Recognition
- Machine Learning model can classify and output data to be shown in UI.
## What didn't work
#### Acquisition
- Mic is 8 bit data.
#### Visualization
- Visualizations not customizable.
#### Recognition
- Current synthetic data is not 8 bit.

## Future Work
#### Acquisition
- Portability needs otbe addressed.
- More pre-processing needs to be done to ensure analysis accuracy.
#### Visualization
- Add more audio visulizations and info
#### Recognition
- Add multi classification.
- More models for database.

[View on GitHub](https://github.com/SAASAVR/)



---
