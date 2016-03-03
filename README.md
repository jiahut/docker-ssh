## docker centos with ssh

1. install

	curl -sSL https://get.daocloud.io/docker | sh

2. build 

	docker build -t docker-centos-with-ssh .

3. run 

	docker run -d -p 22 docker-centos-with-ssh

4. login 

	ssh -p <port> user@localhost 
