Raft Decomposition

Leader Election
1. Select one server to act as leader, randomly
2. Pick a new leader if old crashes.

Log replication
1. Leader accepts commands from clients, appends them to its logs
2. Leader replicates it logs to other servers.

Safety
1. Keep log consistent
2. Only server with up to date logs can become leader.






