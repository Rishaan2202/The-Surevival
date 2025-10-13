# Day 2! Progress!!!
So I did the USB Type-C power input connection today for my ESP. I took help from the 'Custom Devboard' guide and the ESP32 datasheet for this, but I can't figure out where to connect the D+ and D- pins! but don't worry, I'll do something for them! Take a  look at the Schematic now:-
<br>
<br>
<img width="443" height="489" alt="Screenshot 2025-10-10 230450" src="https://github.com/user-attachments/assets/8b96ff99-7b46-460a-ba37-17d747164271" />
<br>
<h2>Time Invested: 1 Hour</h2>


# Day 3! Even more progress!!!
Yeah! You see the schematic, it doesn't look like a day 3 schematic but yeah, it is! So today I tried to search for the Load sensors, but couldn't find any SMD one, so I will think upon it. I also tried to figure out that D+ and D- pin thingy, but couldn't come to any conclusion. So I asked for it on #electronics. I hope to get some answers on that. The major thing done today is the connection for BME280 sensor!!! Yeah, it's a great achievement for me!:-
<br>
<br>
<img width="485" height="360" alt="image" src="https://github.com/user-attachments/assets/9307e809-955a-479b-8f72-1a01d4d11f8d" />
<br>
<h2>Time Invested: 1.75 Hour</h2>


# Day 4! Done with the USB-to-UART thing!!!
I did it! One of my friend (Teammate in another proect) told me that I had to use the USB to UART feature for cthe transmission of Data between the MCU and the coding Device via the Type-C port. After this, my D+ and D- problem came to an end, and I used the CP2102 USB-to-UART converter for this (As my friend suggested this). I also kinda engulfed some stuff inside those boxes for my schematic to look more systematic and organised (and yeah, cooler!). Look at the schematic now:-
<br>
<br>
<img width="782" height="671" alt="image" src="https://github.com/user-attachments/assets/a826398f-7655-4df7-a6cd-6a742e65eda4" />
<br>
<h2>Time Invested: 1.15 Hour</h2>
