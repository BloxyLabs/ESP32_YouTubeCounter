# ESP32_YouTubeCounter
ESP32 YouTube counter with MAX7219
<br>
Check the instruction on how to use it on [YouTube](https://www.youtube.com/@bloxylabs "YouTube").
<br>
<br>
If you had fun with the projects, please consider buying us a [cup of coffee](https://www.buymeacoffee.com/bloxylabs "cupofcoffee").

<h3><u>What do you need</u></h3>
<p>Hardware:</p>
<p>An ESP32 Wroom development Kit (you can also use other ESP32's)<br>
A MAX7219 dot matrix module with 4 segments<br>
Five female to female jump wires (if they are not included with the MAX7219 dot matrix module)<br>
An USB-A to Micro-USB cable or on USB-A to USB-C cable (this depends of the ESP32 version)<br>
<br>
<p>Software and credentials:</p>
Arduino IDE (you can download this from www.arduino.cc)<br>
The ID of your YouTube data api (see our instruction on YouTube)<br>
The ID of your YouTube channel (https://www.youtube.com/account_advanced)<br>
Your WiFi SSID and WiFi password<br>
</p>
<h3><u>Connecting the pins</u></h3>
   <table>
<thead>
  <tr>
    <th>LED Matrix</th>
    <th>ESP32 pin</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>VCC</td>
    <td>Vin</td>
  </tr>
  <tr>
    <td>GND</td>
    <td>GND</td>
  </tr>
  <tr>
    <td>DIN</td>
    <td>23</td>
  </tr>
  <tr>
    <td>CS</td>
    <td>5</td>
  </tr>
  <tr>
    <td>CLK</td>
    <td>18</td>
  </tr>
</tbody>
</table>
<h3><u>Required libraries</u></h3>
<p>Libraries already available in ARduino IDE:<br>
MD_Parola by majicDesigns<br>
MD_MAX72XX by majicDesigns<br>
ArduinoJson by Benoit Blanchon<br>
<br>
Additional library available on this GitHub:<br>
FontSubs<br>
</p>
