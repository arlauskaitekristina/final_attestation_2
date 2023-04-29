cat > "Домашние животные.txt"
cat > "Вьючные животные.txt"
cat "Домашние животные.txt" "Вьючные животные.txt" > "Друзья человека.txt"
cat "Друзья человека.txt"
mkdir Питомник
mv "Друзья человека.txt" /home/ubuntulinux/animals/Питомник
wget https://dev.mysql.com/get/mysql-apt-config_0.8.24-1_all.deb
sudo dpkg - i mysql-apt-config_0.8.24-1_all.deb
sudo apt-get update
sudo apt-get install mysql-server
sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
sudo dpkg -r docker-ce-cli
