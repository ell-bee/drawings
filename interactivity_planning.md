# Interactivity Planning

#### Interacting elements: 
I want to recreate pong, so the interacting elements are gonna be a circle ball and rectangle paddles.

#### Parameters
The paddles will be restrained to the vertical edges of the frame, so y = some value, and x = mouseX, and there will be two of them. The ball should only bounce when touching the paddle that you control. The other paddle will follow the y movement of the circle so that you only have to play as one paddle. If circle x == rectangle y, then dx *= -1. 
