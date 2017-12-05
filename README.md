# component-composable-map

A composable map component has:
- a Vue SFC as root, but...
- ...most of the logic outside a Vue SFC
- can add arbitrary layers to a map
- layers simple emit events on click (other interactions?)
- layers can be styled
- control for switching layers on/off happens outside the Vue SFC
- re-rendering the data is smart, only does what is needed, not redrawing all layers every time


