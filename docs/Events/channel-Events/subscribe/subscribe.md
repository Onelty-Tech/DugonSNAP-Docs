# Subscribe

This event is used to remotely subscribe clients to specific channels on the SNAP network.


## Parameters

- channel(string): The name of the channel where the client will connect.

- hash(string): The channel password on the SNAP network.

## Example

```json
{
    "subscribeChannel": {
        "channel": "News",
        "hash": "09023"
    }
}
```

After sending this the target will start receiving packets from the channel.