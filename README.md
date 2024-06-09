# ansible-ssh-and-user-control

This ansible script is used for managing admin-users and their respective ssh-keys on remote servers, while using an service on those remote machines.  

The script takes an variables-yaml for the usernames, ssh-keys and uuid. As well as another whitelist-yaml for some service users that need to be on the server like git etc.  

It updates the ssh-keys of all admin users to ensure that only the correct ssh-keys are used and for the convience of changing them only in the variable-yaml.  

The feature of deleting unused or not specified users is currently not implemented as it requires further testing.
