Experiment from a Master Thesis Project, Decoding Emotions through EEG in Real and Virtual Environments
EEG measurements and mEDI detections using a spectrometer and ALFA simulations.
The experiment has been carried out in 5 days, testing 15 participants.

Parameters include:
- **Day**,
- **Participant**, 
- **Phase of the day**,
- **Environment**, 
- **Light**, 
- **Scenario**, 
- **Sky Condition**,
- **Time and Date**,
- **mEDI**,
- **α ALPHA AVG**, 
- **β ALPHA AVG**, 
- **γ ALPHA AVG**,
- **F3 electrode α ALPHA AVG**,
- **F4 electrode α ALPHA AVG**,
- **F7 electrode α ALPHA AVG**,
- **F8 electrode α ALPHA AVG**, 

Spectrometer used: GL SPECTIS 1.0 Touch + Flicker (mEDI was measured 120cm above the floor on a vertical plane),
VR headset used: Oculus Quest 2; it features a high-resolution screen with two separate displays with a refresh rate of 90Hz,
The EEG headset used is Unicorn Hybrid Black. It acquires eight electrodes of a complete 8-channel EEG sampled at 24 bits and 250 Hz.

Columns in the dataset:
- DAY: Values 1 to 5
- PARTICIPANT: 1 to 15
- PHASE OF THE DAY: Time monitored for the different phases of the experiment
- ENVIRONMENT: RE= Real Environment; VR= Virtual Environment
- LIGHT: Condition tested: DL = Daylight / DL+EL = Electrical lighting
- SCENARIO: 
**CONT**=Control phase; 
        A brief phase before each testing condition, 30 seconds long, where the participants, both in the Real environment. and in the recreated virtual environment., faced the back wall and had to stare at a black paper with a white cross to establish a baseline for 
        EEG signals minimize external stimuli and reduce distractions.
**EXP**=Experiencing the room: The first part of the experiment where, for 1 minute, the EEG recorded the participant, who freely, while always remaining seated, explored the room in the two conditions of light (DL and DL+EL). This was done 
       to assess visual perception and visual comfort, analyse cognitive load and attention under different lighting conditions, and get emotional and psychological responses.
**ACT**=Performing an activity;
       The second stage of the experiment consisted of recorded participants sorting cards numbered from 1 to 9 in increasing and decreasing order. This was done to assess the cognitive load and executive function, attention, and 
       Concentration and motor activity to understand the neural correlates of motor planning and execution.
- SKY CONDITION: * Lower letters: Sky type during the measurement, derived from the CIE 15 type of skies ("Spatial Distribution of Daylight" – CIE Standard General Sky, ISO 15469:2004(E)/CIE S 011/E:2003 - https://cie.co.at/publications/spatial-distribution-daylight-cie-standard-general-sky) 
** CAP Letters: An approximation of the same sky type was used in ALFA with available sky conditions (Clear sky, Hazy, Overcast and Heavy rain) Since evaluating mEDI from a VR headset is impossible.
- TIME AND DATE: refers to the measurement and indication of chronological events, including the phases of the day and the transitional periods of twilight.
- mEDI: the calculated value of melanopic Equivalent Daylight Illuminance 
        *RE = detected with spectrometer; 
        **VR = measured with ALFA
- α ALPHA AVG: Average band frequencies from EEG headset for alpha waves
- β ALPHA AVG: Average band frequencies from EEG headset for beta-low waves
- γ ALPHA AVG: Average band frequencies from EEG headset for gamma waves
- F3 α ALPHA AVG: Average band frequencies from Channel 3 (Fz Frontal sagittal plane) for alpha waves
- F4 α ALPHA AVG: Average band frequencies from Channel 4 (C4 central) EEG headset for alpha waves
- F7 α ALPHA AVG: Average band frequencies from Channel 7 (Oz occipital zero) EEG headset for alpha waves
- F8 α ALPHA AVG: Average band frequencies from Channel 8 (PO8 parietal-occipital) EEG headset for alpha waves


Note: mEDI calculations at 17:00 in the "DLl" case were not possible (due to low daylight), so mEDI values were set to 0

![Procedure of the whole experiment](./Procedure.png)

Dataset made by Gabriele Zoochi and supervised by Georgios Triantafyllidis in Lighting Design Lab AAU (https://www.light.aau.dk/)
