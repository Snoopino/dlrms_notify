# Fivem Notification Script
Using for (Client-Side) :

```lua
TriggerEvent('dlrms_notify', 'type', 'Type_your_message_here', duration)
```

Using for (Server-Side) :

```lua
TriggerClientEvent('dlrms_notify', source, 'type', 'Type_your_message_here', duration)
```

# If no duration is given, will default to 3000ms

### Notification types
* Information - 'info'
* Error - 'error'
* Success - 'success'
* Warning - 'warn'

### Original
![Image of Notification](https://cdn.discordapp.com/attachments/850181379778150420/854773290257350686/Screenshot_34.png)

### Custom
![Image of Notification](https://cdn.discordapp.com/attachments/850181379778150420/854773606319259708/Screenshot_35.png)
```css
/* Custom CSS Code*/
.dlrms-card {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px 10px 10px 39px;
    border-radius: 4px;
    transition: .4s all ease-in-out;
    position: relative;
    background: #fff;
    color: black;
}

svg {
    position: absolute;
    left: 10px;
    width: 19px;
    height: 19px;
}

.dlrms-card.success {
    border-left:3px solid var(--successColor);
    fill: var(--successColor);
}

.dlrms-card.warn {
    border-left:3px solid var(--warningColor);
    fill: var(--warningColor);
}

.dlrms-card.info {
    border-left:3px solid var(--informationColor);
    fill: var(--informationColor);
}

.dlrms-card.error {
    border-left:3px solid var(--errorColor);
    fill: var(--errorColor);
}
