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
