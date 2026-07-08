# Strykebrett - Version: [1.0]

Date: 2023-10-16

Name: Benjamin Dehli

Profile: [store.dehlimusikk.no][Gumroad profile]

## Included formats

- Decent Sampler

## Release notes

### Version 1.0 (2023-10-16)

- First version released

## Description

A sampled Logan String Melody II with some added features.

## Technical specification

|                       | Sample rate | Bit depth | Channels   | Number of files | File size |
|----------------------:|------------:|----------:|------------|----------------:|----------:|
|           **Samples** |    44.1 kHz |    24 bit | 1 (mono)   |             121 |  171.7 MB |
| **Impulse responses** |      48 kHz |    24 bit | 2 (stereo) |               4 |    3.6 MB |

## User Interface

|![User interface for the "Strykebrett" library](/Screenshots/strykebrett.png)|
|:--:|
|User interface for the "Strykebrett" library|

The user interface offers precise control over every aspect of the instrument and effects.
Explore parameters to refine your sound, including control over the six drawbars, envelope, amplitude modulation with LFOs, highpass and lowpass filters, velocity/dynamics, oscillator drifting, and the immersive effects of ensemble, phaser, echo and reverb.

### Mixer (Bass / Treble)

|![Drawbar controls for the bass and treble section of the keyboard](/Screenshots/mixer.png)|
|:--:|
|Drawbar controls for the bass and treble section of the keyboard|

Unleash the power of the six drawbars to shape your tone with precision. Each drawbar controls the amplitude of a specific octave or sound, offering you unparalleled control over the instrument's harmonic richness.

### Voltage Controlled Amplifier (VCA)

|![Envelope and LFO controls for the voltage controlled amplifier](/Screenshots/vca.png)|
|:--:|
|Envelope and LFO controls for the voltage controlled amplifier|

#### ADSR Envelope

Shape your sound precisely with the Attack, Decay, Sustain, and Release parameters. Whether you desire a punchy, staccato tone or a smooth, lingering ambiance, the ADSR envelope allows you to tailor the dynamics to your liking.

- Attack
  - Individual attack time of the amplitude envelope for four of the drawbars
- Decay
  - Individual decay time of the amplitude envelope four of the drawbars
- Sustain
  - Individual sustain level of the amplitude envelope four of the drawbars
- Release
  - Individual release time of the amplitude envelope four of the drawbars

#### Low-frequency Oscillator (LFO)

The Rate and Depth knobs enable you to modulate the amplitude of four of the drawbars with the desired depth and rate using the Low-Frequency Oscillator (LFO), opening up a world of rhythmic possibilities. The LFOs for the treble section has a sine waveform for smooth transitions. The LFO for the bass section has a sawtooth waveform for a rhythmic effect.

- Rate
  - LFO rate determines the speed at which the modulation occurs
- Depth
  - Adjust the LFO depth to introduce subtle or pronounced variations in volume

### Voltage Controlled Filter (VCF)

|![Controls for the highpass and lowpass filters](/Screenshots/vcf.png)|
|:--:|
|Controls for the highpass and lowpass filters|

Strykebrett has a highpass filter and a lowpass filter. The highpass filter ranges from 20 Hz to 2000 Hz and the lowpass filter ranges from 200 Hz to 8000 Hz.

- On / Off
  - Turns on or off the filter
- Freq
  - Cutoff frequency for the filter
- Res
  - Amount of resonance at cutoff frequency

## Oscillators

|![Button controls for the oscillators](/Screenshots/oscillators.png)|
|:--:|
|Button controls for the oscillators|

- Dyn
  - Turns on or off the velocity controlled amplitude
- Drift
  - When enabled, each sample will have a slight pitch drift. The pitch drift for each sample is unique and independent. It's less pitch drift in the bass samples than the treble samples.

## Ensemble

|![Button controls for the ensemble effects](/Screenshots/ensemble.png)|
|:--:|
|Button controls for the ensemble effects|

- O
  - 3 stereo choruses with different speed and depth
- Acc
  - Turns the ensemble off
- Solo
  - Fast stereo vibrato
- Organ
  - A slow stereo chorus

## Effects

The phaser is the built-in phaser from DecentSampler. The echo and reverb effects are achieved using carefully crafted impulse responses. The echo effect employs a Fulltone Tube Tape Echo recorded twice for stereo, while the reverb effect draws from a Chase Bliss Audio & Meris CXM 1978 reverb pedal with a room setting.

### Phaser

|![Controls for the phaser](/Screenshots/phaser.png)|
|:--:|
|Controls for the phaser|

- On
  - Turns the phaser on and off
- Color
  - Adds more feedback to the phaser
- Rate
  - Adjust the rate of the phaser modulation

### Echo

|![Controls for the tape echo impulse response](/Screenshots/echo.png)|
|:--:|
|Controls for the tape echo impulse response|

Select from two distinctive echo options: the short echo, delivering a classic slapback effect, and the long echo, characterized by a slower decay and numerous repeats.

- On
  - Turns the echo on and off
- Long
  - Switches between a short slapback echo and a long echo with slow repeats and high feedback
- Mix
  - Mix between direct signal and echo signal

### Reverb

|![Controls for the room reverb impulse response](/Screenshots/reverb.png)|
|:--:|
|Controls for the room reverb impulse response|

You'll also find two reverb effects: the short reverb, evoking the intimacy of a small room, and the long reverb, enveloping your sound in the vastness of a spacious environment.

- On
  - Turns the reverb on and off
- Long
  - Switches between a short/small room reverb and a long/big room reverb
- Mix
  - Mix between direct signal and reverb signal

[Gumroad profile]: https://store.dehlimusikk.no/
