**1-qadam. Serverga kirish. Putty desktop ilovasi orqali kiriladi**

        ssh {server_name}@{ip_address} -p {post_number}
<br><br>
**example:**
<br>
- -p port odatda 22 bilan kiriladi, bazi hollarda u o'zgarib turishi mumkin.

        ssh test@129.230.90.145 -p 22

<br><br>

**2-qadam. Serverga kirilganidan so'ng nginx, psql va pip package ni o'rnatib olamiz!**

        sudo apt update
        sudo apt upgrade

        sudo apt install python3-pip python3-dev libpq-dev postgresql postgresql-contrib nginx curl
<br><br>

**3-qadam. PostgreSQL ga kirib baza shakillantirib olamiz**

        sudo -u postgres psql

**login parol bilan kiriladi** 

