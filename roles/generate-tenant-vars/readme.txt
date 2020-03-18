This role will be executed across all the hosts listed in $PWD/inventory/{{site}}/hosts.yml

This role will generate variables required to generate tenant config for all leaf and spine devices 

Input file for this role is:-
- $PWD/inventory/lab/group_vars/all/tenants.yaml

Output file generate by this role is:
- $PWD/host_vars/{{site}}/{{inventory_hostname}}/generated-tenant-vars.yaml

In output file following list of items will be generated:-
- INFRA_NW:  Will be used to generate config for infrastructure networks  or SRIOV networks . Each infra_nw can be created either in CRB or ERB mode
- OVERLAY_NW: will be used to generate config for IP-VPN (Contrail VN) extended to SDN-Gateway



