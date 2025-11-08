# Gesture Recognition Game

A minimal Bonsai workflow that runs real-time hand gesture detection.

When the workflow starts, you should see the following:
- A shader window displaying the current camera's view.
- A table layout panel showing the gesture recognition model's inference, a static image of classified gestures, and an experiment start button.

How it works:
- When you press the start button to begin, there will be a prompt on the shader window to get ready. 
- After a short delay, you will see an action prompt at the top. You need to perform the gesture for as long as possible before switching to the next action.
- You get scored based on the total amount of time you correctly perform the gesture.