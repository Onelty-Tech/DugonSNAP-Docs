# chainingStream 

This event iterates over all the packets, merging them into one, re-queuing the already joined packets.


## Parameters

- name(string): Name of the stream where packets will be joined.

## Example

```json
{
    "chainingStream": {
        "name": "main.py"
    }
}
```