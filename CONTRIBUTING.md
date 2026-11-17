# How to contribute:

1. Before making any changes, please check if there already is an issue describing what you want to
do. If there isn't open an issue describing the change you wish to make.
This allows others to assess whether the proposed change is beneficial and if it aligns
with the project goals.

2. Once your issue is reviewed, and if it is confirmed that your change would be useful,
and no one else is currently working on it, you may proceed with a pull request (PR).

3. When you start working on an issue leave a comment under that issue it so others know who is working on it.

4. When creating your PR, please include a description that outlines exactly
what changes have been introduced. This helps others understand your contribution better.

5. After submitting your PR, kindly wait for your changes to be reviewed, we usually discuss stuff on Discord.
We appreciate your patience as we work to ensure quality and consistency in the project.

6. If you add new components or replace existing ones, please ensure you read the [wiki article about new components](https://github.com/V3lectronics/SPIRIT/wiki/Suggesting-new-parts)

7. SMD resistors, capacitors and other components that come in very small packages have to be preferably 0603 (if available) or larger. Please use Panasonic components if available, if not use Yageo,
if both are unavailable use whatever you think is reasonable. Sometimes an exception can be made the general idea is to keep the board as friendly to hand soldering and reworks as possible.

8. When adding new components in KiCad please be sure to:
- Use the update PCB from schematic tool. The schematics and PCB must be in sync at all times.
- Make sure the symbol fields are filled out. All new components should have a Value, Datasheet, MPN field with the correct information filled in. (See power schematic for examples). Exception to save time:
resistors and capacitors don't need the Datasheet field.
- Make sure that the symbol comes with the correct footprint linked with a 3D model.
- Add the symbol to the `SPIRIT-components.kicad_sym` library file.
- Add the footprint to `SPIRIT-footprints.pretty` folder.
- Add the 3D model to `SPIRIT-3D-models `folder.

9. Please use the newest major release of KiCad.

10. Don't hesitate to ask questions and ask for help. A good place to do that is `troubleshooting-and-help` forum channel on Discord.

11. Avoid massive pull requests that are hard to review. It is easier for
everyone if you split your contribution into small, atomic pieces (within reason of course). That means: each commit should represent a single change/modification.

12. Change only the files you need, e.g. if you made a change to the power schematic you probably don't have to commit changes to audio. This reduces clutter and git conflicts.

13. Write all text in English. 

14. Please make sure you understand at least the basics of how Git and pull requests work if you plan on using those for your contribution.

15. Sometimes it is useful to add images to schematics, for example screenshots of datasheets fragments like pinouts. This makes the schematic easier to review.

# Tasks to do

Here is the [issues list](https://github.com/V3lectronics/SPIRIT/issues). You can filter them using the "good first issue" label.

Ping `v_electronics` on Discord or send me an email if you want to discuss anything

Good luck and please stick to the guidelines for smooth cooperation! If you think a rule is stupid just communicate it and exceptions can be made.

# Contact

V Electronics Discord server with channels for discussing SPIRIT stuff:

>https://discord.gg/zBG4KdHJWx

Project lead maintainer email:

>jwaga76@gmail.com

