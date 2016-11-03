# moat-texteffects
Cool text effects for Garry's Mod


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


## Rainbow Text
__DrawEnchantedText( speed, text, font, x, y, color, glow_color, xalign, yalign )__ <br / >
_speed_ = speed at which the transitions happen (2 is good)<br / >
_glow_color_ = the other color to transition through


## Inferno Text
__DrawFireText( intensity, text, font, x, y, color, xalign, yalign, glow, shadow )__ <br / >
_intensity_ = number between 0 and 1 (0.5 is half of the text height)<br / >
_glow_ = should the text glow?<br / >
_shadow_ = should there be a shadow between the text and the fire?
