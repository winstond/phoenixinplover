# phoenixinplover
Quick start for using Pheonix Steno Theory in Plover

Want to use Phoenix Steno Theory in Plover Open Source Steno software?<br />Well you can!  Here are a few recommended steps to ensure you have no issues.

## Assumptions:
1. You know what Stenography is
2. You have Plover installed and working<br />
You don't? Find out what [Plover](https://www.openstenoproject.org/plover/) is and find out how to get started with plover (includes link to installation guide).
3. You have enough experience with Stenography and have decided you want to use Pheonix Theory 

## Connect with the Community on Discord
First, connect with the community in Discord!  You are sure to have a question at some point.  There is a Discord Server for Plover with a channel for Phoenix Theory users there.
Install Discord on your computer.  Then search for and join the "Plover" community.  Once you have joined, look for the "pheonix-theory" channel.

## How to use Phoenix in Plover
1. Get a starter Phoenix Dictionary from ?? (Plover supports rtf, or if you can get a Pheonix dictionary converted to native Plover json format all the better)
2. Install Plover if needed, ensure it is working
3. Install the following Add-Ins in Plover (see [Plover Plugins](https://github.com/openstenoproject/plover/wiki/Plugins) for more info)
- plover-phoenix-stenotype
- plover-number-format
- plover-retro-text-transform
4. Configure your Plover to use "Phoenix Stenotype" system (In Plover, select Configure, go to the "System" tab, then select "Phoenix Stenotype".  The default was "English Stenotype")
5. Add your base Phoenix Dictionary to the dictionaries list
6. Disable the default Plover and Plover Command dictionaries
7. Download the [phoenix_fix dictionary](https://github.com/Volensia/volensia_steno_repo/blob/main/phoenix_fix.json) to your computer and add this dictionary to plover.
(If you are using Chrome, to download select the "Raw" button, then right click on the page and select "download". It should download a file named "phoenix_fix.json".  Put this with your other dictionaries, then add it to Plover)
8. Move the "phoenix_fix" dictionary **above** your Phoenix dictionary.

With a working Plover, and having followed the above steps, you should be able to use Phoenix without issue.  Specialty strokes defined in Phoenix for punctuation and retro formatting should work as well.  You may come across the occassional issue.  Jump in to the Discord and ask if you have an issue.

## A few quick explanations in case you are interested.
1. **Phoenix Stenotype**: Why are we changing Plover from "English Stenotype" to "Phoenix Stenotype".
Many Phoenix users have found that the orthography rules in the default engine cause errors for some Phoenix translations.  The "Phoenix Stenotype" resolves the majority of these issues.  You may occassionally find a rare word that doesn't translate quite as it should.  If so, add a full definition for the word to your personal dictionary to fix it, but those should be rare!
2. **AddIns**: What are the "plover-retro-text-transform" and "plover-number-format" add-in for?
Phoenix has some strokes that automatically format what you just stroked as currency, a phone number, a social security number, etc.  There are other strokes that do things like automatically format the last few words as title case.  The default Phoenix dictionary has definitions that work in CaseCAT, but not Plover.  These plugins allow for alternative strokes to work in Plover
3. **Phoenix-fix Dictionary**: What is the "phoenix-fix" dictionary for?
This dictionary (compiled by user Volensia), adds all the override definitions you need for Phoenix strokes to work as expected.  It fixes a variety of issues, for example
- Adds the strokes to convert numbers to Roman
- Adds fixes for fingerspelling
- Adds some fixes for numbers that don't work correctly using just the base Phoenix dictionary
- Adds strokes using retro-text-transfrom and number-format add ins as mentioned to make those strokes work
- Defines additional useful command strokes for plover
- Defines many punctuations strokes that don't work correctly with the Phoenix theory dictionary out of the box

## Some recommendations for learning Phoenix (using Plover or otherwise)
1. Go to the official Phoenix Theory site at [Chicorymeadow.com](https://www.chicorymeadow.com/) to find course materials.  Phoenix has outstanding course materials available for purchase from the theory maintainer.
(The [Complete Textbook Set](https://www.chicorymeadow.com/product/phoenix-theory-complete-textbook-set/) (includes books 1 and 2, plus reference book) is recommended)
2. As mentioned, connect with the Plover community on Discord and join us in the Phoenix-Theory channel!


