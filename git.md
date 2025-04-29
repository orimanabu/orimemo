# Git memo

## git clone with a specific private key file

git -c core.sshCommand="ssh -i ~/.ssh/gpscloud_id_rsa -F /dev/null" clone git@github.com:orimanabu/orimemo.git
