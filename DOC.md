# sbtool-mrmt
# documentation
last updated 2017-07-23 for version 0.1

## frontend

### usage

The tag used for search and replace, `.mrmtname.`, should be written including the periods on either side of the string. This should funtion identically in plaintext as it does in regex.

#### the base

1. Come to terms with the fact that you will never make anything remotely close to as cool as the Munari.

2. Choose a base template and copy it into your mods folder. Get ready to rename things!
  1. Rename the folder you just copied to whatever you want your mods project folder to be called!
  2. Search and replace .mrmtname. with your species name in the text files, file names, and folder names.
It is recomended that you use all lowercase alphanumeric characters and do not use spaces, hyphens, periods, or any other special characters.

3. Start your mod! All other modules included are optional.

Base module based on the [Skittles Race Mod] by [Miss Skittles]. Distributed with permission.

#### additional modules

##### npcs

1. Make a copy of 'mrmt-npcs'. It does not matter where you make it or what you call it as it is temporary.

2. Within this copy search and replace multiple different items appearing only in file text, not in any file or folder names.
  * `.mrmtname.` with the same name you chose for the base module search and replace.
  * `.mrmtgeartype.` with the name of the vanilla species whos clothing you would like to borrow.

3. Copy the contents of your copy of 'mrmt-npcs' into the folder of your mod.

##### dialog options

1. Pick a dialog style.
  * Direct will duplicate all dialog from the vanilla species you choose. your species would be refered to as a memeber of that vanilla species.
  * Rename will mimic the dialog of the species you choose replacing any references to self by species name with the species name of your choice.
  * Generic will mimic the dialog of the species you choose replacing any references to self by species name with pronouns when feasable and by the species name of your choice elsewise.
    * Generic and rename styles can be found inside the folder marked for that species.

2. Make a copy of the folder you choose. It does not matter where you make it or what you call it as it is temporary.

3. Within this copy search and replace multiple different items appearing only in file text, not in any file or folder names.
  * `.mrmtname.` with the same name you chose for the base module search and replace.
  * `.mrmttitlename.` with the name of your species written with proper capitalization, or however you want it presented.
  * `.mrmtcapname.` with the name of your species written in all caps.
  * `.mrmtdialtype.` with the name of the vanilla species whos dialog you would like to borrow.

4. Copy the contents of your copy of the dialog module into the folder of your mod.

##### object description

1. Pick an object description style.
  * Direct
    * Copy will duplicate all dialog from the vanilla species you choose. your species would be refered to as a memeber of that vanilla species.
    * Repeat will make every description the same string. Useful if you want your species to look at everything and go '...'.
  * OOC will mimic the default description for each object but with `((` and `))` on either side of it.
    * Full will use the regular description.
    * Short will use the object name.
  * Species will mimic the descriptions of the selected vanilla species. References to self are mixed, some are changed to your species name, some are unchanged leaving in the original species name. This is chosen depending on if the entity is actually refering to itself or its own species, OR looking at an object belonging to the base species.

2. Make a copy of the folder you choose. It does not matter where you make it or what you call it as it is temporary.

3. Within this copy search and replace multiple different items appearing only in file text, not in any file or folder names.
  * `.mrmtname.` with the same name you chose for the base module search and replace.
  * `.mrmttitlename.` with the name of your species written with proper capitalization, or however you want it presented.
  * `.mrmtdialtype.` with the name of the vanilla species whos dialog you would like to borrow.
  * `.descstring.` with the text you would like your species to repeat on inspecting something, only used for 'repeat' style.

4. Copy the contents of your copy of the dialog module into the folder of your mod.

Description module generated with help from [Starbound Race Description Patcher - Compiler tool] by [GTG3000].

##### extras

### the folder structure

* base templates
  * apex
  * avian
  * brew
  * floran
  * glitch
  * human
  * hylotl
  * novakid
* dialog options
  * direct
  * floranlike
    * generic
    * rename
  * glitchlike
    * generic
    * rename
* npcs
* object description options
  * direct
    * copy
    * repeat
  * floranlike
  * glitchlike
  * ooc
    * full
    * short

### licensing

Attribution is *not* required when publishing a project made with this template. It is still appreciated.

## backend

#usage

[Miss Skittles]: http://community.playstarbound.com/members/96422/

[Skittles Race Mod]: http://community.playstarbound.com/resources/956/

[GTG3000]: http://community.playstarbound.com/members/191401/

[Starbound Race Description Patcher - Compiler tool]: http://community.playstarbound.com/resources/4306/

---

@license MIT
@author IHCaTHB
