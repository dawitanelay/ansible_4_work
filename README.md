# ansible_4_work
ansbile_playbook_list 
- list of playbook to play

1 package

2 service

3 filesystem

4 user


# most used commands
- ansible all -m ping                                                     --- 4 testing 
- ansible all --list-hosts                                                --- 4 listing hosts ip 
- ansible all -m gather_facts                                             --- 4 getting facts 
- ansible all -m gather_facts --limit 52.201.235.104                      --- 4 target one host 
- ansible all -m apt -a update_cache=true                                 --- 2 run apt update on ubuntu os 
- ansible all -m apt -a name=htop                                         --- 2 install top 
- ansible-playbook --list-tags installing_package.yml                     ----2 list tags  