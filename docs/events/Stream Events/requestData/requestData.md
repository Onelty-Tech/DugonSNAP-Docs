# requestData

This event is used to take a packet from one stream and send it to another stream on the specified client.

## Parameters

- user(string): Client where the package will be redirected.

- streaming(string): Name of the stream from which the packet will be taken to be redirected.

- enqueue(string): Name of the stream where the requested packet will be queued.

## Example

```json
{
    "requestData" {
        "user": "Sophia",
        "streaming": "news",
        "enqueue": "MyNews"
    }
}
```