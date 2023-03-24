# Rescue Mission (PI2 summer project)

This project consists in a device intended to send distress signals and location to the exterior in case of a natural disaster. 

[Document with periphereals and bio-data interpretation](https://devinci-my.sharepoint.com/:w:/r/personal/sezgi_isik_edu_devinci_fr/_layouts/15/Doc.aspx?sourcedoc=%7B4EBE9C59-3251-4046-A05A-C7A0C9B39F0C%7D&file=Document3.docx&_DSL=1&action=default&mobileredirect=true)

[Arduino RF sensors for communication with master device](https://randomnerdtutorials.com/rf-433mhz-transmitter-receiver-module-with-arduino/)

## Small proposition
Since the use of a traditional balloon system for measuring arterial blood pressure in the arm with a relative pressure sensor would be way too non-practical, a smaller, more mathematical approach can be used. Instead of using a pneumatic system to measure the relative pressure between the air inside the balloon and the one in the environment, we could perform an approximation of it using a torniquet system in the wrist controlled by the readings of the pulse oximetry sensor. The idea is simple. Since the traditional measurement is done inflating a balloon against the braquial artery at the level of the elbow until no more beats can be detected, and recording the systolic and diastolic pressures by measuring the pressure of the air inside the balloon when the beat is no longer detected (aka. no more oxygenated blood is going through that point) and when the beat is detected again (aka. the oxygenated blood is passing again through that point), we can approximate a module that does the same thing, but instead of listening for a beat, it listens to the measures of the oxymetry sensor and tabulate pressure ranges through the oxygen saturation values. This way we can make a better use of the oxymetry sensor and spare the use of the relative pressure sensor for the arterial pressure monitoring.
