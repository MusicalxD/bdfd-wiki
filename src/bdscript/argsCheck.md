# $argsCheck
When this function is used, the command can only be executed if the user’s message contains a certain amount of arguments (words).

## Syntax
```
$argsCheck[how many?;error message]
```

### Parameters

| Argument      | Description                                                   | Type     | Flag     |
|---------------|---------------------------------------------------------------|----------|----------|
| how many?     | How many arguments there should be in the user's message.     | HowMany  | Required |
| error message | The message that the bot will send if the user has too many/little arguments. | String | Emptiable |


### Note :
   > If you want users to have 3 or more arguments in their message; you can use `>3`. If you want users to have less than 3 arguments in their message, you can use `<3`. If you want the users to have exactly 3 arguments in their message put `3`. 

## Example
```
$nomention
$argsCheck[>1;❌ Please provide something for me to say!]
$noMentionMessage
```

- With arguments
![example](https://user-images.githubusercontent.com/113303649/209973658-2e392e0e-deef-483b-98a9-5597c9bce740.png)

- Without arguments
![example](https://user-images.githubusercontent.com/113303649/209973418-97663aac-9075-48f6-b241-3feb11a730f0.png)
