### SANLcommands
|Export|Sided|Parameters|Description|
|---|---|---|---|
|sendMessage|Server|strMessage, playerElem, red, green, blue|Sends a message to the player's messagebox. Use 'false' for playerElem to send to all players.|
|sendClientMessage|Client|strMessage, red, green, blue [, funcFormattable]|Sends a message to the local player's messagebox. If you use %s in the strMessage, the return value of funcFormattable will show in real-time.|

### SANLsql
|Export|Sided|Parameters|Description|
|---|---|---|---|
|exec|Server|strQuery [, ...]|Executes an SQL query (without waiting for results).|
|query|Server|strQuery [, ...]|Executes an SQL query and polls results.|
