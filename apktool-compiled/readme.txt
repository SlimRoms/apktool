Dear user,

we want to provide the new apktool for the TRDS/darkUI feature

Download the version you need and use it like the official one...it is working same.
(the zip contains aapt, apktool, framework-res, and a installation help)

You need to add new aapt and use the new apktool to decompile and compile
your apps you want. (HINT: aapt is much bigger then the original....thats
because the original just compiles the things in which are really needed
for apktool...we provide the complete aapt from recompiled android sdk)

About how it is working: in general you just need to add folders with the
new qualifier -inverted (or -notinverted). Eg. drawable-inverted-hdpi, or drawable-inverted-values etc etc
Important.....AOSP hast strict rules in which order qualifier are used. Please
read for that the AOSP docu. our inverted qualifier is from order directly before
the official UIMode qualifier.

Have fun and cheers

your SlimRoms Team
