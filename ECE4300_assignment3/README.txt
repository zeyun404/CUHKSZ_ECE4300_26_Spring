README.txt
Assignment 3: Hand-Gesture Interactive System in TouchDesigner
============================================================

BASIC FEATURES (7 pts)

1. Hand Tracking System Setup
   - MediaPipe plugin is used to detect and track both hands in real time
     via webcam. Hand position is accurately mapped to the screen.

2. Smooth & Stable Tracking Data
   - Hand tracking data has been smoothed using filters to eliminate
     jitter, resulting in stable and natural interaction.

3. Hand Landmark Visualization / UI
   - Key hand landmarks (fingertips and joints) are visualized as lines
     and points overlaid on the camera feed.

4. Gesture-Based Interaction
   - Right hand PINCH (index finger + thumb): controls image size.
     The closer the fingers, the smaller the image; the further apart,
     the larger the image.
   - Right hand ROTATION: triggers an image switch with a transition
     effect.
   - Right hand FULL PINCH (fingers fully closed): switches the visual
     to a black-and-white style of the original image.

5. Interactive Visual Feedback
   - When pinch gesture is detected, the image size changes visibly
     in real time.
   - When rotation gesture is triggered, a switching transition effect
     plays on screen.
   - When fully pinched, the screen switches to a black-and-white
     filter effect.

6. Visual Effects Driven by Hand Tracking
   - Right hand pinch distance drives the scale of the displayed image.
   - Right hand rotation drives an image transition visual effect.

7. Audio / Playback / Final Output Integration
   - Hand gestures control audio volume and sound effects in real time.
   - The final output combines camera feed, hand tracking visualization,
     visual effects, and audio into a complete interactive experience.

============================================================
BONUS FEATURES

1. Finger Tip Trail Effect
   - A yellow trail follows the fingertip
     as they move, leaving a motion trace on screen.
   - The trail length is set to show recent movement history.
   - To see the effect: move your hand across the camera view and
     watch the yellow trail follow the fingertip positions.

2. Water Ripple Visual Effect on Pinch
   - When the right hand performs a full pinch (index finger and thumb
     fully closed), the display switches to a black-and-white style
     overlaid with a water ripple / particle visual effect.
   - To trigger: bring right hand index finger and thumb together
     until fully pinched.

============================================================
HOW TO RUN
- Open the .toe file in TouchDesigner
- Make sure your webcam is connected
- Select the correct webcam in the MediaPipe node parameters
- Place your hand in front of the webcam to begin interaction
============================================================