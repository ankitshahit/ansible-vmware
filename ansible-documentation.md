## Ansible version == 2.7

#### Parameters that can be set as variables to connect
<code>VMWARE_HOST</code>
<code>VMWARE_PASSWORD </code>
<code>VMWARE_USER </code>
<code>VMWARE_VALIDATE_CERTS</code>

### vmware-playbook.yml
Supports printing information pertaining to: 
 - vmwares in vcenter
 - uuid for vm in vcenter
 - datastore for a given datacenter
 - acquire clusters from a given datacenter

### Sources

#### How to acquire facts for datastore
- https://docs.ansible.com/ansible/2.7/modules/vmware_datastore_facts_module.html

#### How to acquire facts for cluster
- https://docs.ansible.com/ansible/2.7/modules/vmware_cluster_facts_module.html

#### How to acquire vmware facts
 - https://docs.ansible.com/ansible/2.7/modules/vmware_vm_facts_module.html

