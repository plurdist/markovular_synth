# Granular–Markov Hybrid System (Max/MSP)

This repository contains a set of Max/MSP patches used as part of a live performance instrument combining granular synthesis, a Markov-based generative system, vocoding, and effects processing.

The system is designed to encourage exploration of granular textures from source audio, with an optional Markov-based module semi-autonomously generating MIDI data that can modulate the sound in real time. 

These patches draw on a range of existing ideas and tutorials, which have been adapted and integrated into a single performance system.

## Files

- `markovularMain.maxpat` – main performance patch  
- `markovular.maxpat`
- `markov.maxpat` – Markov MIDI generator (requires training data)  
- `MIDI_Length.maxpat` 
- `robot_master.maxpat` 
- `robot_pfft.maxpat` – FFT-based processing module  

## Usage

- Keep all patches in the **same folder**
- Open `markovularMain.maxpat` to run the system
- The Markov component is optional and not required to use the basic granular system
- Train the Markov patch with MIDI before performance  
- Replace audio file as required for granular processing  

## References / Credits

- Granular synthesis approach inspired by Oliver Thurley  
  https://www.youtube.com/watch?v=g3nAeDWgf9Y  

- Markov system design inspired by Samuel Pearce-Davies  
  https://www.youtube.com/watch?v=LG-GYFyJw74  

- `ml.markov` object from the ml.* toolkit by Benjamin Day Smith  
  https://www.benjamindaysmith.com/ml-machine-learning-toolkit-in-max/

## Notes

- Built for live, improvised performance contexts  
- Source material can include any audio (percussive samples, speech, instrumental recordings, etc.)
