This role will generate variable file which will be further used to generate eBGP config for leaf and spine devices 

Input files required for this role are:-

$PWD/inventory/{{site}}/group_vars/all/generated_p2p_ips.yaml
$PWD/inventory/{{site}}/group_vars/all/underlay-topology.yaml.yaml

output file for this role will be "$PWD/host_vars/{{site}}/{{inventory_hostname}}/generated-underlay-vars.yaml" 
