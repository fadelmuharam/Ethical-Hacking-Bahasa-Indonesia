# Klasifikasi Serangan

Motif di balik serangan keamanan informasi 
* Mengganggu kelangsungan bisnis
* Melakukan pencurian informasi 
* Memanipulasi data 
* Menciptakan ketakutan dan kekacauan dengan mengganggu infrastruktur penting
* Membawa kerugian finansial ke target
* Menyebarkan keyakinan agama atau politik 
* Mencapai tujuan militer negara 
* Merusak reputasi target 
* Balas dendam 
* Meminta tebusan

Menurut IATF, serangan keamanan diklasifikasikan menjadi lima kategori: pasif, aktif, close-in, insider, dan distribution.

## Passive Attack : 
Serangan pasif melibatkan intercepting ataupun memonitoring network traffic dan data flow pada jaringan target dan tidak merusak data. Penyerang melakukan reconnaissance pada aktivitas jaringan menggunakan sniffer. Serangan ini sangat sulit dideteksi karena penyerang tidak memiliki interaksi aktif dengan sistem atau jaringan target. Serangan pasif memungkinkan penyerang untuk menangkap data atau file yang dikirim dalam jaringan tanpa persetujuan pengguna. Misalnya, penyerang dapat memperoleh informasi seperti data tidak terenkripsi saat transit, kredensial dalam bentuk plaintext, atau informasi sensitif lainnya yang berguna dalam melakukan serangan aktif.
Contoh serangan : 
* Footprinting
* Sniffing dan eavesdropping 
* Network traffic analysis 
* Decryption of weakly encrypted traffic

## Active Attack : 
Serangan aktif melakukan tamper data yang sedang dalam perjalanan atau mengganggu komunikasi atau service antar sistem untuk mem-bypass atau mengeksploitasi sistem. Terkadang mereka masuk dan  menginfeksi jaringan internal target untuk mendapatkan akses ke sistem dari jarak jauh.
Contoh serangan : 
* Denial-of-service (DoS) attack 
* Bypassing protection mechanisms 
* Malware attacks (viruses, worms, ransomware)
*  Modification of information 
* Spoofing attacks 
* Replay attacks
* Password-based attacks 
* Session hijacking
* Man-in-the-Middle attack
* DNS and ARP poisoning
* Compromised-key attack 
* Firewall and IDS attack 
* Profiling 
* Arbitrary code execution
* Privilege escalation 
* Backdoor access 
* Cryptography attacks 
* SQL injection 
* XSS attacks 
* Directory traversal attacks
* Exploitation of application and OS software

## Close-in Attack :
Dilakukan ketika penyerang berada dalam jarak fisik yang dekat dengan sistem atau jaringan target. Tujuan utama melakukan jenis serangan ini adalah untuk mengumpulkan atau mengubah informasi atau mengganggu aksesnya. Misalnya, penyerang bisa melakukan shoulder surf untuk mengintip kredensial pengguna. Contoh Serangan : Social engineering (Eavesdropping, shoulder surfing, dumpster diving)

## Insider Attack :
Serangan orang dalam dilakukan oleh orang tepercaya yang memiliki akses fisik ke aset penting target. Serangan orang dalam melibatkan penggunaan akses istimewa untuk melanggar aturan atau dengan sengaja menyebabkan ancaman terhadap informasi atau sistem informasi organisasi. Orang dalam dapat dengan mudah melewati aturan keamanan, merusak sumber daya berharga, dan mengakses informasi sensitif. Serangan ini berdampak pada operasi bisnis, reputasi, dan keuntungan organisasi. Sulit untuk mengetahui serangan orang dalam. Contoh serangan : Eavesdropping dan wiretapping , Social engineering, Pod slurping,  keyloggers, dan malware.

## Distribution Attack :
Serangan distribusi terjadi ketika penyerang mengutak-atik hardware atau software sebelum instalasi melalui backdoor yang dibuat oleh vendor hardware atau softwarenya pada saat pembuatan. Penyerang memanfaatkan backdoor ini untuk mendapatkan akses tidak sah ke informasi, sistem, atau jaringan target.