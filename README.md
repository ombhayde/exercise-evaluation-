AI Exercise Evaluator
The AI Exercise Evaluator is a web application that uses computer vision and pose estimation to track and evaluate exercise form in real-time. Currently, it supports squats and push-ups with immediate feedback on form and technique.
Features

Real-time Pose Detection: Uses MediaPipe to track body position during exercises
Automatic Rep Counting: Counts repetitions based on movement patterns
Form Analysis: Evaluates proper form with specific feedback on:

Squat depth and knee alignment
Back posture during exercises
Push-up depth and body alignment


Visual Feedback: Color-coded landmarks highlight problem areas
Exercise Metrics: Tracks reps, provides a form score, and shows current movement phase
Responsive Design: Works on various screen sizes

Requirements

Modern web browser with camera access (Chrome, Firefox, Safari, Edge)
Device with webcam
Internet connection (for loading required libraries)

Installation
No installation required! The application runs in your browser.

Simply open the HTML file in your web browser
Allow camera access when prompted

Usage

Position yourself where your full body is visible to the camera
Select an exercise:

Click "Start Squats" for squat evaluation
Click "Start Push-Ups" for push-up evaluation


Begin your exercise and receive real-time feedback
Click "Stop" when finished

Squat Form Rules
The app checks for:

Squat Depth: Proper knee bend during the down phase
Back Angle: Maintaining correct torso position (45-75 degrees)
Knee Alignment: Keeping knees tracking over toes

Push-Up Form Rules
The app checks for:

Elbow Bend: Proper depth in the down phase
Arm Extension: Full extension at the top position
Back Alignment: Maintaining a straight back (no sagging or piking)
Head Position: Proper neck alignment with spine

Technical Details

Built using MediaPipe for pose estimation
Uses Three.js for enhanced visual feedback (annotations)
Canvas API for drawing pose landmarks
Pure JavaScript implementation with no additional frameworks

Privacy

All processing happens locally in your browser
No video or image data is sent to any server
No data is stored between sessions

Limitations

Requires good lighting for accurate pose detection
Camera should capture your full body
Works best with plain backgrounds
May have reduced accuracy with loose clothing

Troubleshooting
Camera not starting?

Make sure you've allowed camera permissions
Try refreshing the page
Check if another application is using your camera

Poor tracking accuracy?

Improve lighting in your environment
Ensure your full body is visible
Wear form-fitting clothes for better landmark detection
Use a plain background

Performance issues?

Close other demanding applications
Reduce browser tabs running in background

Future Improvements

Additional exercise types (deadlifts, lunges, etc.)
Exercise history and progress tracking
Custom exercise parameter adjustments
Offline support
Mobile app version

License
This project is available for personal use.
