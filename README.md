sudo -i
apt-get install git  
ssh-copy-id "webdevs1.kateruna.holondii@gmail.com"  
cat ~/.ssh/id_rsa.pub  
git config --global user.name "webdevs1-kateruna-holondii"  
git config --global user.email "webdevs1.kateruna.holondii@gmail.com"  
git config --list  
git clone git@github.com:webdevs1-kateruna-holondii/webdev1.git  
cd webdev1  
git branch  
git status  
mkdir kateruna-holondii  
git add kateruna-holondii  
git commit -m "add new folder kateruna-holondii"  
git checkout kateruna-holondii-pr  
git add README.md  
git commit -m "add README.md"  
git push  

