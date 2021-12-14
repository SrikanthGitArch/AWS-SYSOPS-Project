
installation of  Mattermost application 
Switch as super user 
wget https://storage.googleapis.com/skl-training/aws-codelabs/mattermost/mattermost_install.sh 
chmod 700 mattermost_install.sh 
sudo ./mattermost_install.sh  10.0.0.46
sudo chown -R mattermost:mattermost /opt/mattermost 
sudo chmod -R g+w /opt/mattermost 
cd /opt/mattermost 	
sudo -u mattermost ./bin/mattermost	