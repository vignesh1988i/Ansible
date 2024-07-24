<h3>mq_obj_bkup.yml:</h3>

This is to take MQ Object Backup on from the Queue Manager.

This takes the backup and save one copy on Managed node (Where the Qmgr runs) & one copy on the Ansible Node (Where Ansible Playbook runs).

This also take care of the retention of the old backup files and deletes files that are 4 weeks old (Default Behaviour).

The ID running this playbook should either be "mqm" or a ID part of "mqm" group & the id should have access to login to the MQ hosts via SSH.

The roles path can be updated based on your firm based Data working directory path.

Please go thru the playbook and make necessary changes to the configurations accordingly.
