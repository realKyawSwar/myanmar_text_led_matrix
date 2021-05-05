# myanmar_text_led_matrix
scroll myanmar text on LED matrix
ဒီlink မှာ မြန်မာFont ကို binary အဖြစ်ပြောင်:
https://www.riyas.org/2013/12/online-led-matrix-font-generator-with.html

"မ" ဆိုရင် အောက်ပါအတိုင်းဖြစ်မယ်
![Capture](https://user-images.githubusercontent.com/20748792/117156490-53865180-adf0-11eb-9dd9-0e7327457c4d.PNG)

ပြီးရင် kerning ကို 6 ထားပါ။

ဥပမာ အနေနဲ့
font5x7 array ထဲမှာ အောက်ပါ binary နဲ့ kerning 6 ကို ပြောင်ပေးပါ။
"မ" အတွက်အောက်ပါအတိုင်း

B10000001,
B10000001,
B10000001,
B01000010,
B00111110,
B00100100,
B00011000,
B00000000,
6,

"ဂ်" အတွက် အောက်ပါအတိုင်း
B00111000,
B00100000,
B00111000,
B00011000,
B00100100,
B01000010,
B01000010,
B01000010,
6,
