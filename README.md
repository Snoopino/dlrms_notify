# dlrms_notify
Fivem Notification Script

## Use
Using for (Client-Side) :

```lua
TriggerEvent('dlrms_notify','type','Type_your_message_here', duration)
```

Using for (Server-Side) :

```lua
TriggerClientEvent('dlrms_notify','type','Type_your_message_here', duration)
```

# If no duration is given, will default to 3000ms

### Notification types
* Information - 'info'
* Error - 'error'
* Success - 'success'
* Warning - 'warn'

![Image of Notification](https://media.discordapp.net/attachments/850181379778150420/850181476230103110/Screenshot_9.png?width=1202&height=676)
