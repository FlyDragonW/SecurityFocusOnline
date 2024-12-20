# SecurityFocusOnline_Dec
- 本課程屬於初階的入門課程
- 課程主要內容在簡報，這個 Repo 主要是放指令和程式碼方便複製  

▲ 直播線上課程(Google Meet)連結：https://meet.google.com/kbh-kyub-oct

▲ 課程簽到(表單開啟時間8:00)：  
12/22(日) 簽到：https://forms.gle/bcCootTCESMrqiet6  
12/29(日) 簽到：https://forms.gle/8zptcDJxsn6XJbk47  

▲ Writeup 繳交表單：https://forms.gle/svQYUHdtsmrELyY16  
開放繳交時間：2024年12月22日（日）00:00 至 12月30日（一）23:59

▲ 課程CTF平台： http://23.146.248.233  
開啟時間：2024年12月22日（日）08:00 至 12月30日（一）23:59

▲ 回饋問卷調查：https://forms.gle/kMZnwec3HeHz7VzCA  
開放時間：2024年12月29日（日）13:00 至 12月30日（一）23:59

## 課前準備
- 練習虛擬機使用和 Linux 基本指令
- 請加入 [Discord 群組](https://discord.gg/9G9eqSUyWA)
- 安裝所需工具或直接使用我提供的虛擬機檔案
- 會 C 語言基礎語法佳

## 證書發放標準
`<TBD>`

## 環境
虛擬機檔案載點：[分流1](https://drive.google.com/file/d/1hRD0UoNMt8flW2SJuIZf5L5QojCcTlm-/view?usp=drive_link) [分流2](https://drive.google.com/file/d/1zU_TVs8zIIAM1xKYzYwdKRVys4KDFQdv/view?usp=sharing)

[匯入虛擬機圖解](https://hackmd.io/@Flydragon/how2ovf)

本次課程需要以下工具，請在上課前自行安裝或直接使用我提供的虛擬機檔案

1. GNU
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install build-essential
```
2. Radare2
```
git clone https://github.com/radareorg/radare2
sudo ./radare2/sys/install.sh
```
3. GDB-peda
```
git clone https://github.com/scwuaptx/Pwngdb.git ; cp ~/Pwngdb/.gdbinit ~/
git clone https://github.com/scwuaptx/peda.git ~/peda ; echo "source~/peda/peda.py" >> ~/.gdbinit ; cp ~/peda/.inputrc ~/
```
4. Pwntools (with Python2)
```
sudo apt install python2
sudo apt install python-pip
python2 -m pip install --upgrade pip==20.3.4
python2 -m pip install --upgrade pwntools
```
