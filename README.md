# Ansible-docs
Important
Parallelism is important when executing playbooks against many hosts. In a cluster environment, all hosts might become temporarily unavailable when using Ansible's default behavior of running one task on all hosts before proceeding to the next task. To avoid this, use the serial keyword in the playbook to run hosts in batches through the entire play

