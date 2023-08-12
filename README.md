# Flexion Friend

[_Let's see that knee bend, friend!_](https://skortchmark9.github.io/flexion-friend/)

![Screenshot of the app](screenshot.png)

This is a web app for measuring and tracking knee angles. "Flexion" is the amount you can bend your knee. Most people have around -5 - 150° of flexion. However, if you're recovering from knee surgery, your range of motion will be much more limited, and you'll need to do daily exercises to recover it.

### How does it work?
The app uses your device's camera and a machine learning model to detect your knee angles. The model is [Movenet](https://www.tensorflow.org/hub/tutorials/movenet) from TensorFlow, and I have made almost no changes to the pose detection algorithms.

### How do I make it fullscreen?
Flexion Friend is a PWA! So, you just need to "add to homescreen" to make it fullscreen. Hit Share -> Add to Home Screen. When you open it from there, it should be fullscreen.
