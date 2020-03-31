This role will be executed across all the hosts listed in $PWD/inventory/{{site}}/hosts.yml

This role will generate following config:-

- Infra network:- any network which is required to enable communication between 2 phyiscal servers via underlay fabic is called infra network

- An infra network can be deployed in pure layer 2 mode or l2+l3 mode

- An infra network can  be deployed in ERB mode or in CRB mode

- Infra network in ERB mode will be typical used to server to server communication 

- If an infra network is cofnigured in CRB mode which is for SRIOV workflows then it can have north bound connection with eBGP session towards north

- An infra network l3 interface can be cofnigured in inet.0 or inside a VRF




- Ovelay network are virtual networks extended from Contrail to the SDN-gateway 

- An overlay network can have north bound connection with eBGP session towards north

- Route leaking can happen between 2 overlay network , between 2 Infra network (CRB model) or between an overlay network and between an infra network

- QoS re-write rules can be applied on north bound tagged/ sub interfaces 

 
