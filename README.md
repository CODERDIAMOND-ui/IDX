# Import Github Repo
```https://github.com/JishnuTheGamer/vps123```
# Create VPS
``` bash <(curl -s https://vps1.jishnu.fun) ```
# Get SSHX
```curl -sSf https://sshx.io/get | sh -s run```
# Get All Files
```bash <(curl -s https://raw.githubusercontent.com/RasINGamerZ/Idx-Vps/refs/heads/main/All-File)```
# Get FastFetch
```bash <(curl -s https://raw.githubusercontent.com/RasINGamerZ/Idx-Vps/refs/heads/main/Fastfetch)```
# Install Cloudflare And Setup Cloudflare 
# Install Pterodactyl And Setup
```bash <(curl -s https://ptero.jishnu.fun)```
# Install Wings And Add to Cloudflare
 ```bash <(curl -s https://ptero.jishnu.fun)```
 # Clone This And cd 1
 ```git clone https://github.com/rasingamerzop/1.git```
 # Move To BluePrint And Install
 ```
# Run Nebula
# echo "Running nebula..."
mv nebula.blueprint /var/www/pterodactyl
blueprint -install nebula.blueprint 

# Run huxregister
# echo "Running huxregister..."
mv huxregister.blueprint /var/www/pterodactyl
blueprint -install huxregister.blueprint 

# Run loader
# echo "Running loader..."
mv loader.blueprint /var/www/pterodactyl
blueprint -install loader.blueprint 

# Run simplefavicons
# echo "Running simplefavicons..."
mv simplefavicons.blueprint /var/www/pterodactyl
blueprint -install simplefavicons.blueprint 

# Run simplefooters
# echo "Running simplefooters..."
mv simplefooters.blueprint /var/www/pterodactyl
blueprint -install simplefooters.blueprint 

# Run snowflakes
# echo "Running snowflakes..."
mv snowflakes.blueprint /var/www/pterodactyl
blueprint -install snowflakes.blueprint
```
# 24/7
```
sudo apt update && sudo apt upgrade -y

sudo apt install xfce4 xfce4-goodies xrdp -y

echo "startxfce4" > ~/.xsession
sudo chown $(whoami):$(whoami) ~/.xsession


sudo systemctl enable xrdp
sudo systemctl restart xrdp
```
# Add This Extension 
```https://addons.mozilla.org/en-US/firefox/addon/auto-refresh-page/```
