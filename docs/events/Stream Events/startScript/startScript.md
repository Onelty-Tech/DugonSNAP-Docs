# startScript


This stream event only works with the "SCRIPT" tag, it takes the first packet sent to the stream and executes it remotely on the target.


## Parameters

- startScript(string): the name of the stream where the script will be executed remotely.

## Example

```json
{
    "startScript" "main.py"
}
```