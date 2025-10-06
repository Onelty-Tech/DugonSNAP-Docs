# Unsubscribe


This event is useful for remotely unsubscribing clients from channels on the SNAP network.


## Parameters

- channel(string): Channel from which the client will be unsubscribed.

## Example

```json
{
    "unsubscribeChannel": {
        "channel" "News"
    }
}
```

After sending this package, the target will no longer be subscribed to that channel and will therefore no longer receive updates from it.