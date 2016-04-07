#influxdata-testcase
A Vagrantfile and ansible glue for documenting influxdata related testcases.

##Installation

Install vagrant and ansible, then:

	vagrant up

##Running

	ansible-playbook issue-423.yml
	ansible-playbook issue-331.yml

##Restarting the docker containers

	ansible-playbook setup.yml --tags=start
