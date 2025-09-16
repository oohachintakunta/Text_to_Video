📂 Project Structure
├── app.py         # Flask app entry point, handles routes and requests
├── main.py        # Core logic for processing question/keyword and generating video
├── index.html     # Frontend form for user input + video player

⚙️ Features

Web Form Interface
Users can enter a question and a keyword through a simple HTML form.

Video Generation
Backend logic (main.py) processes the inputs and creates a video (output: final_video.mp4).

Automatic Playback
After form submission, the generated video is displayed in the browser and starts playing automatically

index

.

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/your-username/video-generation-app.git
cd video-generation-app

2. Set Up Environment

Make sure you have Python 3.8+ installed.

Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

3. Install Dependencies
pip install -r requirements.txt


⚠️ If you don’t have a requirements.txt, install Flask (and any video-related libraries you use in main.py):

pip install flask moviepy

4. Run the Application
python app.py
