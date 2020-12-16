# ロボットシステム学　task1
  
  ## 概要
  
  　　講義内容で作成したプログラムを改造し、数字によって異なる速度で点滅するプログラムを作成した。
    
    
  ## 動作環境
   　ubuntu18.04

  
  ## 用意するもの

   ・Raspberry Pi 4
 
   ・ブレットボード
  
   ・ジャンパー線　4本
  
   ・抵抗　220Ω　1個
   
     
   ## 動画

   ・https://youtu.be/vi7FN_k27n0
 
  
   ## 実行方法


    ・git clone https://github.com/Asahi0801/task1.git
 
 
    ・cd myled
  
  
    ・sudo insmod myled.ko
  
  
    ・sudo chmod 666 /dev/myled
  
  
    ・echo 0 or 1 > /dev/myled
    
  
  


## 機能説明


   ・echo 0を入力した場合速く点滅します
  
   ・echo 1を入力した場合遅く点滅します
    
    

