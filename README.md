| [3D Background Boxes](https://github.com/lana-20/50Projects50Days/tree/main/3DBackgroundBoxes) | [Live Demo](https://lana-20.github.io/3d-background-boxes/) |
 |----|----|
 
I am making a 3D boxes background. I am using modern CSS to create this 3D effect.
I am using a background gif for each one of the boxes. It's all the same image - a Pikachu image.
I am extending the background size beyond the the single box to make it as big as the container.
Then I dynamically calculate the background position, so I can move the boxes around and form what
looks like one big image. When really it's a just a bunch of the same image.
I am also adding an event listener to the "Magic ✨" button. When clicked, the whole box area shrinks
and gives the rotate/twirl effect on each box and then combines them all together,
so there's no spacing in between and it looks like one big connected image.
I am using CSS transforms and transitions, ::after and ::before pseudo selectors to achieve this rotation effect.
I am using a loop in JavaScript to go through these boxes and calculate the background position.
