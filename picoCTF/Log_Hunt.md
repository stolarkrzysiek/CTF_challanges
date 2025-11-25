# Treść wyzwania
<img width="634" height="669" alt="image" src="https://github.com/user-attachments/assets/d850008c-bd38-4547-991b-ed141e1d7d9c" />

--- 

Pobrałem plik server.log zawarty w treści wyzwania. Wykorzystałem komende "cat server.log" w celu wyświetlenia zawartości pliku w konsoli.

<img width="561" height="396" alt="image" src="https://github.com/user-attachments/assets/5a8c3bcc-fd69-4329-85a6-33ba674ffef2" />

Pierwszy wiersz pliku zawierał poziom logu o nazwie "INFO FLAGPART", jako wiadomość zawierał część flagi "picoCTF{us3_". Wykorzystałem komende "cat server.log | grep -i FLAGPART" w celu wypisania wszystkich wersów z pliku server.log, które zawierają poziom logu o nazwie "INFO FLAGPART"

<img width="672" height="757" alt="image" src="https://github.com/user-attachments/assets/42e84738-85f1-4ca6-9f26-8dc7b5728309" />

Część wiadomości powielała się, natomiast po złączeniu wszystkich wiadomości pomijając powielenia, otrzymałem flagę "picoCTF{us3_y0urlinux_skills_cedfa5fb}"

<img width="693" height="63" alt="image" src="https://github.com/user-attachments/assets/f3c713a1-35cb-4694-b4c0-328156f94a61" />
