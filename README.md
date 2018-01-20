# ansible-role-lp-vg
Ansible role to deploy vgallissot/lp-vg custom PS1 for liquidprompt

Description
-----------

Just git clone and link liquidpromptrc to accurate destination.


Role Variables
--------------

| Name  | Default  | Mandatory  | Description  |
| :---- |:--------:|:----------:|:------------ |
| lp_vg_path | `/usr/local/src/lp-vg` | yes | Path where git repo will be cloned to |
| lp_vg_lprc | `/etc/liquidpromptrc` | yes | Path to symbolic link for liquidpromptrc in repo. This path must be one that liquidprompt loads in its startup process. |


