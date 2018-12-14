# ansible-hortonworks-extras
Extra utilities for ansible-hortonworks

# Add the following items in your inventory
```
[ambari-server]
<your ambari server>

[hadoop-cluster]
<all nodes in your cluster>

```

# Run the playbook
`ansible-playbook -i <inventory location> delete_hw_cluster.yml`
