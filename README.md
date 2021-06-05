# masep

* environment
  * cleanroom
  * safety
    * safety goggles
    * HF / ammonium bifluoride
      * calcium gluconate gel hard to obtain for individuals, but seems to work mainly on skin surface and not be
        absorbed. Calcium gluconate powder on a wet towel should therefore be better than no antidote at all.
      * (internet search) neoprene gloves are chemically resistant against HF but easy to damage mechanically.
        Far from ideal since HF would easily leak through any crack.
      * (internet search) nitrile gloves are a bit less chemically resistant against HF but mechanically more durable.
        This seems to be the way to go.
      * No information yet on ideal glove thickness. Obviously thicker is more resistant and more durable, but also
        makes it harder to handle objects and therefore increases both the probability of accidentally dropping stuff
        and increases distraction and facilitates errors.
  * disposal
    * NaOH: neutralize with vinegar
    * HF: neutralize with limestone or hydrated lime (easy to get for construction). Watch out for splashes.
      DO NOT neutralize with soda as NaF is toxic.
    * silicon-contaminated solutions? Most should be harmless, but check each one individually.
  * cooperation
    * makerspaces
* steps
  * photography
    * coating
      * photoresist: Kontakt 20
      * soft-bake: depends on accuracy and ramping of the oven. Kontakt 20 is picky about being baked too hot.
        * my oven: lowest setting (70°C), put the wafer inside, turn on for 5 min, turn off and keep the wafer inside
          for another 5 min. Wafer should sit on the plate inserted in the middle rail.
    * developing
      * PP holds NaOH, i.e. use a PP container with a lid both for storage and developing
      * use outer container to contain splashes
  * etching
    * Armour Etch should work, but unknown if it contains an abrasive (would scratch lower layers)
    * PP is described to hold HF (try)
  * oxide growth
    * hot furnace (900-1200°C) needed for acceptable grow time
    * wet oxidation is faster, but may produce low-quality surface or even conductive surface
    * wet oxidation is not hot enough to split water, but the water/silicon reaction does
    * self-ignition temperature of hydrogen is ca. 550°C, but furnace walls and other factors may prevent self-ignition,
      so hydrogen might accumulate up to explosive concentrations
    * oxide thickness
      * be careful not to confuse nm and Å
      * native oxide: 10-20 Å
      * gate oxide: 150-500 Å
      * mask oxide: 2000-5000 Å
      * field oxide: 3000-10000
  * doping
    * boron nitride disc close to the wafer is reported to diffuse boron atoms into the wafer at furnace temperatures
  * spin coating
    * PP tin glued on top of a PC case fan / CPU fan. Stick the die into the center of the tin using double-sided
      sticky tape. Spin up, then spray the photoresist.
      * Fan pins must not be reversed
  * (cleaning jeweils Teil dieser schritte, kein separater Schritt, da Schritt-abhängig)
* processes
  * MaSeP-1m
    * keine Photographie
      * Versuch, ob Edding die Ätzpaste abkann
      * falls nein, Photoresist und darauf mit Edding malen
  * MaSeP-100u
  
