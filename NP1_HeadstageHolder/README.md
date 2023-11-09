**NP1_HeadstageHolder**

  The NP1_HeadstageHolder was designed to allow free-moving recordings with the NP1_Apollo_Implant (https://github.com/Coen-Lab/chronic-neuropixels). 

**Purpose and background**

In our first recordings with the NP1_Apollo_Implant, we folded the probe flex underneath the caps (within the implant) so that the ZIF connector of the probe permanently protruded from the top of the implant (Fig 1A). During recordings, the headstage was connected to the probe and sat unsuported above the implant/animal. Whilst recordings were possible in this configuration, the force exerted by the animal movement on the ZIF connector introduced noise into the recordings. Worse, after a few recordings this force and tension on the ZIF connector  resulted in damage ZIF pads on the flex. This damage resulted in frequent error #14, 'BIST_ERROR', for the Parallel Serial Bus probe tests, which indicates a poorly seated probe.
  
To prevent damage to the ZIF pads during recordings we designed this NP1_HeadstageHolder.  

![image](https://github.com/NathanaelONeill/Apollo_Implant_Modifications/assets/94172541/aa189e55-18af-4ec1-8b7e-e2be5f00a9da)

**Usage**

The headstage can be attached to the NP1_HeadstageHolder with epoxy (permanent) or a wrap of parafilm (temporary). Prior to recordings, the arms of the NP1_HeadstageHolder are slid onto the ridges of the NP1_Payload (like with the NP1_PayloadHolder) (Fig 1B). The probe flex is lopped between the NP1_Payload and NP1_HeadstageHolder and attached to the ZIF connector at the base (Fig 1C). Importantly, for this to work the flex needs to be full length.

**Printing**

Selective laser sintering. Material: Nylon PA12. Printed by: www.sgd3d.co.uk. Weight (without the headstage) = 0.5 g

**Designs**

Design was by Nathanael O'Neill, a postdoc in the Lignani lab, UCL email: skgtnon@ucl.ac.uk
  
The dimensions of the headstage mount of the NP1_HeadstageHolder were from Dr Emily A. Aery Jones's (https://github.com/emilyasterjones) excellent protocol: Chronic Recoverable Neuropixels in Mice https://github.com/emilyasterjones/chronic_NPX_mouse
  
The arms of the NP1_HeadstageHolder were adapted from the NP1_PayloadHolder design by Pip Coen (https://github.com/pipcoen) and Célian Bimbard (https://github.com/cbimbo).
