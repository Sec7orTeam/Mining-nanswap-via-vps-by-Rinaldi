1. edit config.json, pada bagian user isi alamat atau address xno kalian, lalu save
{
    "autosave": true,
    "cpu": true,
    "opencl": false,
    "cuda": false,
    "pools": [
        {
            "coin": null,
            "algo": "rx/0",
            "url": "xmrig.nanswap.com:3333",                                                        
            "user": "paste address XNO lu",
            "pass": "x",
            "tls": false,
            "keepalive": true,
            "nicehash": false
        }
    ]
}


2. setelah udah di edit config nya sekarang install shnya dengan code :
*bash install.sh*

tunggu sampai selesai

3. setelah sudah jalankan file 1.sh dengan code :
bash 1.sh

4. lanjut lagi edit file run.sh dan edit $address jadi alamat atau address xno kalian
 ./xmrig -o xmrig.nanswap.com:3333 -a rx -k -u $address -p x -t 64




code edit :
nano namafile

contoh :
nano config.json
nano run.sh

kalo untuk save teken CTRL+X lalu pilih Y untuk save lalu enter
