# IBC information

```
SUCCESS Channel {
    ordering: Unordered,
    a_side: ChannelSide {
        chain: BaseChainHandle {
            chain_id: ChainId {
                id: "osmo-test-5",
                version: 5,
            },
        runtime_sender: Sender { .. },
        },
        client_id: ClientId(
            "07-tendermint-2300",
        ),
        connection_id: ConnectionId(
            "connection-2172",
        ),
        port_id: PortId(
            "transfer",
        ),
        channel_id: Some(
            ChannelId(
                "channel-5861",
            ),
        ),
        version: None,
    },
    b_side: ChannelSide {
        chain: BaseChainHandle {
            chain_id: ChainId {
                id: "shielded-expedition.88f17d1d14",
                version: 0,
            },
            runtime_sender: Sender { .. },
        },
        client_id: ClientId(
            "07-tendermint-1236",
        ),
        connection_id: ConnectionId(
            "connection-530",
        ),
        port_id: PortId(
            "transfer",
        ),
        channel_id: Some(
            ChannelId(
            "channel-350",
            ),
        ),
        version: None,
    },
    connection_delay: 0ns,
}
```
