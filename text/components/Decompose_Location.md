## ![](../../images/icons/Decompose_Location.png) Decompose Location - [[source code]](https://github.com/mostaphaRoudsari/ladybug/tree/master/src/Ladybug_Decompose%20Location.py)

![](../../images/components/Decompose_Location.png)

Use this component to separate and exctract the information in the 'location' output of the importEPW or constructLocation component. - 

#### Inputs
* ##### location [Required]
The output from the importEPW or constructLocation component.  This is essentially a list of text summarizing a location on the earth.

#### Outputs
* ##### locationName
Name of the location.
* ##### latitude
Latitude of the location.
* ##### longitude
Longitude of the location.
* ##### timeZone
Time zone of the location.
* ##### elevation
Elevation of the location.


[Check Hydra Example Files for Decompose Location](https://hydrashare.github.io/hydra/index.html?keywords=Ladybug_Decompose Location)