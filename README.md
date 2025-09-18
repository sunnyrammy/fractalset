Hello guys! This is my first program that deals with my favorite topic— fractals!

This specific program deals with a specific equation that I think is personally fascinating—— z = cos(z) + ln(c)

I was originally inspired by a picture I found of a very fascinating-looking fractal. The man who made it posts those kinds of fractals pretty often on Wikimedia, but it's almost like he's disappeared. He's also made other photos like this:
![MANDEL_COS(Z)+1_C_medium](https://github.com/user-attachments/assets/cc082044-4b4a-4358-9954-ddb8c3b034f7)


 Anyway, I did some digging and found an old screenshot that had the actual equation at the bottom, the focus of this program: cos(z)+ln(c)!

Now, it's not particularly fascinating if you're not a fan of fractals. But I HAD to make a program on it somehow, since so many of the fractal imaging programs were costly or were outdated. So I got to work! I originally made this program in Java using a .,:#?! system (it was still fun, but so hard to translate into Python TT), but this is where I first learned quite a lot about this function (so much so I got scared haha). The initial photograph that the man posted showed a small image of this fractal, but it's almost underrated how complex this fractal truly is. I wasn't the one who discovered this fractal, so I guess I don't have complete rights to coin a name for it, but if I did, I would totally name it 'The Batman Fractal.'

To some extent, the shape of the fractal is so oddly reminiscent of the Batman logo.

I'm getting carried away, but I think one thing that is VERY interesting about this fractal is its self-similarity. It sounds pretty standard if you're into fractals, but I discovered something about this that I don't think anyone has ever really talked about before. The bounds for the initial render are from (-25, 25) on the real and imag axis, and if you zoom in far enough you'll see that in the center (i'll post estimated coordinates), you'll eventually a self-similar fractal within the fractal.

HOWEVER, when I zoomed OUT, i.e (-400, 400), guess what I found? Self-similarity! Which, to me, is absolutely crazy!! See, the Mandlebrot and the Julia Set both have a very small 'range' of where these fractal patterns can occur, i.e. all series diverge in the mandlebrot when z (or c) is greater than 2. Something more similar to the infinite fractal pattern in terms of range that I'm talking about is more of the equation z = sin(z) + cos(c) that goes on forever and ever (because sin and cos go on forever…), or the Burning Ship fractal that has smaller, more tinier versions of itself along the real axis.

Seeing the kind of self-similarity such as in the cos(z)+ln(c) set is something I've never seen nor heard of, though. It almost makes me wonder if bifurcation even applies in the same way as it does for the other sets.
