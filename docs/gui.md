## GUI for MSST code 

GUI was prepared by **Bas Curtiz** and is based on [wxpython](https://en.wikipedia.org/wiki/WxPython) module.

![Window example](https://github.com/ZFTurbo/Music-Source-Separation-Training/blob/main/gui/wx_msst_screen.png)

### How to

How to use GUI with ZFTurbo's Music Source Separation Universal Training Code:

1. Install Python: https://www.python.org/ftp/python/3.11.6/python-3.11.6-amd64.exe
2. Install Microsoft Visual C++ 2015-2022 (x64): https://aka.ms/vs/17/release/vc_redist.x64.exe
3. Install Microsoft C++ Build Tools: https://visualstudio.microsoft.com/visual-cpp-build-tools/
Select Desktop development with C++
4. Install PyTorch: https://pytorch.org/get-started/locally/
5. Download and unzip Music Source Separation Universal Training Code:
https://github.com/ZFTurbo/Music-Source-Separation-Training
6. Open up CMD inside the folder and enter: `pip install -r requirements.txt` 
7. enter: `pip install wxpython` 
8. enter: `python gui-wx.py`
9. Download models - assign the config (.yaml) and checkpoint (.bin, .ckpt, or .th)
10. Done.

Video guide on [Youtube](https://youtu.be/gyxMCbDwfAw).