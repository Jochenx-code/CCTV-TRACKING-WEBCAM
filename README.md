🔒 CCTV Surveillance System with Motion Detection This is a multi-camera CCTV surveillance system built using Python, OpenCV, and Tkinter. It features live video feed display, motion detection, and real-time notification panel—all within a fullscreen OpenCV window and a simple GUI for camera management.

Build Status License

📸 Features

📷 Multi-Camera Support: Add multiple cameras by ID (e.g., 0 for default webcam).
🔍 Motion Detection: Uses frame differencing and contour analysis to detect movement.
🖥️ Live Feed Display: Fullscreen grid display of active camera feeds using OpenCV.
🛎️ Real-Time Notifications: Motion events are timestamped and shown on a side notification panel.
🧠 Persistent Motion Tracking: Maintains bounding boxes for smoother visual tracking of motion.
🪟 User-Friendly GUI: Tkinter-based interface for adding cameras and starting feeds.
🧰 Requirements

Python 3.x
OpenCV
NumPy
Tkinter (comes pre-installed with Python on most systems)
Installation
Install dependencies (if not already installed):

pip install opencv-python numpy
Run Locally
Clone the repository

git clone https://github.com/your-username/cctv-motion-detection.git
cd cctv-motion-detection
Run the script

python cctv_gui.py
Usage/Examples
Click "Add Camera" to register a camera by ID.
Click "Start Feeds" to launch the motion detection system.
Pressqin the OpenCV window to stop.
Camera ID Notes
Camera ID 0 refers to your default webcam.
Other IDs (1, 2, 3...) correspond to additional USB or network-connected cameras.
Sample Output
✅ Motion detected on Camera 0 at 2025-08-13 20:30:45
✅ Notification displayed on the right panel in fullscreen view.
Future Improvements
Save video recordings upon motion.
Email/SMS alerts.
Facial recognition integration.
Web-based remote view.


Author
Jochenx-code

License
This project is open-source and available under the MIT License.
