# HA-dash
---

This is a simple Dashboard for home assistant running on tablet inspired from YouTuber Everything Smart Home 
 
You will need some custom cards and integrations for this to work

Custom Cards used

### [1- custom:layout-card](https://github.com/thomasloven/lovelace-layout-card)
### [2- custom:stack-in-card](https://github.com/custom-cards/stack-in-card)
### [3- custom:mini-graph-card](https://github.com/kalkih/mini-graph-card)
### [4- custom:simple-thermostat](https://github.com/nervetattoo/simple-thermostat)
### [5- custom:gap-card](https://github.com/thomasloven/lovelace-layout-card#gap-card)
### [6- custom:weather-card](https://github.com/bramkragten/weather-card)
### [7- custom:sun-card](https://github.com/AitorDB/home-assistant-sun-card)
### [8- Card Mod](https://github.com/thomasloven/lovelace-card-mod)

I have used [dark](https://community.home-assistant.io/t/clear-theme-dark/100960) theme and removed the header with the below command from card mod
```
      card-mod-theme: night #name of the theme used
      card-mod-root: |
        app-header {
          display: none;
        }
```

![alt text](https://raw.githubusercontent.com/Uaeguy/HA-dash/main/HAdash.png)


# What you need to do?
#### change all entities to your HA 
#### This is only 1 dashboard, you need to add more dashboards or views then edit the buttons card and add navigation to your dashboards
