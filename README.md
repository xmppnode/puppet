# Install
sudo docker build -t="xmppnode/static_web:v1" git://github.com/xmppnode/puppet.git
# Run
sudo docker run -d -p 80 --name static_web xmppnode/static_web:v1 nginx -g "daemon off;"
