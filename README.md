# CarX RCN

![GitHub all releases](https://img.shields.io/github/downloads/Hi-ImKyle/CarX_RCN/total)
![My Discord](https://img.shields.io/badge/Discord-KingFisher%232375-738ADB)

---

Real Car Names for CarX, [Click here for the latest releases](https://github.com/Hi-ImKyle/CarX_RCN/releases/latest)

## Which Version do I choose?
If you are using ZML and you want the latest RCN version, then the ZML version.

If you are using anything else then the BepInEx version will suffice as long as BepInEx is present of course. 

Note that the BepInEx version does not have a reload option, nor does it have `Stop Scrolling Names`.

`Stop Scrolling Names` is a basic feature that just prevents the names in the garage list view from scrolling if they are too long.

## Name Override - ZML Version

You can override/add any names provided by the mod by editing the json file at `ZML/mods/RCN/names.json`. The format is as follows.

```json
{
  "InternalCarName": "Your New Desired Name",
}
```

You can change names with the game loaded as there is a `Reload JSON` available on the ZML UI.

## Name Override - BepInEx Version

You can override any names provided by the mod by creating a file called `rcn_override.json` next to the game exe then put the following inside.

```json
{
  "Ktisune": "NSX",
  "Black Fox": "It's too loud"
}
```

Just keep in mind that if you want to add a new line, the previous line must end with a `,`. For all the car names that the game uses please see the `names.json` file inside of this repo to find the name you wish to edit.

## New Cars

Please submit a issue for any new cars and what you think/know they are.

## Shout Outs

- ZML Team
- KINO Team

## Don't redistribute any releases

Just link this GitHub page to whoever wants it.
Looking at you LiLLobby.
