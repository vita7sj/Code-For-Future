libs： <https://github.com/muodov/kociemba>   <https://github.com/asweigart/pyautogui>

如果是Win下，记得先安装下VC++库，不然会有`error: Microsoft Visual C++ 14.0 or greater is required`的错误
> PS：如果是python3.7.x系列，可以直接安装官方提供的whl包<https://pypi.org/project/kociemba/1.2.1/#files>，下载后把名字改成`kociemba-1.2.1-cp37-none-any.whl`就可以通过pip安装了

demo：<https://www.bilibili.com/video/BV12i4y1G74V>

```py

附录

# pip install .\kociemba-1.2.1-cp37-none-any.whl
Looking in indexes: https://pypi.tuna.tsinghua.edu.cn/simple
Processing f:\kociemba-1.2.1-cp37-none-any.whl
Requirement already satisfied: cffi>=1.0.0 in d:\program files (x86)\miniconda py37\lib\site-packages (from kociemba==1.2.1) (1.14.6)
Requirement already satisfied: future in d:\program files (x86)\miniconda py37\lib\site-packages (from kociemba==1.2.1) (0.18.2)
Requirement already satisfied: pycparser in d:\program files (x86)\miniconda py37\lib\site-packages (from cffi>=1.0.0->kociemba==1.2.1) (2.20)
Installing collected packages: kociemba
Successfully installed kociemba-1.2.1

# pip install pyautogui
Looking in indexes: https://pypi.tuna.tsinghua.edu.cn/simple
Collecting pyautogui
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/f0/76/7a0ec1013bc3559b7438f6773cba05ffaec600b8989be2d621a144e39b50/PyAutoGUI-0.9.53.tar.gz (59 kB)
     |████████████████████████████████| 59 kB 1.2 MB/s
Collecting pymsgbox
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/7d/ff/4c6f31a4f08979f12a663f2aeb6c8b765d3bd592e66eaaac445f547bb875/PyMsgBox-1.0.9.tar.gz (18 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
    Preparing wheel metadata ... done
Collecting PyTweening>=1.0.1
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/b9/f8/c32a58d6e4dff8aa5c27e907194d69f3b57e525c2e4af96f39c6e9c854d2/PyTweening-1.0.3.zip (15 kB)
Collecting pyscreeze>=0.1.21
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/4b/64/1087b4f2c1c5ca14e6ceba7d1e116c494629de36b9882cf014ae02814ce5/PyScreeze-0.1.27.tar.gz (25 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
    Preparing wheel metadata ... done
Collecting pygetwindow>=0.0.5
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/e1/70/c7a4f46dbf06048c6d57d9489b8e0f9c4c3d36b7479f03c5ca97eaa2541d/PyGetWindow-0.0.9.tar.gz (9.7 kB)
Collecting mouseinfo
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/28/fa/b2ba8229b9381e8f6381c1dcae6f4159a7f72349e414ed19cfbbd1817173/MouseInfo-0.1.3.tar.gz (10 kB)
Collecting pyrect
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/2f/68/bd7bf96fc44217e769f27912e6c9bb3e9987cba286054af6120448ce8212/PyRect-0.1.4.tar.gz (15 kB)
Collecting Pillow>=5.2.0
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/ed/b8/efda27f02cc00de404fd341d989afebf811ee208f5bf6e3ec84032618ee5/Pillow-8.3.2-cp37-cp37m-win_amd64.whl (3.2 MB)
     |████████████████████████████████| 3.2 MB ...
Collecting pyperclip
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/a7/2c/4c64579f847bd5d539803c8b909e54ba087a79d01bb3aba433a95879a6c5/pyperclip-1.8.2.tar.gz (20 kB)
Building wheels for collected packages: pyautogui, pygetwindow, pyscreeze, PyTweening, mouseinfo, pymsgbox, pyperclip, pyrect
  Building wheel for pyautogui (setup.py) ... done
  Created wheel for pyautogui: filename=PyAutoGUI-0.9.53-py3-none-any.whl size=36583 sha256=7fca5306c15c3a08c50e938785b5254af4451a388d76ce52fdd5d953143dfb0e
  Stored in directory: c:\users\panday\appdata\local\pip\cache\wheels\ba\be\c5\7dc11fdf333764467ce4b4965136a74fa29893e62ef20bfe3c
  Building wheel for pygetwindow (setup.py) ... done
  Created wheel for pygetwindow: filename=PyGetWindow-0.0.9-py3-none-any.whl size=11078 sha256=04a324c70091707bc58d1e7a221309320d49350b40a2a1c6950835b333f72de0
  Stored in directory: c:\users\panday\appdata\local\pip\cache\wheels\7f\24\90\e310494119ef55c0d3decf95ecc9badc9451607ecd3ce7e0e8
  Building wheel for pyscreeze (PEP 517) ... done
  Created wheel for pyscreeze: filename=PyScreeze-0.1.27-py3-none-any.whl size=12893 sha256=80e652c2c193e769a9633f35818440f52049e32232ec0be8967a837df0dc66cf
  Stored in directory: c:\users\panday\appdata\local\pip\cache\wheels\16\12\0f\8f99b7309041d2dfb7757b3a072e71a996d375b8443785b8fa
  Building wheel for PyTweening (setup.py) ... done
  Created wheel for PyTweening: filename=PyTweening-1.0.3-py3-none-any.whl size=3815 sha256=efef4092bf7c979f0905a79425413228f53b7baff2249c44444158911ad933df
  Stored in directory: c:\users\panday\appdata\local\pip\cache\wheels\e7\33\1d\b7f874fdcfda8cce6e415d3c53028a0cf20d5add84d03bbf66
  Building wheel for mouseinfo (setup.py) ... done
  Created wheel for mouseinfo: filename=MouseInfo-0.1.3-py3-none-any.whl size=10905 sha256=e7e9b6b2c7b8cba86374800345755d2a208fd1015276ce12c911e384b537f142
  Stored in directory: c:\users\panday\appdata\local\pip\cache\wheels\f4\15\d1\6a06e4be3305e722e53d3b8efd556185978a12e16012e06517
  Building wheel for pymsgbox (PEP 517) ... done
  Created wheel for pymsgbox: filename=PyMsgBox-1.0.9-py3-none-any.whl size=7420 sha256=8a73cabda12cd2dad449a1a7910207b051e2c3af054e31fec3977b5164dff944
  Stored in directory: c:\users\panday\appdata\local\pip\cache\wheels\88\f8\97\fcc8948d0d54635582b3b723cc9515996f4cd6abf6d01e7aba
  Building wheel for pyperclip (setup.py) ... done
  Created wheel for pyperclip: filename=pyperclip-1.8.2-py3-none-any.whl size=11107 sha256=7cd87df003d431b5022d7b91452c4ec6d3b41eaebce2ca65160c3ee6056ce675
  Stored in directory: c:\users\panday\appdata\local\pip\cache\wheels\f0\8e\31\5a0b03f1dd1e6663be768d712b4088315490722d6b1dd8fbf8
  Building wheel for pyrect (setup.py) ... done
  Created wheel for pyrect: filename=PyRect-0.1.4-py2.py3-none-any.whl size=9547 sha256=e93cfec970537729c62df5aedc90f0e93bb42b9d31ae08157dd95814a5d68fef
  Stored in directory: c:\users\panday\appdata\local\pip\cache\wheels\47\1f\9c\8e4699d8322c785d1027e1354b47fa3d645c12705a18f562dc
Successfully built pyautogui pygetwindow pyscreeze PyTweening mouseinfo pymsgbox pyperclip pyrect
Installing collected packages: pyrect, pyperclip, Pillow, PyTweening, pyscreeze, pymsgbox, pygetwindow, mouseinfo, pyautogui
Successfully installed Pillow-8.3.2 PyTweening-1.0.3 mouseinfo-0.1.3 pyautogui-0.9.53 pygetwindow-0.0.9 pymsgbox-1.0.9 pyperclip-1.8.2 pyrect-0.1.4 pyscreeze-0.1.27
