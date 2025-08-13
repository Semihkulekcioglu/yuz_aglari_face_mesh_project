# Face Mesh Project

This project is a Python application that performs face mesh detection and analysis using MediaPipe.

## 🚀 Features

- **Real-time Face Detection**: Face mesh detection in video streams
- **468 Face Landmarks**: MediaPipe's advanced facial landmark system
- **FPS Indicator**: FPS counter for performance monitoring
- **Video Support**: Support for MP4, AVI and other video formats

## 📋 Requirements

```bash
pip install opencv-python
pip install mediapipe
```

## 🎯 Usage

1. Clone the project:
```bash
git clone https://github.com/Semihkulekcioglu/yuz_aglari_face_mesh.git
cd yuz_aglari_face_mesh
```

2. Install required libraries:
```bash
pip install -r requirements.txt
```

3. Run the program:
```bash
python "Yuz_aglari(Face_mesh).py"
```

## 📁 Project Structure

```
Yüz Ağları/
├── Yuz_aglari(Face_mesh).py    # Main program file
├── video1.mp4                  # Test video file
├── video2.mp4                  # Test video file
├── video3.mp4                  # Test video file
├── Results/                     # Result images
│   ├── Result_1.png
│   └── Result_2.png
├── README.md                   # Turkish description
├── README_EN.md               # English description
├── requirements.txt            # Python dependencies
└── .gitignore                 # Git ignore file
```

## 🔧 Customization

- **Video Source**: Change the filename in `cap = cv2.VideoCapture("video2.mp4")` line
- **Face Count**: Modify `max_num_faces = 1` parameter to detect multiple faces
- **Drawing Style**: Adjust visual style by modifying `drawSpec` parameters

## 📸 Screenshots

When the program runs:
- Face meshes are drawn in real-time
- Coordinates of each facial landmark are printed to console
- FPS value is displayed in the top-left corner of the screen

## 🤝 Contributing

1. Fork this repository
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'New feature added'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## 📝 License

This project is licensed under the MIT License.

## 📞 Contact

You can open issues for questions or send pull requests.

---

**Note**: This project uses MediaPipe and OpenCV libraries. For more information, visit [MediaPipe Documentation](https://mediapipe.dev/) and [OpenCV Documentation](https://opencv.org/).
