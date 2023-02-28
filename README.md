## Goal
Accept a photo from the client (frontend), send to the Flask server (backend),
process image (perform Optical Character Recognition) and return result to client

Design decision:
- should the client call DeepL API to translate or should the Flask backend do this as part
of image processing

## Tech Stack
Expo frontend (React Native framework)
Flask backend (b/c it's python)

Tutorials
1. Main tutorial (getting/sending photo to Flask backend from Expo app)
https://narainsreehith.medium.com/upload-image-video-to-flask-backend-from-react-native-app-expo-app-1aac5653d344
2. Setting up python venv
https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment
3. Installing python3 in gitbash on Windows
https://programmingwithjim.wordpress.com/2020/09/08/installing-python-3-in-git-bash-on-windows-10/

## Python Virtual Environment (backend/v_env)
### Commands
source v_env/Scripts/activate
deactivate