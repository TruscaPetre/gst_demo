# gst_demo
Demo usage of gstreamer and deepstream. 

I mainly followed the tutorial I have found from [this repository ](https://gist.github.com/velovix/8cbb9bb7fe86a08fb5aa7909b2950259) which also has a [Youtube Video](https://www.youtube.com/watch?v=HDY8pf-b1nA) Attached where he shows and explains things 

I didn't find mentioned in the git repo, but it is mentioned in the video:
- This project should sit in the root: `location_of_msys/msys64/home/` 
- For my project, I have used a the python environment from `location_of_msys/msys64/mingw64/bin/python`
- but in my msys, aparently it was not added to the path, so I added it with the command `export PATH=~/../../mingw64/bin:$PATH`
- Not specified in the video, but for better integration, you can integrate the MSYS2 terminal in vscode using the following steps:
  - Open command palette and type: `workspacejson`
  - Paste in the json the commands from [How do I integrate MSYS2 shell into Visual studio code on Window?](https://stackoverflow.com/questions/45836650/how-do-i-integrate-msys2-shell-into-visual-studio-code-on-window)

Run in terminal with: 
`python3 main.py`

