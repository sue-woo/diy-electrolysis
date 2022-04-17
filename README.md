# DIY Electrolysis Hair Removal (How-to) ⚡ 🏳️‍⚧️

 This is intended to be a guide for creating a diy electrolysis machine, for hair removal, based on the idea from post **570** in [Lena's guest book.](http://lena.kiev.ua/guestbook)
 
Lena's original idea is incredibly simple and involves using a 9V battery, a spoon, and an electrolysis needle (or thin wire if necessary). Lena's post explains why this works but Wikipedia also has more information if you're interested.

This follows the same basic principles as Lena's idea but involves creating an easier to use device.

*This project requires some basic knowledge of electronics and access to some basic household tools but is fairly straightforward. This information is provided "AS IS" in the hope that others might find it useful. It is a personal project based on a collection of information I found while searching the internet but I am not an expert in electrolysis or electronics.*

## The finished project
 
![Images of finished machine](/images/finished.jpg)

It's hard to give an estimate for how much this project cost to complete as I already had many of the tools and parts that I needed. The biggest expense was the Sterex needle holder but I would definitely recommend trying to get a proper needle holder and needles if you can as it makes it a lot easier to treat hairs. 

## Things needed
 
   * 9V PPE battery.
   * 9V battery tab connector with wires.
   * **1mA** moving coil ammeter.
   * Red and black hookup-wire.
   * Positive-colour-coded (e.g. red) 4mm banana plug socket.
   * Negative-colour-coded (e.g. black) 4mm banana plug socket.
   * Crocodile/Alligator clip to 4mm banana plug test lead ~1 meter long.
   * A stainless steel electrode (Lena used a spoon but here I use a steel drinking straw).
   * Electrolysis needle holder with 4mm banana plug lead and disposable needles. Some thin solid-core wire can also be used as an improvised electrolysis needle.
   * Suitably sized project box.
   * Solding iron
   * Electrical tape/heat shrink tubing.

## Putting it all together

![Image of schematic](/images/schematic.jpg)

Please note that in the schematic the position of the positive and negative sockets are swapped around from how they are shown in the picture of the finished project. The important part is that **the needle holder _MUST_ be connected to the negative** of the battery, and **the electrode you hold MUST be connected to the positive side** of the battery.

**Connecting the needle to the positive supply will cause the metal in the needle to corrode while under your skin which can result in a tattooing effect. Only use this device with the needle connected to the negative supply!**

## The box

For the box I used a cheap wooden tea chest but you could use any box that you have or even a cardboard shoe box. To prepare the box I used a 65mm hole saw to make holes for the panel meters and a set of drill bits for the holes. 

## Panel meters

 The voltmeter must be connected in parallel across the positive and negative sides of the circuit. The ammeter must be connected in series inline between the positive side of the circuit and the positive electrode socket.

Start by connecting the positive battery wire to the positive terminal of the volt meter. Then connect the negative terminal of the volt meter back to negative battery wire.

Now connect the positive terminal of the voltmeter to the positive terminal of the ammeter, then connect the negative terminal of the ammeter to the positive electrode plug socket. Finally connect the needle holder socket to the negative to the negative terminal of the voltmeter.

The circuit is complete and current flows when the needle is inserted into the hair follicle while holding on to the positive electrode. 

![Image of inside the box](/images/inside-the-box.jpg)

![Image of simple wiring diagram](/images/wiring-diagram.jpg)

## Needle holder and needles

 For the needle holder I found a second-hand Sterex needle holder with switch on Ebay for £20. Unfortunately it can be hard to get these parts unless you buy from an online salon supply store but you can occasionally find them on eBay (for example, [Here](https://www.ebay.co.uk/itm/252222032215)).

Thankfully the needle holder I bought came with an assortment of individually wrapped sterile needles but you could also order needles online from a salon supply store.

[Sterex](https://www.sterex.com/about/needles/) or [Ballet](https://ballettechglobal.com/) needles are probably best but if you can't find a proper needle holder or proper needles then you can also use some thin solid core wire. Thinner wire is best but the wire needs enough strength to allow it to be pushed into the hair follicle without bending or breaking. 

## How it works

Galvanic electrolysis uses DC current to destroy the hair follicle. The current reacts with moisture in the follicle to produce lye which dissolves the hair follicle. The amount of lye that is produced is counted in 'Units of lye' and is determined by the amount of current used and the amount of time the current is applied for. 

## Units of Lye

A 'unit of lye' is the product of *current* (mA) multiplied by *time* (seconds). For example, 0.1mA of current for 10 seconds would produce 10 units of lye. Different types of hair require more units of lye to successfully treat. 

| Type of hair | 	E.g. |	Required units of lye (approx.) |
| ---------------- |----------------- | --------------|
| Vellus hair |	Cheek, upper lip |	15 units of lye |
| Small terminal hair |	Cheek, upper lip |	30 units of lye |
| Medium terminal hair |	Side of face, chin, arms |	45 units of lye |
| Large terminal hair |	Chin, legs, back, shoulders |	60 units of lye |
| Very large/coarse terminal hair |	Beard hair |	80 units of lye |

 To achieve the desired amount of lye, you can either use more current for less time, or less current for more time. Higher currents will feel more uncomfortable so you can use whatever works best for you and your comfort.

For example, to achieve 80 units of lye your could use 0.4mA of current for 20 seconds or 0.2mA of current for 40 seconds. Finding the right balance of current intensity and time taken per hair is mostly a personal preference. 

## Electrical safety

**Only use this device with batteries (9V or less) _DO NOT_ connect this device to a wall outlet even if you use an AC to DC adapter. Using a plug in adapter will not protect you against any voltage spikes, surges, or electrical RF noise that may pass through the adapter and into you.**

 Connecting the needle to the positive supply will cause the metal in the needle to corrode while under your skin which can result in a tattooing effect. Only use this device with the needle connected to the negative supply!

This device relies on your body's internal electrical resistance to limit the current that flows through you. While using a 9V battery, your electrical resistance must be at least 4500 ohms in order for the current to be less than the safe upper limit of 2mA.

Do not use this device around water or when your hands/body are damp as this will lower your body's electrical resistance.

Do not touch the positive electrode and the negative needle holder together while the battery is inserted. This will cause a direct short circuit.

When first using the device you should grip the electrode lightly and check the current on the dial. Gripping the electrode tighter will increase the current flow.

You should disconnect from the device immediately if the current flow exceeds 1mA.

Do not use this device if you have metal plates or pins, diabetes, are pregnant, or have any other medical condition that may be exacerbated by electrical current. 

## Effects of current on the body

This device is intended to be used with a 9V battery at less than 1mA of current. If the current exceeds 1mA then you should disconnect from the device. For safety's sake I have considered 2mA of current to be the upper safe limit. 

You can use Ohm's law (R=V/I) to calculate the lowest safe body resistance. 

`R = 9V / 0.002A `

`R = 4500 ohms `

So for the current to be less than 2mA your body's resistance should be at least 4500 ohms. 

`For 1mA:`

`R = 9V / 0.001A`

`R = 9000 ohms. `

 So for the current to be less than 1mA your body's resistance should be at least 9000 ohms.

The panel meter that I am using has an internal coil resistance of 1500 Ω ±10%. 

| BODILY EFFECT |	DIRECT CURRENT (DC)  |
| --------------- | ------------- |
| Slight sensation felt at hand(s) |	0.6 mA |
| Threshold of perception |	3.5 mA |
| Painful, but voluntary muscle control maintained |	41 mA |
| Painful, unable to let go of wires |	51 mA |
| Severe pain, difficulty breathing |	60 mA |
| Possible heart fibrillation after 3 seconds |	500 mA |

*This table adapted from Lessons In Electric Circuits, Volume I - DC*

## How to use

 To find a comfortable current I start by inserting the needle into a hair follicle and then *gently* gripping the positive electrode until the current needle starts to move. You can adjust the amount of current that flows by adjusting how much contact you make with the electrode. Personally I aim for around 0.2mA of current so adjust my grip until the current dial reads 0.2mA. It's important that you use a light grip to begin with so that you can gradually increase the current in a controlled manner.

Once I have found a current that I am comfortable with I calculate the units of lye I need to treat the hair. I would then count the seconds needed to treat the hair with the required units of lye. I will then check the hair by pulling on it gently with tweezers.

Once fully treated, it should be possible to gently pull the hair out with tweezers. It should not feel like you are 'plucking' the hairs. If the hair tugs on the skin when being pulled then the follicle has not be fully destroyed and you should add more current until it comes out without much force. 

## Resources

[Lessons In Electric Circuits, Volume I - DC (PDF)](https://ibiblio.org/kuphaldt/electricCircuits/DC/DC.pdf)

[SX-B Epilator Manual (PDF)](https://all-guidesbox.com/manual/734279/sterex-sx-b-epilator-18.html)

[Ballet needle videos](https://ballettechglobal.com/ballet-video/)

[Choose the Needle Size to Match or Exceed the Diameter of the Hair Being Treated](https://synopticproducts.com/2018/05/17/needle-size-and-electrolysis/)

[Electrology Now on YouTube](https://www.youtube.com/channel/UCAxzAWBSrxvWhgLeL4nhS_w)

[FAQ: Galvanic Electrolysis ](https://auroraelectrolysis.com/galvanic-electrolysis/)

[I built an electrolysis epilator (r/TransDIY)](https://www.reddit.com/r/TransDIY/comments/k8oxzu/i_built_an_electrolysis_epilator_round_two/)
