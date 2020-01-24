VAJA 1 CubeMX


2.

b) Glede na vašo razvojno ploščico in razširitveno vezje s tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to?
   - To je pin "PC0".

c) V Pinout zavihku ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica?
   - Ploščica ima samo 1 pretvornik.

d) Izbrani ADC pretvornik ima oznako s trikotnikom. Kaj to pomeni?
   - To pomeni, da ni vse čisto v redu in da je pin v nekakšnem "konfliktu" z drugim pinom.
   Kaj morate storiti, da razrešite to omejitev?
   - Izbrani pin (PC0) nastavimo na "ADC_IN0" kot analogni vhod. Neuporabljeni pini morajo biti na "Reset_state".

e) Razširite razdelek ADC. Koliko je vseh vhodnih kanalov?
   - Vseh vhodnih kanalov je 16.

f) Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin.
   Na zaslonu se vam mora ustrezno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina?
   - Poleg pina se izpiše "ADC_IN0".

h) V Configuration kliknemo ADC gumb. V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti 0-255.
   Kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti?
   Prva) - 6-bitna od 0 do 63
   Druga) - 10-bitna od 0 do 1023
   Tretja) - 12 bitna od 0 do 4095


Komentar:
 - V STM Studio je največja vrednost prikazane vrednosti 251, vse ostalo deluje normalno.

