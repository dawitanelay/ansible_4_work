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