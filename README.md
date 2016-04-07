#influxdata-testcase
A Vagrantfile and ansible glue for documenting influxdata related testcases.

##Installation

Install VirtualBox, vagrant and ansible, then:

	vagrant up

##Running

	ansible-playbook testcase.yml -e test=issue-423
	ansible-playbook testcase.yml -e test=issue-331

##Restarting the docker containers

	ansible-playbook setup.yml --tags=start
