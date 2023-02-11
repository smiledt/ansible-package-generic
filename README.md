# Package-Generic

A role to install some basic packages on an Ubuntu server. 

## Requirements

Sudo access to the server. 

## Required variables

Required variables are listed here, along with default example values. Any of these defaults can be overwritten by using the vars role directory. 
    
    package_list:
      - cowsay
      - lolcat
      - toilet

## Dependencies

None.

## Example Playbook


    - name: Install packages
      become: true
      hosts: linux
      roles:
        - role: package-generic

### License

MIT

### Author Information

Derek Smiley - Network Analyst, avid homelabber, and aspiring Systems Administrator.
