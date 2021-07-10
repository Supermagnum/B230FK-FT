# B230FK-FT
Stock ignition map for Volvo B230 FT/FK engines with  the 148 EZK ignition box.
The timing map from the 148 EZK box:
It seems that it is based on load %, so 255 Kpa is 100%.
30 Kpa is 0%.
https://github.com/Supermagnum/B230FK-FT/blob/main/B230FT_stock_ignition_map_148EZK.jpg

Translated to Megasquirt:
https://github.com/Supermagnum/B230FK-FT/blob/main/spark-B230.png

Table for import to Tunerstudio:
https://github.com/Supermagnum/B230FK-FT/blob/main/sparkTbl_B230volvo.table

Ignition sequence:
1-3-4-2
Idle rpm: 750
Ignition timing at idle: 12 BTDC
Engine capacity: 2317 CC
163 bhp)121 kW) @ 4800 rpm
264 Nm (194 lb.ft) @ 3450 rpm
Increased idle speed for emissions test : 2400 - 2600 rpm
Co at increased idle speed: 0.3 vol %
Lambda at increased idle: 0.7- 1.03
Spark plugs:
Bosch WR7DC
Engine oil grade : 5W30
Minimum octane rating : 91 RON
Compression ratio : 1:8.7
ECU ( Volvo 740 1990-1991) Jetronic LH2.4
Ignition ( Volvo 740 1990-1991) EZK 116K, EZ116K Distributor Ignition
I don't know why there are a separate ignition control box,and a ecu box.
The ecu uses a 35 pin connector,the ezk box a 25 pin connector.Most likely same pin and row distance.

Coil driver module:
Bosch 0 227 100 124
Coil dwell: 4.4mSec running.
Crank speed type : 60-2

The control unit identifies TDC as the point 90 deg after the passage of the long missing tooth.
Knock sensor : Yes, one.
Knock ignition degrees per retard step: 2-3°
Max retard: 16 degrees.
Stock max boost: 8 psi, 1.55 bar absolute aka 155kpa. (22.48 PSIG )
No electronic boost control fitted if stock.
Stock injectors: 0280150357 ( 0 280 150 357 ) rated 300 cc/min, EV1 style low impedance.
MAF sensor : 0 280 212 016

Volvo 780 Turbo + ran 196.5 KPA (1.96 Bar absolute.28.42 PSIG) from 3700 rpm and up, boost level under 3700 rpm is 1.55 bar absolute aka 155kpa ) year 1990.
188hp at 4,800 RPM and 206-lbs.ft. of torque at 3,900 RPM, Electronic boost control was fitted to these.

Since about 1990 [late '90 production; early '91 production], the B230 blocks were cast with the 'humps',these are L blocks.
Volvo incorporated a piston cooling system on the L blocks around 1993.
There are three basic ways to ID an L block:
...the timing cover decal will have an "L" on it
...the timing belt and gears are the round tooth type
...the four humps along the main oil galley.
Just because of those three "proofs", it is not for absolute certain that the motor block will actually have the squirter's inside.
Starting in model year 1993, the B230 blocks were machined and drilled for the squirters: with the NA blocks (B230F) having blocking bolts installed; and the turbo blocks (B230FT) receiving the squirters.

The only way to be absolutely sure is to take off the oil pan and its oil baffles.


wiring schematics:
http://www.volvowiringdiagrams.com/

People either add MBC's and turn up the boost (it's basically proven that as long as you run premium fuel, you can turn stock turbo redblock volvos up to about 12psi reliably) or buy an electronic boost controller. Areas with 93 can get away with more, areas with 91, less.
Note: The B230FK engine is mechanical similar to the B230FT engine, but with less boost (1.28 Bar = 128 kpa = 18.5 PSI absolute ) and a smaller turbo.

Caveats, take note:
Volvo delivered the stock engine in a slightly de-tuned form for a reason. In addition to the matter of fuel economy
there is a issue of squeezing extra power from a neglected engine. Volvo knew that as cars age many (or most) owners would not keep their cars in perfect tune and condition. 

This is absolutely essential if you are considering turning up the boost. A failing engine will rapidly self destruct at 12~15 PSI, as such it is highly recommended to complete a checkup before you even think of doing this!

Start with a compression check, to verify that your internals are solid, fix any leaks, replace worn belts and hoses and coolant pump, make sure that the cooling system is clean (flush it!) and has fresh coolant, and freshen fuel and air filters. Give it a dose of high quality fuel system cleaner and fresh plugs (suggest NHK BPR7ES for higher boost levels), and don't even think of having dirty oil in the engine.
Use synthetic oil. Also, consider a fuel pump upgrade.
It uses two fuel pumps, one feed pump in the tank and one high pressure pump located under the car.
These two pumps are a bit on the small side, and they are not rated for E85.

These engines will benefit from a Eaton M62 Supercharger, if fitted with a Inter cooler. It is possible to make a custom intake manifold with Laminova cores in.
This will require a seperate water pump,expansion tank and a separate radiator.
http://www.laminova.se/cooler-guide/intercooler/

Improving the Oil flow in B230 blocks:
http://www.pbase.com/stealthfti/lubesys
