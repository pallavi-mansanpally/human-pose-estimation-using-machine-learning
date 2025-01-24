# human-pose-estimation-using-machine-learning
## Installation Instructions for Human Pose Estimation Project

To set up the Human Pose Estimation application on your local machine, please follow these steps:

### Prerequisites
- **Python Version**: Ensure you have Python 3.8 or higher installed.
- **Package Manager**: Install pip, which is included with Python installations.

### Step-by-Step Installation

1. **Clone the Repository**:
   Open your terminal (Command Prompt, PowerShell, or any terminal emulator) and run the following command to clone the repository:
git clone https://github.com/pallavi-mansanpally/human-pose-estimation-using-machine-learning.git
cd Human-Pose-Estimation

2. **Set Up a Virtual Environment (Optional but Recommended)**:
It’s a good practice to use a virtual environment to manage dependencies. You can create one using:
python -m venv venv
Activate the virtual environment:
- On Windows:
  ```
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```
  source venv/bin/activate
  ```

3. **Install Required Packages**:
Use pip to install the necessary libraries specified in the `requirements.txt` file:
pip install -r requirements.txt

5. **Open in Browser**:
Once the application is running, open your web browser and go to [http://localhost:8501](http://localhost:8501) to interact with the pose estimation tool.

### Additional Information
- If you encounter issues during installation, ensure that all dependencies are compatible with your Python version.
- For optimal performance, consider using a machine with a compatible GPU if you're working with deep learning models.
