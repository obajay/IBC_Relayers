# Mainnets

## [Teritori](https://explorer.stavr.tech/teritori-main/account/tori1ga4fx4mfe3r6ay3vcruslj2mj6fv3tua20sd99) <> [Stride](https://www.mintscan.io/stride/account/stride1673f0t8p893rqyqe420mgwwz92ac4qv6synvx2)
`Our team opened the channel and keeps it alive`

```bash
chain-id: stride-1
client-id: 07-tendermint-38
connection-id: connection-26
port-id: transfer
channel-id: channel-41
"ustrd" on stride-1: ibc/197019C5C45A5E279A78F72BAAFFD5869FD5A93293245E8A45D8AFFF431C6131
strided tx ibc-transfer transfer transfer channel-41 teritoriaddress 100ustrd --from <walletName> --chain-id stride-1 -y
--
chain-id: teritori-1
client-id: 07-tendermint-30
connection-id: connection-10
port-id: transfer
channel-id: channel-9
"utori" on teritori-1: ibc/C5FFCD549BC16BC1682454D30A9225F1C51C7613910D32B58EF4E12FF03471E1
teritorid tx ibc-transfer transfer transfer channel-9 strideaddress 100utori --from <walletName> --chain-id teritori-1 -y
```

## [Osmosis](https://www.mintscan.io/osmosis/account/osmo1pxdmk2hv3qyjt3hlee7yd8nuvk49v6l52v9wpw) <> [Teritori](https://explorer.stavr.tech/teritori-main/account/tori1v9scwrt3ndarwla5juj3mxhr6njpwp4wc3enhm)
`We deployed a relayer on an existing channel`

```bash
osmosisd tx ibc-transfer transfer transfer channel-0 teritoriaddress 100"uosmo" --from <wallet> --fees 100"uosmo" --chain-id osmosis-1 -y
teritorid tx ibc-transfer transfer transfer channel-362 osmoaddress 100"utori" --from <wallet> --fees 100"utori" --chain-id teritori-1 -y
```
# Testnets
## [Hypersign](https://explorer.stavr.tech/hypersign/account/hid1vlxp0uaqyqdemc6j3gp3nqxqh25xdf0dje3phu) <> [Teritori](https://explorer.stavr.tech/teritori/account/tori1s0vm8xsshy5nekdn5uc8jresjshz4hneu7y4a0)
`Our team opened the channel and keeps it alive`
```bash
chain-id: jagrat
client-id: 07-tendermint-9
connection-id: connection-11
port-id: transfer
channel-id: channel-6
hid-noded tx ibc-transfer transfer transfer channel-6 teritoriaddress 100"uhid" --from <walletName> --chain-id jagrat -y
--
chain-id: teritori-testnet-v3
client-id: 07-tendermint-38
connection-id: connection-30
port-id: transfer
channel-id: channel-29
teritorid tx ibc-transfer transfer transfer channel-29 strideaddress 100"utori" --from <walletName> --chain-id teritori-testnet-v3 -y
```
## [Cosmos](https://explorer.stavr.tech/cosmos(gaia)/account/cosmos1jjfdy6akj0cpxm95nlqxx72cgzlzspm84jnfc3) <> [Teritori](https://explorer.stavr.tech/teritori/account/tori1kepukqgun5vm033pp089lvj67q00r87kzemj6w)
`We deployed a relayer on an existing channel`
```bash
gaiad tx ibc-transfer transfer transfer channel-701 teritoriaddress 100"uatom" --from <wallet> --chain-id=theta-testnet-001 -y
teritorid tx ibc-transfer transfer transfer channel-33 cosmosaddress 100"utori" --from <wallet> --chain-id teritori-testnet-v3 -y
uatom ibc/8D9734B53D56DC57A92E4CC788547699853F411190F6DAA70FA12B9BD062F7AE
utori ibc/B4467B4B6E4D6994977E33C4735FB884EE3BFC6D100CA7AAA484C08904A196DC 

```

