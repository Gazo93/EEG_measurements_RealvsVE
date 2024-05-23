# EEG_REvsVE
Experiment from a Master Thesis Project, Decoding Emotions through EEG in Real and Virtual Environments
EEG measurements and mEDI detections using a spectrometer and ALFA simulations.
The experiment has been carried out in 5 days, testing 15 participants

In total there are 1600 measurements and 1600 calculations with ALFA.

Parameters include:
- **Day**,
- **Participant**, 
- **Environment**, 
- **Light**, (Condition tested: DL=Daylight / DL+ELElectrical lighting)
- **Scenario**, (CONT=Control phase; EXP=Experiencing the room; ACT=Performing an activity)
- **Sky Condition**,
- **mEDI**,
- **α ALPHA AVG**, Average band frequencies from EEG headset for alpha waves
- **β ALPHA AVG**, Average band frequencies from EEG headset for beta-low waves
- **γ ALPHA AVG**, Average band frequencies from EEG headset for gamma waves

VR headset used: Oculus Quest 2; itfeatures a high-resolution screen with two separate displays with a refresh rate of 90Hz
EEG headset used: Unicorn Hybrid Black; It acquire eight electrodes of complete 8-channel EEG,, sampled with 24 bits and 250 Hz

Columns in dataset:
- DAY: Values 1 to 5
- PARTICIPANT: 1 to 15
- ENVIRONMENT: RE= Real Environment; VR= Virtual Environment
