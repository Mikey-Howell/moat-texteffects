# moat-texteffects
Cool text effects for Garry's Mod :D

##[Video of effects can be seen here](http://moatgaming.net/texteffects.mp4)
[Examples can be seen here](https://github.com/moat7/moat-texteffects/blob/master/moat_TextEffects.lua#L342-L370)<br / >
You can also type in console moat_TextEffects to see all of the effects in game :D

## Glowing Text
__DrawGlowingText( static, text, font, x, y, color, xalign, yalign )__ <br / >
_static_ = Should the glow be constant instead of fading in and out?


## Fading Colors Text
__DrawFadingText( speed, text, font, x, y, color, fading_color, xalign, yalign )__ <br / >
_speed_ = speed at which the colors fade between each other <br / >
_fading_color_ = the other color to fade to


## Rainbow Text
__DrawRainbowText( speed, text, font, x, y, xalign, yalign )__ <br / >
_speed_ = speed at which the rainbow transitions to a new color (1 - 100)


## Enchanted Text
__DrawEnchantedText( speed, text, font, x, y, color, glow_color, xalign, yalign )__ <br / >
_speed_ = speed at which the transitions happen (2 is good)<br / >
_glow_color_ = the other color to transition through


## Inferno Text
__DrawFireText( intensity, text, font, x, y, color, xalign, yalign, glow, shadow )__ <br / >
_intensity_ = number between 0 and 1 (0.5 is half of the text height)<br / >
_glow_ = should the text glow?<br / >
_shadow_ = should there be a shadow between the text and the fire?


## Electric Text
__DrawElecticText( intensity, text, font, x, y, color, xalign, yalign )__ <br / >
_intensity_ = number between 0 and 1 (higher the number = less delay)


## Bouncing/Waving Text
__DrawBouncingText( style, intesity, text, font, x, y, color, xalign, yalign )__ <br / >
_style_ = (1) bounce up (2) bounce down (3) waving<br / >
_intensity_ = intensity of the wave (1-3 is usually good)


## Sparkling/Snowing Text
__DrawSnowingText( intensity, text, font, x, y, color, sparkle_color, xalign, yalign )__ <br / >
_intensity_ = How many sparkles there should be<br / >
_sparkle_color_ = Color of the sparkles (Default white)
