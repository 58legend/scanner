PHP-Antimalware-Scanner form https://github.com/marcocesarato/PHP-Antimalware-Scanner

Пофікшено зависання при знаходженні деяких типів вірусних файлів

Завантажити:

wget https://raw.githubusercontent.com/58legend/scanner/main/scanner --no-check-certificate

Запускається як і раніше, ніяких інших змін немає. 

Як варіант ось команда запуску, дописує в назву файлу дату перевірки:

php7.4 scanner ./ -r --path-report ./virusscan_$(date +%d-%b-%y).html 
