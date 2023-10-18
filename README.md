# w4sp_LAB
原代碼問題太多，這是確認可以運行的LAB版本，可以用來練Wireshark的資安部分
+ https://github.com/w4sp-book/w4sp-lab
+ https://computerscience.unicam.it/marcantoni/reti/laboratorio_wireshark/Wireshark%20for%20Security%20Professionals%20-%20Using%20Wireshark%20and%20the%20Metasploit%20Framework.pdf

使用步驟:
+ 開啟parrot vm
+ 文件下載下來
+ 運行sudo python w4sp_webapp.py
+ 等待一段時間，開啟瀏覽器，訪問http://127.0.0.1:5000

如果跑不了，大機率是因為環境的套件問題!

VM dow:
https://drive.google.com/drive/folders/10ZXBOCia6vONENgOUX0aWss_PLYDCwYT?usp=drive_link


![image](https://github.com/Trinity-SYT-SECURITY/w4sp_LAB/assets/96654161/5f0776f8-578e-4a12-a7c9-fccd3dbc74dd)

首先註意到的是螢幕中間的網路圖。每個圓圈表示一個設備，可以是交換器（sw1、sw2）或路由器（r1、r2）、各種服務的伺服器（ftp1、ftp2、smb2等），也可以是受害機器（vic1、vic2等）在） 。

W4SP 實驗室中的網路拓撲並不固定。拓撲根據不同場景的需要而變化。當然，當我們在後面的章節中首次使用它們時，我們將更深入地了解每個場景。右側的紅色按鈕將自訂實驗室，為特定的練習和演示做好準備

SYSTEM 1 ← --------------------------------- → SYSTEM 2

Application ← specific service or application → Application

Presentation ← how the service is formatted → Presentation

Session ← rules how systems talk to one another → Session

Transport ← segment reliability, error checking → Transport

Network ← packets / datagram routing → Network

Data Link ← structure of data to/from physical → Data Link

Physical ← tangible electrical, light or RF → Physical
