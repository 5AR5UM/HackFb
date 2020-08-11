# HackFb
#!/bin/bash
#Gunakan Tols ini dengan Bijak
clear
figler "Valdo Sarsum"
echo "_________________________"
echo "Author : Valdo Sarsum"
echo "Whatsap: 082195783433"
echo
echo"[ Pilih Menunya ]"
echo"[1] Dark Fb"
echo"[2] Stabilkan Jaringan"
echo"[3] Insall Bahanya Om"
echo
read -p " [ Pilih Nomor ]>>> " Pill
#Batas Gan"
if [ $pill = "1" ]
then
echo "Sedang Menginstall.... " ;sleep2
git clone https://github.com/V4N654T/dark-fb
cd dark-fb
pyton2 da.py
echo "Menginstall Selesai"
fi
#batas ga£
if [ $pill = "2"  ]
then
ping -s 900
fi
#batas gan
if [ $pill = "3" ]
then
echo "Sedang Menginstall Bahan.... " ;sleep 2
pkg update && pkg upgrade
pkg install nano
pkg install figle
pkg install git
pkg install toilet
pip2 install requests mechanize
echo "Menginstall Selesai"
fi
#batas gan
if [ $pill = "0" ]
then
echo "Makasi Om Sudah Mampir^_^"
exit
fi
