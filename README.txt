This test is used on Firefox x64.
It'll open a browser and change a few settings in some codepen pages.
The MutationObserver contains 2 actions. One that'll add a CSS preprocessor and the other one that'll change the indentation to tabs instead of spaces.
The AnimatedMenu contains 1 action that'll change the HTML preprocessor to "Slim".

Both tests have checkpoints on the editor to act as an assertion.

MutationObserverKO should fail on the second action on the CSS preprocessor. The checkpoint was volontarily changed.