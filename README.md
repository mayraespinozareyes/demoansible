# demoansible

ansible
ansible-lint
ansible-galaxy collection install ibm.cloudcollection
*ansible-galaxy collection install ansible.utils


ROKS
------------------------------

Supported parameters include: 
**cos_instance_crn, (resource_instance_id) 
crk, 
disable_public_service_endpoint, 
entitlement, 
*flavor, 
force_delete_storage, 
host_pool_id, 
*ibmcloud_api_key, 
id, 
image_security_enforcement, 
kms_account_id, 
kms_config, 
kms_instance_id, 
kube_version, 
*name, 
operating_system, 
patch_version, 
pod_subnet, 
resource_group_id, 
retry_patch_version, 
secondary_storage, 
service_subnet, 
state, 
tags, 
taints, 
update_all_workers, 
*vpc_id, 
wait_for_worker_update, 
wait_till, 
worker_count, 
worker_labels, 
*zones


COS
---------------------------

Supported parameters include: 
iaas_classic_api_key,
iaas_classic_username, 
*ibmcloud_api_key, 
id, 
*location (Required for new resource), 
*name (Required for new resource), 
parameters, 
parameters_json, 
*plan (Required for new resource), 
region, 
resource_group_id, 
service (Required for new resource), 
service_endpoints, 
state, 
tags

VPC
--------------------------

Supported parameters include: 
access_tags, 
address_prefix_management, 
classic_access, 
default_network_acl_name, 
default_routing_table_name, 
default_security_group_name, 
generation, 
ibmcloud_api_key, 
id, 
name, 
region, 
resource_group, 
state, 
tags

SubNet
----------------------------

Supported parameters include: 
access_tags, 
generation, 
ibmcloud_api_key, 
id, 
ip_version, 
ipv4_cidr_block, 
name, 
network_acl, 
public_gateway, 
region, 
resource_group, 
routing_table, 
state, 
tags, 
total_ipv4_address_count, 
*vpc, 
*zone

Resource Group
-------------------------
Supported parameters include: 
ibmcloud_api_key



Volumen
-------------------------

Supported parameters include: 
access_tags, 
capacity, 
delete_all_snapshots, 
encryption_key, 
generation, 
ibmcloud_api_key, 
id, 
iops, 
name, 
profile, 
region, 
resource_group, 
source_snapshot, 
state, 
tags, 
zone


Attach
----------------------------

Supported parameters include: 
cluster, 
ibmcloud_api_key, 
id, 
resource_group_id, 
state, 
volume, 
worker


Worker Pool
-----------------

Supported parameters include: 
cluster, 
crk, 
entitlement, 
flavor, 
host_pool_id, 
ibmcloud_api_key, 
id, kms_account_id, 
kms_instance_id, 
labels, 
operating_system, 
resource_group_id, 
secondary_storage, 
state, 
taints, 
vpc_id, 
worker_count, 
worker_pool_name, 
zones.

