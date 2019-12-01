# Important:
- Intention: Test pre-releases in a controlled environment to prevent connecting with incompatible versions on IOHK network and also have a stable environment to learn/study.
- Remember: To avoid spamming logs of nodes of other network (invalid block0), please ensure to not re-use IP-port combination between different networks
- Also Remember: Before starting node, ensure your storage folder is empty
- Cap: Pools intending to run their stake pool have been distributed 1000000000 Test Lovelaces (RC4), would be great if we use it as a cap.
- For genesis hash and faucet funds request, we expect you to know where the secret hideout is.
- For helper scripts, these are either copies - or small modifications of IOHK provided helper scripts to keep them compatible with versions here.

## v0.8.0rc2

### Trusted Peers
```
  trusted_peers:
    #rdlrt
    - address: /ip4/139.99.221.149/tcp/4002
      id: 3799c23842a0fbfa4acc29dda595dd03a14fa48cf38012ff
    #ocg
    - address: /ip4/167.71.144.137/tcp/3933
      id: 656201174b276bf1e81e0f3d0b3bc3343569f0314435564e
    #markus
    - address: /ip4/185.161.193.61/tcp/9030
      id: ada4cafebabecafebabecafebabecafebabecafebabe4ada
    #rcmorano
    #- address: /ip4/51.15.64.122/tcp/9299
    #  id: 1d93b98261d632e25412c207a665053e91fbd2bb04717512

```
