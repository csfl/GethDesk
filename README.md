# GethDesk

**GethDesk** - is a web based application to simplify work with Ethereum [Geth Go](https://github.com/ethereum/go-ethereum/wiki/geth) console client.

**GethDesk** makes easier to show you data about your [Geth Go](https://github.com/ethereum/go-ethereum/wiki/geth) node current 
condition, without using inconvenient console commands.

### Dashboard page
1. Blockchain current synchronization progress.
2. Enabled and Disabled "APIS".
3. To which network your node connected.(Main or Testnet and name of 
   the network.);
4. "Open" or "Not" your node to network connections.
5. Number of peers connected to your node.(default maximum is 25, if not 
   specified else.);
6. Current Ethereum protocol version.
7. Node mining status "Yes" or "Not", if yes than you get the hashrate speed. 
8. Current price per gas in ether.(Other units available also).
9. Mining default reward address.(You can change it).

![GitHub Logo](/readmeIMG/dashboard.jpg)




![GitHub Logo](/readmeIMG/accounts.jpg)
### Accounts Manager page:
1. Number of accounts your node owns.
2. Accounts addresses with current balance in ether.
3. Create new password protected accounts.
4. Import private keys and encrypt them with password.
5. Send to email or print a payment request receipt with requested amount to 
    pay.

![GitHub Logo](/readmeIMG/paymentRequest.jpg)

![GitHub Logo](/readmeIMG/mining.png)
### Mining page:
1. Mining with the required number of cores.
   
#### Keep in mind. Important!

!!! On Main network mining won't start until your blockchain is fully synchronized! (Mining will be scheduled to start automatically when blockchain fully synchronized.

!!! On Test network mining can start without blockchain being fully synchronized. (it will start and stop during blockchain synchronization.)
 
1. CPU mining status.(Mining or Not)
2. Mining hashrate speed.
3. visualized mining chart (Exist only if node mining).
4. Choose a default mining reward address.

![GitHub Logo](/readmeIMG/nodeInfo.jpg)

### Node Info page:
1.YOUR RUNNING NODE INFORMATION (Default Database Directory, Node name, Node 
  Id, Node Ip, Listen Addr, Enode.)
2.Detailed information about each peer connected to your Node: Enode, Id, 
  LocalAddress, RemoteAddress, Caps, Network Static:, Network Trusted:, 
  Inbound, Difficulty, Head, Version.

![GitHub Logo](/readmeIMG/mapofNodes.jpg)

### Map Page
View connected nodes on world map.
