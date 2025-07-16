# 🖱️ Virtual Mouse using OpenCV and Python

This project implements a **Virtual Mouse** that uses hand gesture recognition with a webcam to control the mouse pointer and perform click actions. It is built using Python and OpenCV along with the MediaPipe library for hand tracking.

## 🎯 Objective

The goal is to simulate mouse movement and clicks using hand gestures without any physical mouse — turning your hand into a controller.

## 🌟 Features

* Track hand landmarks in real-time using webcam
* Move mouse cursor by tracking index finger
* Perform left and right click using specific finger gestures
* Customizable gesture detection
* Smooth cursor movement

## 🧰 Technologies Used

* Python
* OpenCV
* MediaPipe
* PyAutoGUI

## 📁 Project Structure

```
virtual-mouse/
│
├── virtual_mouse.py         # Main script
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies
```

## ⚙️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/virtual-mouse.git
   ```

2. Navigate to the project folder:

   ```bash
   cd virtual-mouse
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the script:

   ```bash
   python virtual_mouse.py
   ```

## 💡 Controls

* **Move Cursor**: Move your index finger
* **Left Click**: Index and middle fingers close together
* **Right Click**: (Optional) Use custom gestures or key binds

> Make sure your camera is turned on and positioned well for best tracking performance.


## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 🙋‍♀️ Author

**Sharanya Mishra**
Connect with me on [LinkedIn](https://www.linkedin.com/)
