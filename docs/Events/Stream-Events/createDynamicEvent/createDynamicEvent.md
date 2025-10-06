# createDynamicEvent

This event is used to create dynamic events in streaming.

Dynamic events in streaming are scripts on disk, that upon completion, return a handback that is sent on the SNAP network.


## Parameters

- streaming(string): Streaming where it will take the script and create the dynamic event.

- path(string): path where the dynamic event script is saved.

- eventName(string): Name of the dynamic event to be invoked.

- handback(bool): The handback is a container that will be sent at the end of the dynamic event script.

## Example

```json
{
    "createDynamicEvent": {
        "streaming": "Fire",
        "path": "./api/cache/dynamic/main.py",
        "eventName": "put out fire",
        "handback": false
    }
}
```

When sending this event, the first packet sent to the stream will be used as a dynamic event as a script.

