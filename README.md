# datadog-nfs-vagrant
This will create an Ubuntu vagrant with an nfs synced directory (see
https://www.vagrantup.com/docs/synced-folders/nfs.html).

## Running
- Execute `DD_API_KEY=$DD_API_KEY vagrant up` from the command line, where
  `$DD_API_KEY` is either an environment variable or your actual API key.
- You can ssh into the box via `vagrant ssh`
- You can verify the Datadog agent is running and reporting via:
  `sudo /etc/init.d/datadog-agent info`
