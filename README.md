sudo apt update  
sudo apt install -y openssh-server curl  
sudo systemctl enable --now ssh  
sudo systemctl status ssh  

curl -fsSL https://tailscale.com/install.sh | sh  
sudo tailscale up  
log in with waldo email   

tailscale ip -4  
tailscale status  
