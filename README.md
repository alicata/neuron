# neuron

## 1. Installation
```
pip install neuron
```

## 2. NEURON simulation - Basic example
from https://nrn.readthedocs.io/en/latest/tutorials/scripting-neuron-basics.html

Engine to simulate biologically realistic membranes with active and passive ion channels, combined with virtual connectivity and electrophysiology tools to drive and measure neuron and network behaviors.

- Create a passive cell membrane
- Create a synaptic stimulus onto the neuron.
- Modify membrane and stimulus.
- Visualize results
  
```
import neuron
from neuron import h, rxd
from neuron.units import ms, mV

soma = h.Section(name="soma")
h.topology()
```
