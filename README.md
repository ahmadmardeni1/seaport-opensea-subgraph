# Seaport Opensea Subgraph

## Smart Contract

### Address
`0x00000000006c3852cbEf3e08E8dF289169EdE581`

### Flowchart

![Seaport drawio](https://user-images.githubusercontent.com/63211822/175781585-e4b682d0-2327-4000-bd11-fd7412aa4220.svg)

### Important Links
- [GitHub repo](https://github.com/ProjectOpenSea/seaport)
- [Seaport Interface](https://docs.opensea.io/v2.0/reference/seaport-interface)
- [Data Source Template](https://thegraph.com/docs/en/developer/create-subgraph-hosted/#data-source-templates)

### Example TXs

https://etherscan.io/tx/0x9c7088bb4ed88e5040bf6231517a5179087638d293a8a3120e6a6d05fdf4de39#eventlog

event 1 OrderFulfilled
event 2 721 Approval
event 3 721 Transfer

---------------------------------------------------------------------------------------------------

https://etherscan.io/tx/0xf188d4e29af2bae81a7f469c0a2fa0e1c0f8bc2a59b6138f234dda08e37ad903#eventlog

event 1 ERC20 Transfer
event 2 721 Transfer
event 3 ERC20 Transfer (marketplace fee)
event 4 ERC20 Transfer (collection royalty)
event 5 OrderFulfilled

---------------------------------------------------------------------------------------------------
