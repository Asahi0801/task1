# ロボットシステム学　task1

## 機能説明


  
  
    ・0を入力した場合速く点滅します
  
  
    ・1を入力した場合遅く点滅します
  
  
  
## 用意するもの




    ・Raspberry Pi 4
 
 
    ・ブレットボード
  
  
    ・ジャンパー線　4本
  
  
    ・抵抗　220Ω　1個
  


## 実行方法




    ・git clone https://github.com/Asahi0801/task1.git
 
 
    ・cd myled
  
  
    ・sudo insmod myled.ko
  
  
    ・sudo chmod 666 /dev/myled
  
  
    ・echo 0 or 1 > /dev/myled
    
    
 ## 動画

　
      https://youtu.be/vi7FN_k27n0
