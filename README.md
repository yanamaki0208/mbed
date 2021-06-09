**＃工業大学４年の雑な人がやっているので、お見苦しい点も多々あるかもしれませんがよろしくお願いいたします＃** 
## SPI_master_LPC1768とSPI_slave_LPC1768を使用している様子（mbedとmbed間の通信）
![PXL_20210609_154754903](https://user-images.githubusercontent.com/66021066/121388121-2b0cec80-c986-11eb-91bf-edffa2d72c10.jpg)
![PXL_20210609_154830596](https://user-images.githubusercontent.com/66021066/121387885-fac54e00-c985-11eb-91ab-01ad325b3990.jpg)  
左のmbed(master)がCOM4、右のmbed(slave)がCOM3に接続されています。  
なんとなく手を近づける前後で値が変化してることが分かるので成功です。（ややノイズが気になる）  
  
## DCmoter_calibrationを使用している様子（DCモーターの正転・逆転・PWMの増減）
![image](https://user-images.githubusercontent.com/66021066/120954193-963d9f80-c789-11eb-8378-a7ea72a6206f.png)
どの程度までPWM値が低くても負荷を動かすことができるのかというのの確認用として使ってます。  
サーボモータのキャリブレーション用のプログラムを少しいじって作りました。
