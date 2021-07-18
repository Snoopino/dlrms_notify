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

### Original Style
![Image of Notification](https://cdn.discordapp.com/attachments/850181379778150420/854773290257350686/Screenshot_34.png)

### Original Style Video
https://youtu.be/gfYHG7jNzAY

### Custom Style
![Image of Notification](https://cdn.discordapp.com/attachments/850181379778150420/854773606319259708/Screenshot_35.png)

### Custom Style Video
https://youtu.be/cVbuNmIiEdU

### Style CSS
```css
/* CSS Code for Original Style */
.dlrms-card.success {
    box-shadow: 0 0 2px var(--successColor);
    background: var(--successColor);
    fill: #fff;
}

.dlrms-card.warn {
    box-shadow: 0 0 2px var(--warningColor);
    background: var(--warningColor);
    fill: #fff;
}

.dlrms-card.info {
    box-shadow: 0 0 2px var(--informationColor);
    background: var(--informationColor);
    fill: #fff;
}

.dlrms-card.error {
    box-shadow: 0 0 2px var(--errorColor);
    background: var(--errorColor);
    fill: #fff;
}
```

```css
/* CSS Code for Custom Style */
.dlrms-card.success {
  border-left: 3px solid var(--successColor);
  fill: var(--successColor);
}

.dlrms-card.warn {
  border-left: 3px solid var(--warningColor);
  fill: var(--warningColor);
}

.dlrms-card.info {
  border-left: 3px solid var(--informationColor);
  fill: var(--informationColor);
}

.dlrms-card.error {
  border-left: 3px solid var(--errorColor);
  fill: var(--errorColor);
}
