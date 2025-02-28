# 📦 Project Releases & Compatibility  


## How i make the release files.

```zip -r ubuntu_settings_24.04_v0.zip . -x ".git*"```

Example Code:

zip -r ubuntu_settings_24.04_v1.zip . -x ".git*"

zip -r ubuntu_settings_24.04_v2.zip . -x ".git*"


By running this upper command i will get a zip file of the name of my desired file without the .git folder and then i use this file in the Binary in the release section, and it become available as a release to use in later time.



I want to create **official releases** for this repository to ensure:  
- Easy usage without dependency issues.  
- Guaranteed compatibility with the latest Ubuntu ISO files.  
- A stable experience on new Ubuntu Desktop installations.  

Currently, I don’t have a clear plan for managing releases, but I am actively working on it.  
Future updates will include a structured release system to improve usability and stability. 🚀  
