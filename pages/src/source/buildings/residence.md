---
type: building
building: residence
layout: building
---
{% capture content %}
Citizens will go to the Residence they are assigned to at night to sleep. The Residence is also a way to get more citizens for your colony.

Each level of the Residence will house one citizen. So: 

| Building Level | Citizens Housed |
| -------------- | --------------- |
| 1              | 1               |
| 2              | 2               |
| 3              | 3               |
| 4              | 4               |
| 5              | 5               |

For additional citizens to spawn, you first have to have enough space in your Residence(s) to house your first four citizens. After you have created enough space for your initial four citizens, you have two options for your colony to grow. The first way is to have a free bed in your colony. You can also make space for a new citizen, go to the [Tavern](../../source/buildings/tavern), wait for a traveler to show up, and then give them the items they request to recruit them.

### Note: To have over 25 citizens, you must first complete the research in the [University](../../source/buildings/university).
{% endcapture %}
{% capture infobox %}
{% include infobox/building.html %}
{% endcapture %}
{% include infobox/wrapper.html content=content infobox=infobox %}

## Residence GUI

{% include contentblock/building/main-gui.html data=site.data.gui.citizen header="When accessing the Residence's hut block by right-clicking on it, you will see a GUI with different options. You start on
the main tab:" image="../../assets/images/gui/housegui.png" %}

{% include contentblock/building/other-gui.html header="You reach this screen by clicking <strong>Manage Housing</strong> on the main tab." content="If the house is filled, you will need to <strong>Unassign</strong> a citizen before being able to add new citizens.  Each citizen will be listed, starting with the residents of this residence.  Citizens will show their occupation, the distance from their work hut to <strong>this</strong> residence, and the distance from their work hut to their current residence.  If the second line is green, this residence is closer to their work hut.  If it's yellow, it's farther.  <br><br><strong>Building Assignment Mode</strong> allows you to override the Townhall's housing setting, for this residence only." image="../../assets/images/gui/housegui2.png" %}