# capture colour schemes
Various .Xresources colour schemes made from combining stuff in my Adobe capture CC library

## .Xresources explanation

My .Xresources file is loosely based off of the [Tomorrow Night Eighties .Xresources structure](https://github.com/chriskempson/tomorrow-theme/blob/master/Xdefaults/XresourceTomorrowNightEighties)

### Colour naming schemes

In the theme files you'll find something like:

```
#define t_p1c1		#AEB5BF
#define t_p1c2		#4480A6
#define t_p2c1		#979FA6
#define t_p2c2		#A7C6D9
#define t_p3c1		#F2F2F2
#define t_p3c2		#568FA6
...
```

I do this because when I make the theme file I put the colours into pairs.

So what ``t_p1c1`` stands for is
- ``type``
- ``pair: one``
- ``colour: one``

This matches up with:

```
! Pair one
*.color1:	t_p1c1
*.color9:	t_p1c2

! Pair two
*.color2:	t_p2c1
*.color10:	t_p2c2

! Pair three
*.color3:	t_p3c1
*.color11:	t_p3c2
```
in the .Xresources file.

## Preview

Creek Colours + Colours 10:

![pic.png](preview/cc-c10.png)
