# Key-Value Store

A simple key-value store implementation in Rust. 

## Run

```
# In one terminal
cd server/
cargo run

# In another terminal
cd client/
cargo run
```

## Features
* Uses `async/await` to support asynchronous handling of client requests in server.
* Supports concurrent handling of multiple clients with `Tokio` tasks.

## To-Do
- [ ] Implement linearizability of operations. 
- [ ] Implement duplicate detection in server to handle client faults.
- [ ] Use replication for better availability, fault-tolerance and provide strong consistency 
- [ ] Use Raft select primary without a central controller and Raft logging for fault-tolerance. 


