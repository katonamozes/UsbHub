# UsbHub

This is a basic usb hub that splits 1 usb port into 4. I made it because I was running out of usb ports on my computer and instead of buying a generic usb hub I wanted to make something that was more personal and I also enjoy just making stuff like this. I was really inspired by my hobbes and interests for the silkscreen and I also had fun making the rest of the board and the case. I also wanted to flex my knowledge a bit to my classmates ;) . I used this tutorial to make it: https://jams.hackclub.com/batch/usb-hub/part-1#Start%20a%20new%20project 

Here is the whole scematic: <img width="1259" height="855" alt="image" src="https://github.com/user-attachments/assets/868fdc5a-5e27-42ac-9716-b0167c66cffd" />

And a few  screenshots from Fusion: <img width="889" height="662" alt="image" src="https://github.com/user-attachments/assets/c094b7ed-fcac-4ad1-999f-21ddab187e68" />
<img width="804" height="588" alt="image" src="https://github.com/user-attachments/assets/f386e320-f394-4420-bdc4-749c81391540" />
<img width="641" height="462" alt="image" src="https://github.com/user-attachments/assets/3d6e0e14-7ab4-4ced-9bd3-1df44e9398de" />

Regarding the tutorial I also change some stuff like I used a different processor to add more functionality to use later if I want to like leds. 
<img width="273" height="386" alt="image" src="https://github.com/user-attachments/assets/e51c7146-e504-40ab-8a54-0fa1a4c71385" />

I also added 2 more usb ports to make it more useful.

I also added a custume silkscreen so that it is more personal.
<img width="607" height="759" alt="image" src="https://github.com/user-attachments/assets/da3a96b2-3cb9-4f69-b71d-d258359c03ae" />

BOM:
| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
| ---- | ------- | -------- | ---------------- | ---- | ----------- |
| Through hole ceramic capacitor | For capacitence | 10 | 0.51 | https://www.lcsc.com/product-detail/C123150.html?spm=wm.gwc.xh.9.cbm___wm.mly.ssl.gwc&lcsc_vid=EgJbVwUCE1FfA1MEFQBbUFJQTwAMA1FVQFEMVlVWE1ExVlNRTlJWUFxQQldXVzsOAxUeFF5JWBEPFBcWGBMaSQgFBAJABAsLWA%3D%3D | LCSC Electronics |
| Ceramic Capacitor | For capacitence | 100 | 0.15 | https://www.lcsc.com/product-detail/C1525.html?spm=wm.gwc.xh.8.cbm___wm.mly.ssl.gwc&lcsc_vid=EgJbVwUCE1FfA1MEFQBbUFJQTwAMA1FVQFEMVlVWE1ExVlNRTlJWUFxQQldXVzsOAxUeFF5JWBEPFBcWGBMaSQgFBAJABAsLWA%3D%3D | LCSC Electronics |
| Thick Film Resistor | To resist | 100 | 0.49 | https://www.lcsc.com/product-detail/C17902.html?spm=wm.gwc.xh.7.cbm___wm.mly.ssl.gwc&lcsc_vid=EgJbVwUCE1FfA1MEFQBbUFJQTwAMA1FVQFEMVlVWE1ExVlNRTlJWUFxQQldXVzsOAxUeFF5JWBEPFBcWGBMaSQgFBAJABAsLWA%3D%3D | LCSC Electronics |
| Through Hole Resistor | To resist | 100 | 0.57 | https://www.lcsc.com/product-detail/C713913.html?spm=wm.gwc.xh.6.cbm___wm.mly.ssl.gwc&lcsc_vid=EgJbVwUCE1FfA1MEFQBbUFJQTwAMA1FVQFEMVlVWE1ExVlNRTlJWUFxQQldXVzsOAxUeFF5JWBEPFBcWGBMaSQgFBAJABAsLWA%3D%3D | LCSC Electronics |
| Oscillator | For oscillating | 1 | 0.71 | https://www.lcsc.com/product-detail/C295101.html?spm=wm.gwc.xh.5.cbm___wm.mly.ssl.gwc&lcsc_vid=EgJbVwUCE1FfA1MEFQBbUFJQTwAMA1FVQFEMVlVWE1ExVlNRTlJWUFxQQldXVzsOAxUeFF5JWBEPFBcWGBMaSQgFBAJABAsLWA%3D%3D | LCSC Electronics |
| Hub USB 2.0 Interface Controllers | To control everything | 1 | 0.80 | https://www.lcsc.com/product-detail/C6776948.html?spm=wm.gwc.xh.4.cbm___wm.mly.ssl.gwc&lcsc_vid=EgJbVwUCE1FfA1MEFQBbUFJQTwAMA1FVQFEMVlVWE1ExVlNRTlJWUFxQQldXVzsOAxUeFF5JWBEPFBcWGBMaSQgFBAJABAsLWA%3D%3D | LCSC Electronics |
| Ceramic capacitor | For capacitence | 50 | 0.52 | https://www.lcsc.com/product-detail/C19702.html?spm=wm.gwc.xh.3.cbm___wm.mly.ssl.gwc&lcsc_vid=EgJbVwUCE1FfA1MEFQBbUFJQTwAMA1FVQFEMVlVWE1ExVlNRTlJWUFxQQldXVzsOAxUeFF5JWBEPFBcWGBMaSQgFBAJABAsLWA%3D%3D | LCSC Electronics |
| Diode | For diodey stuff | 10 | 1.17 | https://www.lcsc.com/product-detail/C48192.html?spm=wm.gwc.xh.2.cbm___wm.mly.ssl.gwc&lcsc_vid=EgJbVwUCE1FfA1MEFQBbUFJQTwAMA1FVQFEMVlVWE1ExVlNRTlJWUFxQQldXVzsOAxUeFF5JWBEPFBcWGBMaSQgFBAJABAsLWA%3D%3D | LCSC Electronics |
| Usb female ports | to plug stuff into the pcb | 10 | 0.46 | https://www.lcsc.com/product-detail/C46407.html?spm=wm.gwc.xh.1.cbm___wm.mly.ssl.gwc&lcsc_vid=EgJbVwUCE1FfA1MEFQBbUFJQTwAMA1FVQFEMVlVWE1ExVlNRTlJWUFxQQldXVzsOAxUeFF5JWBEPFBcWGBMaSQgFBAJABAsLWA%3D%3D | LCSC Electronics |
| Usb male port | to plug the pcb into my computer | 5 | 0.52 | https://www.lcsc.com/product-detail/C98125.html?spm=wm.gwc.xh.0.cbm___wm.mly.ssl.gwc&lcsc_vid=EgJbVwUCE1FfA1MEFQBbUFJQTwAMA1FVQFEMVlVWE1ExVlNRTlJWUFxQQldXVzsOAxUeFF5JWBEPFBcWGBMaSQgFBAJABAsLWA%3D%3D | LCSC Electronics |
| PCB | It is the circuit | 5 | 3.50 | https://jlcpcb.com/pcb-fabrication/fr4-pcb | JLCPCB  |
