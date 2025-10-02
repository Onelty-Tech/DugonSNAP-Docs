# createStream

With this event you can create streams on any client.


## Parameters

- name(string): The name of the streaming, this will be used to identify it in the future.

- type(string): The type is a tag that can be added to streams individually, depending on their functionality or purpose in the network. Depending on the type of tag you choose, you will have different predefined events that can be used at any time during streaming.

- size(int): streaming queue size, such queue is emptied when packets are collected by the client itself or remote clients on the network.

## Example

```json
{
    "createStream" {
        "name": "coordinates",
        "type": "",
        "size": 12
    }
}
```


