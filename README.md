   # Link On/Off/Briteness State of Multiple Light Entities v1.0.0
   Select multiple entities to link their on/off/brightness state.  If any selected entity is turned on or off or changed brightness, the other selected entities will be sent a matching on/off command and brightness.
    You can select any light entity, but only entities supported by the `light.turn_on` or `light.turn_off` service calls will work.
    ## Requirements
    * All selected entities MUST suport `light.turn_on` and `light.turn_off` or errors will be logged and the blueprint will not work.
    * Requires Home Assistant 2022.5.0 or newer.

   ![badge](https://my.home-assistant.io/badges/blueprint_import.svg)
   (https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fwroadd%2Fhome-assistant-blueprints%2Fmain%2Fmain%2Fha_sync_dimmers.yaml)
      
