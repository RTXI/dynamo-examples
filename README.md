###DYNAMO Models

**Requirements:** GMP library (included in Live CD)
**Limitations:** none noted


This is a collection of models built using the DYNAMO scripting language. These can be compiled using the DYNAMO Model Loader in RTXI. The result is a module based on the DefaultGUIModel class with labels and textboxes for each parameter. DYNAMO models are fully compiled into shared libraries so you only need to compile them once and then the compiled binary can be loaded via the regular Module Loader in the RTXI menu bar.

    brk.dynamo: Booth, Rinzel, Kiehn (1997) model of motoneurons
    chem_inhib_synapse.dynamo: creates a half-center oscillator model with two cells via two inhibitory chemical synapses
    event.dynamo: generic event example
    function.dynamo: a triggered stimulus
    hh.dynamo: Hodgkin-Huxley neuron
    hybrid_inhib_chem.dynamo: model that connects a model neuron to a real neuron
    morris-lecar.dynamo: Morris-Lecar model that outputs a voltage and a synaptic current, driven by input from another cell
    stimulated-morris-lecar.dynamo: Morris-Lecar model driven by a function generator
    wangbuzsaki.dynamo: Wang-Buzsaki model
