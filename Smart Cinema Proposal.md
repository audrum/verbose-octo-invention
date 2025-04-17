# Smart Cinema Proposal

### Core system

We are going to use Home Assistant as the main controller for the whole automation.

#### Assets Required

- [Home Assistant Yellow](https://www.seeedstudio.com/Home-Assistant-Yellow-Kit-with-Power-Supply-p-5674.html)
 
---

### Audiovisual

- Re-use the AppleTV and BOSE sound system already implemented
	- AppleTV -> BOSE -> Projector
- Install an IR blaster for replacing existing remotes
- Align projector image within screen
- Send an HDMI cable directly from the BOSE controller to the projector, or replace existing extender box for a better one

#### Assets required

- [Broadlink RM4 Pro IR Blaster](https://amzn.eu/d/3wfjRQJ)
- **Optional:** [HDMI Cable 2.1+ (Length we need to check distance from BOSE controller to projector)](https://amzn.eu/d/dXrNUUm)

---

### Lighting

- Replace the 8 in-wall LED strips, 3 meters each one
- Get a new LED strip for under sofas light
- Check how the ceiling starlight is configured and improve it
- Create Zones:
	- Ceiling star light
	- Spot lights
	- Cove lights
	- Wall LED strips by pairs
	- Under sofa

#### Assets required

- 10 Units (8 for walls + 2 for sofas) [Nanoleaf Matter Essentials Lightstrip (5 meters)](https://amzn.eu/d/16pbWF5) (It can be trimmed but no extended)

---

### AC
Get an AC consultant and check the current status of the existing AC unit in order to know if it uses:

- Dry Contact terminals (Usually labeled ON/OFF, COM, etc.)
- Thermostat terminal blocks (R, Y, G, W, C, etc.)

**Note:** This can be checked on the AC board

#### What to do?

- If option 1: AC Has Dry Contact Terminals (ON/OFF Control), use: Shelly 1 or Shelly 1PM
	- It’ll control:
		- ON/OFF reliably
		- Limited control over temp/fan/mode unless mapped to other relays
- If  option 2: AC Supports 24V or Standard Thermostat Wiring, use: Moes Wi-Fi Smart Thermostat Module
	- It’ll control:
		- Full HVAC behavior (cool, heat, fan, auto)
		- Works with voice control, dashboards, scenes in Home Assistant

---

###  Controlling automation

The user will be able to control everything from:
- In-wall display
- Dedicated tablet 
- Personal phone
- Voice control

#### Assets required

- [Shelly Wall Display](https://amzn.eu/d/gjyRadA)
- [iPad Air](https://www.apple.com/ae/shop/buy-ipad/ipad-air)

---

### Additional assets 

- Aqara Cube T1 Pro for triggering automations
- [Presence sensor](https://apolloautomation.com/products/msr-2)
- TVOC sensor for checking in-cinema air quality

---

### Shopping list summary


| CATEGORY | DEVICE | QUANTITY |
| --- | --- | --- |
| Core System | Home Assistant Yellow | 1 |
| Audiovisual | Broadlink RM4 Pro IR BLASTER | 1 |
| | HDMI 2.1 ~10 meters | 1 |
| Lighting | Nanoleaf Matter Essential Lightstrips (5 meters each) | 10 |
| AC | MOES Wi-Fi Smart Thermostat | 1 |
| Control | Shelly Wall Display | 1 |
| | iPad Air or iPad Mini | 1 |
| Additional | Aqara Cube T1 | 1 |
| | Presence sensor | 1 |
| | TVOC Sensor | 1 |



