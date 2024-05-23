Experiment from a Master Thesis Project, Decoding Emotions through EEG in Real and Virtual Environments
EEG measurements and mEDI detections using a spectrometer and ALFA simulations.
The experiment has been carried out in 5 days, testing 15 participants

In total there are 1600 measurements and 1600 calculations with ALFA.

Parameters include:
- **Day**,
- **Participant**, 
- **Environment**, 
- **Light**, 
- **Scenario**, 
- **Sky Condition**,
- **mEDI**,
- **α ALPHA AVG**, 
- **β ALPHA AVG**, 
- **γ ALPHA AVG**,
- **AROUSAL α**,
- **AROUSAL β**,
- **VALENCE γ**.

VR headset used: Oculus Quest 2; itfeatures a high-resolution screen with two separate displays with a refresh rate of 90Hz
EEG headset used: Unicorn Hybrid Black; It acquire eight electrodes of complete 8-channel EEG,, sampled with 24 bits and 250 Hz

Columns in dataset:
- DAY: Values 1 to 5
- PARTICIPANT: 1 to 15
- ENVIRONMENT: RE= Real Environment; VR= Virtual Environment
- LIGHT: Condition tested: DL = Daylight / DL+EL = Electrical lighting
- SCENARIO: CONT=Control phase; EXP=Experiencing the room; ACT=Performing an activity
- SKY CONDITION: Sky type during the measurement - An approximation of the same sky type was used in ALFA
- mEDI: the calculated value of melanopic Equivalent Daylight Illuminance using ALFA simulation
        RE = detected with spectrometer; VR = measured with ALFA
- α ALPHA AVG: Average band frequencies from EEG headset for alpha waves
- β ALPHA AVG: Average band frequencies from EEG headset for beta-low waves
- γ ALPHA AVG: Average band frequencies from EEG headset for gamma waves
- AROUSAL α: If alpha decreases, Arousal Increases
- AROUSAL β: If beta-low decreases, Arousal Increases
- VALENCE γ: If gamma decreases, Increases in High Valence ; If gamma increases, Decrease in Low Valence 

![Procedure of the whole experiment](./Procedure.png)


Note: mEDI calculations at 17:00 in the "dl" case were not possible (due to low daylight), so mEDI values were set to 0
