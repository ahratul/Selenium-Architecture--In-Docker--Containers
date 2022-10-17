# Selenium-test-execution-on-Docker-containers

1. Understanding docker and its use in selenium test execution

2. Selenium grid setup using docker containers

3. Executing selenium tests sequentially or parallelly on docker containers.

# Docker Coomannd to check
sudo docker ps -a

# The docker-compose.yml will create three  instance in Selenium architecture
1. one for chrome browser
2. one for firefox browser
3. one for opera browser

# Scall up the instances command

sudo docker-compose up --scale firefox=number(number of instace you want ex: any number) -d




this command will crete n number of firefox broeser instances.

#Execute testing  parallel in different container

In thesing.xml file, if you want to change which browser you want to change do this way
in xml file change the brosr name like

name example('Chrome Test',Firefox Test', 'Opera test'
and the parameter change with browser which you want to run like(chrome-remot,firefox-remote,opera-remote) 


