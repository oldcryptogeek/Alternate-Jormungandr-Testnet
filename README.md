# Important:
- Intention: Test pre-releases in a controlled environment to prevent connecting with incompatible versions on IOHK network and also have a stable environment to learn/study.
- Remember: To avoid spamming logs of nodes of other network (invalid block0), please ensure to not re-use IP-port combination between different networks
- Also Remember: Before starting node for the first time, ensure your storage folder is empty
- Cap: Pools intending to run their stake pool have been distributed 1000000000 Test Lovelaces, would be great if we use it as a cap.
- The information below is not complete and only intended for usage between the operators using these networks.
- For helper scripts, these are either copies - or small modifications of IOHK provided helper scripts to keep them compatible with versions here.

# Cardano Node (Haskell - PBFT) Testnet details

### Genesis Hash
```
c2ac03dc61ffd10baf8d03e2b7066c0d7d4733363894e0235bde7c1806e3f83a
```

### Known Peers

```
{
  "Producers":[
     {
        "addr":"88.99.83.86",
        "port":9000,
        "valency":1
     },
     {
        "addr":"139.99.237.20",
        "port":9000,
        "valency":1
     },
     {
        "addr":"139.99.237.20",
        "port":9001,
        "valency":1
     }
  ]
}
```

# Jormungandr (Rust) Testnet details - Enabled upon request

## v0.8.14

### Trusted Peers
```
  trusted_peers:
    #rdlrt
    - address: /ip4/88.99.83.86/tcp/4007
      id: 0add359010d13fc0e9d403c822887638969276aaedccd1f4
```
