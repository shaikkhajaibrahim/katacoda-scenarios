# Chef workstation
* In this scenario we will be setting up the chef workstation 21.2.278

* Download the chef workstation
`wget https://packages.chef.io/files/stable/chef-workstation/21.2.278/ubuntu/20.04/chef-workstation_21.2.278-1_amd64.deb`{{execute}}

* Install the chef workstation `dpkg -i chef-workstation_21.2.278-1_amd64.deb`{{execute}}
* Verify the installation `chef -v`{{execute}}
* Now Move to the next step to create a cookbook using chef workstation