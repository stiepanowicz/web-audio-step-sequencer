# Periodic Wave

The Web Audio API provides the capability to create and manipulate audio graphs for audio processing. The PeriodicWave interface represents a periodic waveform, which is a set of harmonically related sine waves that together form a complex waveform.

The 'real' and 'imag' properties of the PeriodicWave constructor represent the real and imaginary parts of the Fourier series coefficients of the custom waveform. The Fourier series is a mathematical representation used to represent a periodic waveform as a sum of sinusoidal components.

### real
A Float32Array containing the cosine terms that you want to use to form the wave (equivalent to the real parameter of BaseAudioContext.createPeriodicWave).

### imag
A Float32Array containing the sine terms that you want to use to form the wave (equivalent to the imag parameter of BaseAudioContext.createPeriodicWave).

These two numbers allow to create a custom periodic waveforms, which can then be used with an 'OscillatorNode'

https://developer.mozilla.org/en-US/docs/Web/API/PeriodicWave/PeriodicWave

