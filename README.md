Platea
======

Sample app for Droidcon India 2014, and maybe the start of something new.

I'm interested in working on using a combination of mobile and wearable tech,
plus elements of machine learning and NLP, to make the whole concept of understanding
and using foreign languages a lot more interesting, intuitive, and a load of other adjectives
that probably don't make sense.

Anyway, as of now, this app's just a small demo on using Mobile Chrome Apps for Android dev.
The idea is to showcase useful phrases for 2-3 languages - probably French, German
and Greek - as well as audio samples for those phrases, to help someone who's just
landed in, say, Paris, Berlin or Athens, to get by.

Build Instructions
===================

You're going to need the Android SDK, as well as the CCA tool. You can check out
installation instructions for those [here](https://github.com/MobileChromeApps/mobile-chrome-apps/blob/master/docs/Installation.md).
Just make sure you have the Android SDK Platform and Build Tools for Android 19, since MCA doesn't run on
anything higher than that. But fret not, the code will run just fine on newer Android builds.

Okay, so once you're set up with this, simple fork/clone this repo, and inside the repo,
run ```cca emulate android```, to test the app on an emulator. You will need an emulation device set up
using the AVD Manager; again, for further info, check [this](https://github.com/MobileChromeApps/mobile-chrome-apps/blob/master/docs/Develop.md) out.

After this, if you're feeling like [Richard the Lionheart](http://en.wikipedia.org/wiki/Richard_I_of_England),
feel free to run ```cca build android --debug```, which should give you an APK that you can load onto
your unsuspecting guinea pig of a smartphone.


Questions? Issues? Rants? Feel free to post an issue, or hit me up [here](http://rudimk.github.io/contact/).