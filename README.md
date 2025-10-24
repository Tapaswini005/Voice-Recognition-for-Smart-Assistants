
[VRSA Readme.pdf](https://github.com/user-attachments/files/23130714/VRSA.Readme.pdf)


Voice-Recognition-for-Smart-Assistant:

  A Python-based Voice Assistant that can perform various tasks like playing music, setting alarms/reminders,
  reading clipboard content, fetching weather,opening applications, telling jokes/quotes, searching Wikipedia,
  and more. The assistant can run in the background with a system tray icon and responds to voice commands using a wake word.
  
Features:

  •	Voice Recognition & Commands:
           ▶	Wake word detection (assistant)<br>
           ▶	Greeting based on time of day<br>
           ▶	Weather updates<br>
           ▶	Search Wikipedia<br>
           ▶	Read clipboard content<br>
           ▶	Play music from a directory<br>
           ▶	Tell jokes and motivational quotes<br>
           ▶	Check system “feeling” based on CPU/memory usage<br>

  •	Task Automation:
           o	Set alarms with notifications<br>
           o	Take notes and save to file<br>
           o	Set reminders for tasks at specific times<br>
           o	Open common applications like Google, YouTube, Notepad, Calculator, Visual Studio Code<br>

  •	Background Mode:
           o	Runs in the background with optional system tray support<br>
           o	Logs activities to a voice_assistant.log file<br>

  •	Cross-Platform Considerations:
           o	Compatible with Windows<br>
           o	Optional system tray icon using pystray and Pillow<br>


Installation:

  1.	Clone the repository:
           git clone https://github.com/Tapaswini005/Voice-Recognition-for-Smart-Assistant.git cd voice-assistant<br>
  
  2.	Install dependencies:
            	pip install -r requirements.txt<br>
 	        Dependencies include:<br>
            o	speechrecognition<br>
            o	pyttsx3<br>
            o	wikipedia<br>
            o	pyjokes<br>
            o	psutil<br>
            o	pyperclip<br>
            o	schedule<br>
            o	pystray (optional)<br>
            o	pillow (optional)<br>
 3.	Run the assistant:
             	python voice_assistant.py<br>


Usage:
           •	Say “assistant” to wake up the assistant.<br>
           •	Commands you can try:<br>
                o	play music<br>
                o	set alarm for 14:30<br>
                o	take note Buy groceries<br>
                o	set reminder call mom at 17:00<br>
                o	read clipboard<br>
                o	open YouTube<br>
                o	search Python programming<br>
                o	tell joke<br>
                o	tell quote<br>
                o	how are you?<br>
                o	goodbye to stop the assistant<br>

Project Structure:
            voice-assistant/<br>
      │<br>
      ├─ assets/<br>
      │   └─ music/           # Store music files here<br>
      ├─ notes/               # Notes saved by the assistant<br>
      ├─ reminders/           # Reminders saved by the assistant<br>
      ├─ voice_assistant.py   # Main assistant script<br>
      ├─ requirements.txt     # Python dependencies<br>
      └─ README.md<br>

System Tray Support:
If pystray and Pillow are installed, the assistant creates a system tray icon with the following options:<br>
      •	Status: Shows if the assistant is running<br>
      •	Show Log: Opens the activity log<br>
      •	Restart: Restarts the assistant<br>
      •	Exit: Stops the assistant<br>

Logging:
All actions and errors are logged in voice_assistant.log for debugging and monitoring purposes.<br>

License:
This project is open-source under the MIT License.<br>








