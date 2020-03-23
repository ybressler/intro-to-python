# Intro-to-Python
Some helpful notebooks to get you started on learning python!

## Google Classroom
I've put together a class in [Google Classroom](https://classroom.google.com/) – my first time doing this so bear with me. Use the code `gto5lja` to join.

---
# Loading data
To load the required data for module II, you will need to load a publically available file from Google Cloud. Do so with the following code:
```
import requests

url = "https://storage.googleapis.com/yb-intro-to-python/the%20tempest%20(scenes%201-2).json"

r = requests.get(url)
data = r.json()
```
