# Doodle Jump cpp SFML

------
**The mobile game *Doodle Jump* practice in C++ and SFML**<br>
**Code reference from FamTrinli's YouTube channel**

[YouTube video link](https://www.youtube.com/watch?v=7lmDFAI_jJ8)<br>
[![](http://img.youtube.com/vi/7lmDFAI_jJ8/0.jpg)](http://www.youtube.com/watch?v=7lmDFAI_jJ8 "")

I have poor English ability so I can't describe clearly and there may some grammar/word mistakes. My native language is Chinese so I will write down both English and Chinese.<br>
I am a beginner, please give me some suggestions to improve my coding ability. English advice also. :)

Doodle Jump game in C++ and SFML, there is no OOP conception but simple code you can understand easily.<br>
I watch FamTrinli's YouTube channel to learning and he write the game by C++. I rewrite it in new standards(random number), more clear variables name, comments to understand and add some features.

Using:
------
If you don't know how to set.(sorry for my English ability...) You can watch this [video](https://www.youtube.com/watch?v=axIgxBQVBg0) to set environment.
1. Run Visual Studio 2017 Community
2. Download [SFML 32-bit](https://www.sfml-dev.org/download.php) and [set](https://www.sfml-dev.org/tutorials/2.5/start-vc.php)
3. Creat a folder under the project names **SFML** and copy folders into it.(bin, include, lib)
4. Bulid and run project
5. An error will appear. Copy dll files in **bin** into **Debug** folder.(openal32.dll, sfml-audio-d-2.dll, sfml-graphics-d-2.dll, sfml-network-d-2.dll, sfml-system-d-2.dll, sfml-window-d-2.dll)
6. Rerun the project.

To be fix:
----------
No UI<br>
&nbsp;&nbsp;-Game start immediately when you run this project, no time for player to prepare<br>
&nbsp;&nbsp;-If you want to restart after game over you should rerun the project

The platform generate unnaturally<br>
&nbsp;&nbsp;-Platforms may overlapping<br>
&nbsp;&nbsp;-new platform maybe to high that player can't go on anymore

[Code reference](https://www.youtube.com/watch?v=7Vf_vQIUk5Q)<br>
[SFML](https://www.sfml-dev.org/)

-------
用C++與SFML寫成的Doodle Jump，裡面沒有使用OOP觀念（把角色做成物件等），但是用直觀好了解的邏輯撰寫<br>
程式碼參考自FamTrinli的YouTube頻道，我用新標準重寫(隨機數)、將變數名稱取得更有意義、加入註解並增加了一些功能

使用：
----------
如果你對設置有疑問，可以看這部[影片](https://www.youtube.com/watch?v=axIgxBQVBg0)教學
1. 開啟Visual Studio 2017 Community
2. 下載[SFML 32-bit](https://www.sfml-dev.org/download.php)並[設置環境](https://www.sfml-dev.org/tutorials/2.5/start-vc.php) 
3. 在專案底下開一個資料夾取名為SFML，並將下載的SFML裡面的三個資料夾(bin、include、lib)放進去
4. 建置並執行專案
5. 會出現一個錯誤。複製bin資料夾裡面的dll檔案(openal32.dll、sfml-audio-d-2.dll、sfml-graphics-d-2.dll、sfml-network-d-2.dll、sfml-system-d-2.dll、 sfml-window-d-2.dll)放進Debug資料夾內
6. 再次執行專案

待修正：
----------
沒有UI<br>
&nbsp;&nbsp;-遊戲會立即開始，沒有時間給玩家準備<br>
&nbsp;&nbsp;-死亡不會重來，必須重啟專案
  
平台會不自然地生成<br>
&nbsp;&nbsp;&nbsp;&nbsp;-平台可能重疊<br>
&nbsp;&nbsp;&nbsp;&nbsp;-平台有時生成會高過玩家可到達的位置，造成無法繼續遊戲

[程式碼參考](https://www.youtube.com/watch?v=7Vf_vQIUk5Q)<br>
[SFML](https://www.sfml-dev.org/)
