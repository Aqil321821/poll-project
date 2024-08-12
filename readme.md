# poll-project
 A poll app just FED .....using map

https://poll-app-simple.netlify.app/
















input[name='poll-option']: This part of the selector selects all <input> elements with a name attribute of 'poll-option'.

:checked: This pseudo-class selects the <input> element that is currently checked (for checkboxes or radio buttons).


 querySelectorAll('input, button'):
 Yeh method selected element ke andar sab <input> aur <button> elements ko select karta hai. Isme input aur button dono elements shamil hain.


 for (let [option, votes] of poll):

 Yeh loop poll object ke andar key-value pairs ko iterate karta hai.
poll: Yeh ek iterable object hona chahiye, jaise ek Map ya kisi aise structure jo [key, value] pairs ko support karta hai.
[option, votes]: Destructure kiya gaya pair jahan option key hoti hai aur votes value hoti hai.