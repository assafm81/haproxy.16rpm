# haproxy 1.6.9 rpm works centos 6.7

#Clone the Repo

git clone https://github.com/assafm81/haproxy.1.6.git

# Enter the local copy

cd haproxy.1.6

#install haproxy

rpm -ivh haproxy-1.6.9-1.x86_64.rpm

#Example haproxy.conf is installed > statistics page:

http://"yourhaproxysite":8081  username 'h' password 'h'
