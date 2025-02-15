
`docker exec -it jenkins cat /var/jenkins_home/secrets/initialAdminPassword
`


sudo usermod -aG docker $(whoami)
