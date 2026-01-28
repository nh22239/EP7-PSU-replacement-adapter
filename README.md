# EP7 adapter

A friend of mine found a Studiomaster Trilogy 166 mixing desk at a tip sale, unfortunately it came without it's original power supply. My friend sent me the electrical diagrams for the power supply and asked me if I could build one, but that would be too much of a job, so I offered to make a MacGyver version.

## Requirements

The original power supply, called EP7, takes mains power and spits out +/-17V (900mA) and 48V (100mA) through a 5-pin 240-degree dip jack. This is somewhat awkward, but I have a solution....

<img width="1731" height="1065" alt="image" src="https://github.com/user-attachments/assets/bf8e5b11-61f2-42a1-aa7c-967da5fec144" />


## Solution

I will take two +17V DC power supplies, and one +48V power supply, and build a circuit that combines these into the dip jack that my friend's mixing desk wants.

<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/efeac844-696d-45bf-91ff-cf1d36f29c5e" />

I have included a few additional features here, namely noise reduction on each power line, an on/off switch to help avoid lobsided power, a delay on the 48V line to stop any pops from this supply, and some resistors to discharge everything when powered off.

Some of these additions may be useless, and there may be some sensible features that I have failed to put in, but at least this shouldn't break any of my friend's gear.

<img width="1515" height="861" alt="EP7 PSU replacement" src="https://github.com/user-attachments/assets/f3785d11-7206-4851-9aab-a92b0c67b26a" />

<img width="800" height="600" alt="EP7_PSU_replacement_box_2026-Jan-28_02-31-21PM-000_CustomizedView48688933475_png" src="https://github.com/user-attachments/assets/e57072b2-e359-4584-a86c-64053e667e69" />
