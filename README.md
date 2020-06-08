# css-tilt-animation

How?
  - the parent div is relatively positioned
  - this allows the children divs to have absolute positioning so I can perfectly position them around the edges of the parent
  - it also allows for 1 of the children divs which holds the contents to be absolutely positioned spanning the whole parent
  - the edge children divs have a z-index of 1 to ensure they are stacked on top of the content child and susceptible to :hover
  - each of the children divs around the edges have :hover and are linked to the child holding the contents
  - depending on which edge child is hovered over, the contents child will transform accordingly giving the tilt effect
