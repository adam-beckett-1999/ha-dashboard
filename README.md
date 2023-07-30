# HA Dashboard
This is my adaptation of the Rounded Dashboard created by LE0N on the Home Assistant forums. The original theme & styling can be found here: https://community.home-assistant.io/t/rounded-dashboard-guide/543043. You will need to add the HACS plugin and install some custom cards in order for this to work.

I've made various tweaks to the styling to suit my preferences, and re-designed some of the cards and created my own in a way that matches the original theme.

![image info](images/dashboard-overview.gif)

## Theme Elements

### Page view buttons
The page view buttons allow switching between dashboard views, they can be resized and aligned in any way you choose. I typically leave them at the very top of the dashboard when I use them.

[YAML Code](/page-view-buttons.yaml)

![image info](images/page-view-buttons.png)

### Dashboard header
The header is the centerpiece of each dashboard view. The name, as well as the contents of the pill below can be customized.

[YAML Code](/dashboard-header.yaml)

![image info](images/dashboard-header.png)

### Air quality swiper card
The air quality swiper card contains multiple sensor cards showing info like humidity, CO2 and dust levels from an air quality sensor. The first card is a custom card showing an air quality score, this can be used with something like an Awair AQ sensor or Amazon AQM sensor. In the example, I have my awair air quality score showcased here.

[YAML Code](/air-quality-swiper.yaml)

![image info](images/air-quality-swiper.gif)

### Light slider cards
The light cards come in two forms, for a standard yellow/white light and for a full colour light.

[YAML Code](/light-card-normal.yaml)

![image info](images/light-card-normal.gif)


[YAML Code](/light-card-colour.yaml)

![image info](images/light-card-colour.gif)