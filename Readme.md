Quickstart
====
Use `vagrant up` from within this directory, then `vagrant ssh`.

If you modify the Ansible playbook then use `vagrant reload --provision`.

Shut down the VM with `vagrant halt`. Use `vagrant destroy` to completely get rid of the VM if you have messed it up and want to start again.

The Vim setup needs you to do a `:PluginInstall` the first time.

Notes
====
`ssh_rc` and a couple of lines in the `tmux_conf` are required for ssh agent forwarding to work
within Tmux.
