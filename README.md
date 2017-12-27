# Roll20Tokens
Simple Method for making a roll20 token.  Took about 2 hours to program beginning to end, and allows for a lot of tokens to be made, provided they are of "playable" monster types.

## Steps To Use
1. Get a picture you want to manipulate.  I use  [Hero Forge](https://www.heroforge.com) which has the added benefit of allowing me to make an actual mini of my token if I ever end up playing offline.  Hint: "clear" the base, better than trying to magic wand it away.
2. Delete away layers and change the file names.  I use paint.net, and set eraser to 100% (else it leaves bits behind)
3. Set each filename to the color and the texture you want for that layer (in a list called "lst")
4. Run it!

## Example
1. Get a Picture:

![Archer Test](https://github.com/NeverForged/Roll20Tokens/blob/master/test_archer/test01.png)

2. Delete Away Parts and change filenames (see folder for all deletes/names)

![Archer Test](https://github.com/NeverForged/Roll20Tokens/blob/master/test_archer/test02.png)
![Archer Test](https://github.com/NeverForged/Roll20Tokens/blob/master/test_archer/test03.png)

3. lst = [("test01", 'f2dacd', 'skin'), ('test02','6A4E42','hair'), ... Note: Last entry does not get a comma.

4. Run it!

![Archer done](https://github.com/NeverForged/Roll20Tokens/blob/master/test_archer/test.png)

## Notes
* You need Python to run this.  I wrote this in 3, though it should work in 2.
* There is a color guide at the end of the notebook.  Darker colors end up going "over" and leave red on the image.  I could probably fix this, and may in a later version.
* This is based on a 400 by 400 pixel image, which will be the "fighting space" of your token (5 ft for standard tokens of humans, etc.)  Image is way larger than it needs to be, which is okay.  You can reduce it before you upload if worried about space.
* Note that [Hero Forge](https://www.heroforge.com) also has a prone pose, which is good if you want to show downed people.
