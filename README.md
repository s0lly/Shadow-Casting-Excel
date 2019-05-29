Shadow Casting in Excel

ReadMe

This excel file allows you to gain an intuitive understanding of how 2D shadow casting (without raycasting) works in the basic setting of an excel workbook.
This model uses line equations to determine which pixels lie / don't lie in the lightsource's area of visibility, rather than using stepped rays cast out from the lightsource position.
I hope this is of help for those trying to learn the basics of shadow casting!


Instructions:

First, you need to go to the sheet named "ShadowCasting"

To control the lightsource yourself, you can manually adjust the lightsource x and y positions, or…

… you can use the arrow keys, but to do so you need to first press the "START" button:
This macro assigns new functionality to the following keys
 - "w, a, s, d": press this to move the lightsource in various directions
 - "esc": press this to end the simulation and reset all key functionality
NOTE: this macro overrides these key's normal functionality - you must press ESC or press the END button at the end to reenable these keys in excel to their original functionality

Alternatively, you can press the "ANIMATE" button which will move the lightsource along a predetermined path.

PLEASE NOTE: The formulae "break down" on pure vertical / horizontal line calculations. This can be fixed by using more complicated formulae but I decided to not include these for ease of formula readability.
To avoid this issue, simple add a very small additional value on to any round number (e.g. instead of using an x position of 4, use 4.001).

by s0lly
https://www.youtube.com/c/s0lly
https://www.instagram.com/s0lly.gaming/
https://twitter.com/s0lly

THE MODEL IS PROVIDED WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE MODEL OR THE USE OR OTHER DEALINGS IN THE MODEL.
