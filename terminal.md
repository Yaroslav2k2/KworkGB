mkdir Animal
cd ~/Animal
cat > anihome
cat > annipack
cat anihome anipack > animals
cat animals
mv animals friend
ls -ali
cd ..
mkdir AnimalSys
cd ~/Animal
mv mans_friends ~/AnimalSys
cd ~/AnimalSys
ls -ali
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb
sudo apt-get update
sudo apt-get install mysql-server
sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
sudo dpkg -i docker-ce-cli_20.10.133-0ubuntu-jammy_amd64.deb
sudo dpkg -r docker-ce-cli
