
[English]
Thanks for purchasing my script!
This is a simple script that allows you to add markers to your FiveM server. The script was originally made for QB-Core but also works for ESX (I haven't tried it for any other frameworks).

To create a marker, you need to do the following:

Go to fgselman-marker\server\location.lua

In this file, you can add where you want your markers to be, their size, and color.

{
    pos= {x=-67.07, y= 70.48, z= 71.66}, -- Here you will put the coordinates.
    marker= 23,--which marker you want to use. You can find the markers here: can finde more here https://docs.fivem.net/docs/game-references/markers/.
    scale = 1.0, -- The scale/size of the marker. 
    rgba = {255, 60, 120, 155} -- The color of the marker.
},

I hope you enjoy this script!

------------------------------------------------------------------------------------------------------------------------------

[Svenska]

Detta är ett enkelt script som tillåter dig att skapa markörer på din server. I grund och botten är detta script gjort för QB-Core, men fungerar även för ESX (jag har inte testat det för några andra frameworks). För att skapa en markör, följ dessa steg:

Gå till fgselman-marker\server\location.lua.

Här kan du skapa markörer, ändra storlek, färg och utseende.

{
pos= {x=-67.07, y= 70.48, z= 71.66}, -- Här lägger du in koordinaterna.
marker= 23, -- Här väljer du vilket utseende markören ska ha. Du kan hitta fler alternativ här: https://docs.fivem.net/docs/game-references/markers/.
scale = 1.0, -- Storleken på markören.
rgba = {255, 60, 120, 155} -- Färgen på markören.
},

Hoppas du gillar detta script