## Install MySQL Server on the Ubuntu operating system

​	 mysql  က open-source relational database  ျဖစ္ျပီ း open -source ျဖစ္လုိ႕ ေနရာေတာ္ေတာ္မွာ အသု့ံးျပဳပါတယ္ ၊ ခုေျပာမဲ့ အေၾကာင္းအရာ က ေတာ့ mysql  ကုိ ubuntu linux  မွာ setup or install ဘယ္လုိလုပ္မလဲ ဆုိ တာ တဆင့္ခ်င္း ရွင္းထားတာပါ ။  ဘယ္ commandline ေတြကုိ သုံးထားတယ္ဆုိတာကုိ တဆင့္ခ်င္းရွင္းျပထားပါတယ္္

 

<h1 style="font-size:30px"> Install MySQL
</h1>

အရင္ဆုံး အ ေနနဲ့  <span style="font-weight:bold"> terminal</span>  ကုိ ဖြင္ ့ျပီ းေအာက္ ျပ ထားတဲ့  ေအာက္ က ေပးထားတဲ ့ <span style="font-weight:bold"> command</span>  ကုိ ရုိက္ပါ။

``` html
	  sudo apt-get update
      apt-get install mysql-server
      
```




y/n ေမးလာခဲ ့ရင္ y ကုိ ေျဖ ေပးပါ ပီးတဲ့ အထိ ေစာင့္ေပးပါ။

ေပးထားတဲ့ command ေတြက  အရင္ဆုံး စက္ထဲ မွာ ရွိတဲ့ software ေတြ ကုိ update လုပ္ ပီး <span style="font-weight:bold"> mysql-sever</span> နဲ့ဆုိငင္တဲ ့လုိအပ္တဲ့ dependenices ကုိ  ကုိ သြင္းတာပါ။ ခုဆုိရင္ install လုပ္ျပီး ျပီ လုိ ေျပာလုိ႔ရပါတယ္ အကုန္လုံးေတာ့ မဟုတ္ ေသးဖူး ေပါ့၊ secure ျဖစ္ေအာင္ လုပ္ေပးရ ပါဦးမယ္။ ေအာက္မွာ ေပးထားတဲ့ ကုိ ဆက္ပီး ကူထည့္ပါ၊


```html
 
    sudo mysql_secure_installation utility

```


အ ေပၚမွာ ေပးထားတဲ့ ကုိ ရုိက္ ပီး ရင္utillity (setup လုပ္ဖုိ႕လုပ္ ေပးတဲ့ အရာ tools)ကုိ    secure ျဖစ္ေအာင္ လုပ္ ေပးမဲ့   <span style="font-weight:bold">root password  နဲ႔  root user </span> ကုိ configure လုပ္ ဖုိ႕ အတြက္ launch လုပ္ ေပး တာပါ၊ေနာက္  အ ေန နဲ့ 

 <span style="font-weight:bold">allow remote access </span>  ကုိ ေျပာျပ ပါမယ္ ၊၊ mysql database ကုိ တျခား machine  က ေန ထိန္းခ်ဳပ္ဖုိူအတြက္ enable လုပ္ေပးဖုိ႕လုိအပ္ပါတယ္။ ေအာက္ က ေပးတဲ့ အတုိင္း ရုိက္လုိက္ပါ၊ 

```    
     sudo ufw enable
     sudo ufw allow mysql
```


ဒါဆုိရင္  <span style="font-weight:bold">mysql installation  </span>  ျပီးဆုိသြားပါျပီ။
