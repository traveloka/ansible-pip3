# shared/pip #

Installs python-pip

## Requirements ##

No special pre-requisites.

## Role Variables ##

	- Name: apt_cache_valid_time
	  desc: Run apt-get update if cache is older

## Dependencies ##

None.

## Example Playbook ##

    - hosts: servers
      roles:
        - role: shared/pip
          apt_cache_valid_time: 21600