Find error in standart logs
---
grep "$(date —date='5 min ago' '+%b %_d %H:%M')" /var/log/syslog | grep -i "error"  
🔹 Заменить 5 на нужное количество минут.   
🔹 Работает для логов, где стандартный формат даты (%b %_d %H:%M), например /var/log/syslog, /var/log/auth.log.  
🔹 Ключ -i делает поиск нечувствительным к регистру.  
