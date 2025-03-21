# duelingbook-dark-minimal
Duelingbook minimal / material theme built upon https://github.com/mykesXD/Duelingbook-Dark-Mode

<img width="1553" alt="preview" src="https://user-images.githubusercontent.com/37403330/212520191-90662cc7-7c04-44c9-91d4-046ab5cb5426.png">


## Install

1. Download the extension for your browser - https://stylebot.dev/

2. Go to <a href="https://duelingbook.com">DuelingBook</a> and open the extension

3. Paste the <a href="https://raw.githubusercontent.com/QuotedTF/duelingbook-dark-minimal/main/duelingbook.css">code</a> in the "Code" section

## To Do List

 * ~~End turn and Start turn buttons~~
 
 * "Declare" spark graphic
   * There is no static "spark" graphic, the svg is generated dynamically on demand with a javascript library. I'd like for this project to not use Tampermonkey (or similar), but I'm afraid that this is not going to be doable without fiddling with the js and the aforementioned library especially
 
 * ~~Field zones and decks for other formats (MR3, Speed duels)~~
 
 * ~~DUEL! arrow on title screen~~
 
 * ~~Better shuffle and reveal hand button graphics~~
 
 * ~~Extra Monster Zones counter positions~~
 
 * ~~Better phase button spacing and centering~~
 
 * ~~Fix TCG and OCG labels~~
 
 * ~~Better Rock / Paper / Scissors images~~
   * Thinking about replacing the entire card rather than just the image in the future
 
 * ~~Public chat and online users window icons~~
   * ~~Duel log window icons~~
 
 * ~~Better summoning circle graphic~~
 
 * ~~Better Yes / No / Cancel buttons~~
 
 * ~~Profile avatar frames~~
 
 * ~~Duel room icons~~
 
 * ~~Better title screen social icons~~
 
 * ~~Sword replacement graphic~~

 * ~~Deck Constructor layout fix~~
 
 * Edison field (classic, without pendulum zones)
 
 * Deck builder (DB now uses actual divs rather than a static .svg background, it's going to take a while to replicate my bg using css)
 
## EXPERIMENTAL

I'm tinkering with anime card frames. The stylesheet for those is standalone and in a separate file so you can choose whether or not to use it.  
To use it, just copy the contents of "anime_style.css" and paste them at the bottom of the stylebot editor.

![immagine](https://github.com/QuotedTF/duelingbook-dark-minimal/assets/37403330/120b3abe-ecca-4c46-b7fe-c09ad42ba5d1)

To-dos:
 * ~~Pendulum frames (DB just has the green gradient which is then overlayed over the regular card frame)~~
	* improvable
 * ~~Card names (I'd like to add them to the big text box if possible)~~ 
	* ~~Looking to improve text shadow or (better) add a soft black transparent backdrop~~
 * ~~Card types and abilities (I'd like to use icons)~~ 
	* ~~Looking to improve text shadow or (better) add a soft black transparent backdrop~~
	* No icons for the moment it looks like
 * ~~Link arrows~~
	* To be improved now that the name backdrop has been implemented and had the unintended side effect to mess these up

## Credits

 * <a href="https://github.com/mykesXD">mykesXD</a> for the initial repo and <a href="https://github.com/mykesXD/Duelingbook-Dark-Mode">project</a>

 * <a href="https://www.svgrepo.com">SVGRepo</a> for the svg icons
 
 * <a href="https://www.deviantart.com/xandrewproductions/art/The-Seal-of-Orichalcos-PNG3-For-Card-Art-763330028">XandrewProductions</a> for the Seal of Orichalcos graphic
 
 * <a href="https://www.deviantart.com/matteste">matteste</a> for the S:P Little Knight, Scareclaw Tri-Heart, Ghostrick Festival, Ukiyoe-P.U.N.K. Amazing Dragon and Starry Night, Starry Dragon Master Duel asset rip
 
 * <a href="https://ygopro.org/yugioh-card-maker/">YGOPro Card Maker</a> for the anime card layouts. Original YGOPro Card Maker credits are as follows:
 
   * Commissioned by: <a href="https://github.com/realSetoKaiba">Seto Kaiba</a>

   * Programmed by: <a href="https://github.com/LimitlessSocks">Sock#3222</a>

   * Management lead: <a href="https://github.com/SoaringSky">Soaring__Sky#3222</a>

   * Rush Duel Templates by: <a href="https://www.deviantart.com/alixsep">alixsep</a>

   * Derived from: <a href="https://github.com/Yemachu/cardmaker">Yemachu Cardmaker</a>
