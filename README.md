# multi-ping-use-batch-file
how to many ping use batch file

Buka tutup cmd cuman buat nge-ping kadang menyebalkan, apalagi sering dilakukan. kalo mau gak repot bisa di buat multi ping pake batch file, cara ini jauh lebih mudah dari pada harus ngetik satu2 :D

silahkan buka notepad trus copas aja list dibawah ini, jangan lupa simpan dengan extension bat file (contoh: multi-ping.bat) silahkan ganti alamat domain atau ip sesuai keperluan.

start "Ping PC SERVER 192.168.1.3" ping 192.168.1.3 -t <br>
start "Ping MODEM 192.168.7.1" ping 192.168.7.1 -t <br>
start "Ping Mikrotik 192.168.1.1" ping 192.168.1.1  -t <br>
start "Ping ACCECC POINT" Ping 192.168.80.1 -t <br>
start "Ping OPENDNS 208.67.222.222" ping 208.67.222.222 -t <br>
start "Ping OPENDNS 208.67.220.220" ping 208.67.220.220 -t <br>
start "Ping INTERNASIONAL" ping amazon.com -t <br>
start "Ping LOCAL INDONESIA" ping detik.com -t
