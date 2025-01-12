# $awaitFunc
Used to initiate an awaited command.

## Syntax
```
$awaitFunc[name;(user ID;channel ID)]
```

### Parameters

| Argument   | Description                                                         | Type     | Flag       |
|------------|---------------------------------------------------------------------|----------|------------|
| name       | The name used inside `$awaitedCommand[]` and `$awaitedCommandError[]` callbacks. | String   | Required   |
| user ID    | The user the awaited command will trigger for. Uses command author if `user ID` is not given. | Snowflake | Vacantable |
| channel ID | The channel where the command will be awaited. Uses current channel if `channel ID` is not given. | Snowflake | Optional   |


## Example
```
$nomention
What do you want me to say?
$awaitFunc[say]
```
![example](https://user-images.githubusercontent.com/113303649/212294420-acf01905-c9f5-4673-99f0-375f9d786f25.png)

> For more info, see the [Awaited Commands Guide](../guides/awaitedCommands.md).
