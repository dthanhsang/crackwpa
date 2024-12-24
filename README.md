pkg update && pkg upgrade -y

pkg install root-repo -y

pip install pycryptodome

pkg install git tsu python wpa-supplicant pixiewps iw openssl -y

git clone https://github.com/dthanhsang/crackwpa.git

cd crackwpa

chmod +x dothanhsang.py

sudo python dothanhsang.py -i wlan0 -K
