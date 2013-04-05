Dear user,

till our new qualifier goes the official way to apktool we will provide
our apktool.

Use it like the official one...it is working same.

You need to add new aapt and use the new apktool to decompile and compile
your apps you want. (HINT: aapt is much bigger then the original....thats
because the original just compiles the things in which are really needed
for apktool)

About how it is working: in general you just need to add folders with the
new qualifier -inverted. Eg. drawable-inverted-hdpi, or drawable-inverted-values etc etc
Important.....AOSP hast strict rules in which order qualifier are used. Please
read for that the AOSP docu. our inverted qualifier is an UIMode qualifier.

Have fun and cheers

your SlimRoms Team
