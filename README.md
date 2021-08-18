# GSOC 2021 Report - Sugar Labs

### About the project:

My project involves creating a Measure Activity for Sugarizer which can run on all the platforms.

### Measure Activity:

The Measure Activity is a tool that allows kids to indulge in "learning by doing". It provides an interface for the kids to connect with the physical world and an opportunity to view and understand through a visual and statistical representation of the physical phenomena. Through this activity, children will learn concepts related to sound.

### PR link: https://github.com/llaske/sugarizer/pull/957

### Activity Status:

The activity is in its final stages of testing and will be merged soon to the dev branch. It will then be included in the subsequent release.

### Activity UI:

![MeasureActivtyUI](https://user-images.githubusercontent.com/42293606/129938606-1af1f44e-659d-4eab-9887-cac09fa1b824.JPG)

![Activity Toolbar](https://user-images.githubusercontent.com/42293606/129938744-62ef7f3a-2540-4167-81c4-f5b17ff08457.png)

### Features:

* **Share/Multiplayer:** Activity can be shared among multiple users and changes done by one user will be reflected in other’s activity also.
* **Time and Frequency:** User can switch between time and frequency mode. In time mode, x-axis will contain time and in frequency mode, x-axis will contain frequency. Y-axis will contain amplitude of microphone data.
<p align="center"><img src="https://user-images.githubusercontent.com/42293606/129939948-91f4554f-ec6a-47ef-92f2-a47e75357514.gif" width="300" height="300" /></p>

* **Zoom:** User can increase or decrease scale of x-axis with the help of zoom button and sliders.
<p align="center"><img src="https://user-images.githubusercontent.com/42293606/129942064-168902bc-1f1c-48c0-ac11-ab7aa0b6abea.gif" width="300" height="300" /></p>

* **Play and Pause:** User can play or pause plotting of graph.
* **Waveform setting:**
    * **Amplitude:** User can increase or decrease amplitude of waveform.
    <p align="center"><img src="https://user-images.githubusercontent.com/42293606/129942689-99bf3cbd-f365-486c-a72a-b46609445bfa.gif" height="300" /></p>
    
    * **Inversion:** User can invert waveform.
    <p align="center"><img src="https://user-images.githubusercontent.com/42293606/129943105-298b81db-12a8-4c49-905b-d73fafbba2ea.gif" height="300" width="300" /></p>
    
    * **Triggering Edge:** User can switch between None, rising and falling mode. Different mode represent different plotting of first waveform edge.
    <p align="center"><img src="https://user-images.githubusercontent.com/42293606/129943345-065bbf0e-99f1-4fd5-a3d4-deb49b524c38.gif" height="300" width="300" /></p>
    
* **Logging Interval:** User can record amplitude data at interval of 0.1,1,30 and 500 seconds.
* **Start and Stop recording:** User can start or stop recording of amplitude data.
* **Export logs:** User can export recorded logs in PDF and CSV (with txt extension) format.
* **Instrument selection:** User can select which string instrument is to be tuned from available list of instruments.
* **Note selection:** User can select between different notes of instrument.
<p align="center"><img src="https://user-images.githubusercontent.com/42293606/129944061-89885467-d134-466d-b510-50144f6ee266.gif" height="250" width="400" /></p>

* **Octave selection:** User can select between different octave when no instrument is selected.
* **Tuning Palette:**
    * **Harmonics:** User can show or hide harmonics.
    <p align="center"><img src="https://user-images.githubusercontent.com/42293606/129944785-9012b973-cebd-4bdd-908c-d53214e40049.gif" height="250" width="400" /></p>
    
    * **Tuning line:** User can show or hide tuning line.
    <p align="center"><img src="https://user-images.githubusercontent.com/42293606/129945062-20a8f043-ee99-4ac8-93fb-76434bec0fe8.gif" height="250" width="400" /></p>
    
    * **Frequency Input field:** It will display frequency corresponding to combination of note and octave. Also user can enter any frequency and plot tuning line at that frequency.
    * **Play and stop note:** User can hear sound of different frequency.

* **Graph screenshot:** User can take screenshot of graph and it will be saved in journal.
* **Tutorial:** User can see detailed tutorial containing explanation of each and every functionality.
* **Fullscreen and Unfullscreen:** User can switch between fullscreen and unfullscreen mode.

### My GSOC Experience:

GSoC has been an amazing experience for me. I learned a lot of things. Major among them are:
* About music concepts
* Permission difference in different environments
* How to write good documentation
* Write a better and modular code so that it can easily adopt new features.

It not only improved me professionally but also personally. It undoubtedly improved my thinking and problem solving skills.


