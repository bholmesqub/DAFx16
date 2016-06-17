---
layout: page
title: Physical model parameter optimisation for calibrated emulation of the Dallas Rangemaster Treble Booster guitar pedal
---
This is the companion webpage for the 19th International Conference on Digital Audio Effects paper **"Physical model parameter optimisation for calibrated emulation of the Dallas Rangemaster Treble Booster guitar pedal"** by Ben Holmes and Maarten van Walstijn.

### Audio samples

#### Dry chord:

To provide an audio comparison of the results of the optimisations, a dry guitar chord is used as an input signal.

<audio controls>
  <source src="{{ site.baseurl }}/audio/chord.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

#### Nominal models:

The nominal samples demonstrate what the behaviour of the model using the nominal parameters from Table 1.

Nominal germanium model:
<audio controls>
  <source src="{{ site.baseurl }}/audio/chord-germanium-nominal.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

Nominal silicon model:
<audio controls>
  <source src="{{ site.baseurl }}/audio/chord-silicon-nominal.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

#### Optimised models:

The optimised samples demonstrate the behaviour of the model after optimising the parameters. The parameter sets used are the same sets used in the validation plots in Figure 7.

Optimised germanium model:
<audio controls>
  <source src="{{ site.baseurl }}/audio/chord-germanium-optimised.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

Optimised silicon model:
<audio controls>
  <source src="{{ site.baseurl }}/audio/chord-silicon-optimised.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

#### Circuit samples:

Finally, samples of the chord processed through the circuit are provided for comparison.

Germanium circuit:
<audio controls>
  <source src="{{ site.baseurl }}/audio/chord-germanium-circuit.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

Silicon circuit:
<audio controls>
  <source src="{{ site.baseurl }}/audio/chord-silicon-circuit.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>
