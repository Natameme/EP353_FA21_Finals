# RandWave: Randomized Wavetable File Generator
**RandWave** is a C program which generates files for use with wavetable synthesizers which allow users to import their own wavetables. Each run of the program produces a completely unique wavetable file. **RandWave** provides a great way to inspire creativity and diversity in your synthesis!

![RandWave_Serum1](https://github.com/mayawagner/RandWave/blob/main/Assets/RandWave_Serum1.png)
![RandWave_Serum2](https://github.com/mayawagner/RandWave/blob/main/Assets/RandWave_Serum2.png)  

^ wavetables made with RandWave ^


The program runs easily in the **macOS Terminal** and allows the user to import their desired file saving location and choose between four base waveforms for their wavetable file.

Once a file is generated, it can be imported into any software wavetable synthesizer with user import functionality. Each file generated has pitch **C4**, making it perfect for importation with no transposition or key-mapping necessary. Some compatible synths include:

- **Wavetable** by Ableton
- **Serum** by Xfer
- **VITAL** by Vital Audio
- **Pigments 2** by Arturia
- **Codex** by Waves

## Example Wavetables
**RandWave** works by randomly clipping a waveform over time. Some examples of wavetable files generated by the program and some example applications can be found in in the `Examples` folder of this repository! This folder also contains an Ableton Project which has examples of application with Ableton's *Wavetable* and Xfer's *Serum*.

![RandWave_Ableton1](https://github.com/mayawagner/RandWave/blob/main/Assets/RandWave_Ableton1.png)

![RandWave_Ableton2](https://github.com/mayawagner/RandWave/blob/main/Assets/RandWave_Ableton2.png)

^ wavetables made with RandWave ^

## Running The Program
This repository includes an executable file called `RandWave` in the `Executable` folder. This file is intended for **macOS Systems.** Download the file for simple usage, or clone the repository for access to the code.

Once the executable file is obtained, note the location of the file on your computer. Open the `Terminal` application on your Mac and use `cd` to navigate to the location of the file.

For example, if the file is located on your desktop, you would enter `cd Desktop` and press enter.

Once terminal reads the location of your executable file, type `./RandWave` into the console and press enter. The program will run. Follow the directions to generate your wavetable file!

![RandWave Terminal Screenshot](https://github.com/mayawagner/RandWave/blob/main/Assets/RandWave_Terminal.png)

## Created by Maya Wagner
Maya Wagner is a young music technologist, music producer, and musical artist currently studying Electronic Production and Design with minors in Creative Coding and Electronic Performance at *Berklee College of Music.*

**For more information about the author visit www.mayawagnermusic.com.**