<h1 align="center"> Mainnets </h1>

## [Teritori](https://explorer.stavr.tech/teritori-main/account/tori1ga4fx4mfe3r6ay3vcruslj2mj6fv3tua20sd99) <> [Stride](https://www.mintscan.io/stride/account/stride1673f0t8p893rqyqe420mgwwz92ac4qv6synvx2)🟢
`Our team opened the channel and keeps it alive`

```python
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

## [Osmosis](https://ping.pub/osmosis/account/osmo1at8e9mfuztffnc5mryehpl8yr5uewcggenffdu) <> [Juno](https://explorer.stavr.tech/juno/account/juno1grhaqx02dg8ahwz9ca08d6lnun9hmaeajmx0sz) <> [Cosmos](https://ping.pub/cosmos/account/cosmos1ksnuupxn5pjc6h0e5t4g0nfuxqadxzyf2ypmd9)🟢
`We deployed a relayer on an existing channel`

```python
osmosisd tx ibc-transfer transfer transfer channel-42 junoaddress 100"uosmo" --from <wallet> --fees 100"uosmo" --chain-id osmosis-1 -y
junod tx ibc-transfer transfer transfer channel-0 osmoaddress 100"ujuno" --from <wallet> --fees 5000"ujuno" --chain-id juno-1 -y
junod tx ibc-transfer transfer transfer channel-1 cosmosaddress 100"ujuno" --from <wallet> --fees 5000"ujuno" --chain-id juno-1 -y
gaiad tx ibc-transfer transfer transfer channel-207 junoaddress 100"uatom" --from <wallet> --fees 5000"uatom" --chain-id cosmoshub-4 -y
```
## [Osmosis](https://www.mintscan.io/osmosis/account/osmo1pxdmk2hv3qyjt3hlee7yd8nuvk49v6l52v9wpw) <> [Teritori](https://explorer.stavr.tech/teritori-main/account/tori1v9scwrt3ndarwla5juj3mxhr6njpwp4wc3enhm)🟢
`We deployed a relayer on an existing channel`

```python
osmosisd tx ibc-transfer transfer transfer channel-0 teritoriaddress 100"uosmo" --from <wallet> --fees 100"uosmo" --chain-id osmosis-1 -y
teritorid tx ibc-transfer transfer transfer channel-362 osmoaddress 100"utori" --from <wallet> --fees 100"utori" --chain-id teritori-1 -y
```

<h1 align="center"> Testnets </h1>

## [Hypersign](https://explorer.stavr.tech/hypersign/account/hid1vlxp0uaqyqdemc6j3gp3nqxqh25xdf0dje3phu) <> [Teritori](https://explorer.stavr.tech/teritori/account/tori1s0vm8xsshy5nekdn5uc8jresjshz4hneu7y4a0) 🔴Disabled at this stage (testing is over)
`Our team opened the channel and keeps it alive`
```python
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

## [Defund](https://explorer.stavr.tech/defund-testnet/account/defund1cd3tuh5amfe46jjs3rnpp3w8d4h394qhc7qm7n) <> [Hypersign](https://explorer.stavr.tech/hypersign/account/hid1vlxp0uaqyqdemc6j3gp3nqxqh25xdf0dje3phu) 🔴Disabled at this stage (testing is over)
`Our team opened the channel and keeps it alive`
```python
chain-id: jagrat
client-id: 07-tendermint-40
connection-id: connection-25
port-id: transfer
channel-id: channel-19
hid-noded tx ibc-transfer transfer transfer channel-19 defund1cd3tuh5a.......address "1"uhid --from wallet --chain-id=jagrat -y
--
chain-id: defund-private-4
client-id: 07-tendermint-14
connection-id: connection-9
port-id: transfer
channel-id: channel-11
defundd tx ibc-transfer transfer transfer channel-11 hid1vlxp0uaqyqdem........address "1"ufetf --from wallet --chain-id defund-private-4 -y
"ufetf"	ibc/295323E334581027CE5E55FBB085E33AED9A333F7CC446F681B12FA605311E32
"uhid"  ibc/C472CFCF4F1C39A4C97903CCB7F93B7D16A2237AEB9AA7AB9D9420EC1BB37DE1
```
## [Cosmos](https://explorer.stavr.tech/cosmos(gaia)/account/cosmos1jjfdy6akj0cpxm95nlqxx72cgzlzspm84jnfc3) <> [Teritori](https://explorer.stavr.tech/teritori/account/tori1kepukqgun5vm033pp089lvj67q00r87kzemj6w) 🔴Disabled at this stage (testing is over)
`We deployed a relayer on an existing channel`
```python
gaiad tx ibc-transfer transfer transfer channel-701 teritoriaddress 100"uatom" --from <wallet> --chain-id=theta-testnet-001 -y
teritorid tx ibc-transfer transfer transfer channel-33 cosmosaddress 100"utori" --from <wallet> --chain-id teritori-testnet-v3 -y
"uatom" ibc/8D9734B53D56DC57A92E4CC788547699853F411190F6DAA70FA12B9BD062F7AE
"utori" ibc/B4467B4B6E4D6994977E33C4735FB884EE3BFC6D100CA7AAA484C08904A196DC 

```

