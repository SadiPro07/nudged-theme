Currently we are considering three font varients for our Platform (Bold, Medium, Regular)

How to change font's on Mobile in two steps

step1: Make Sure Font's On Mobile Needs to remove "-" from font name e.g if font you downloaded looks like this
"Rubik-Bold.ttf" you need to rename it to "RubikBold.ttf" just remove "-" only for Mobile apps

step2: modify the name of fontFamily in the mobile/index file like so (export const BoldFont = "UbuntuBold") since you download Rubik fonts so we need to rename like so (export const BoldFont = "RubikBold").

How to change the font's on web, Zoom, Chrome Extension in just one step

step1: rename the font to specific format like (Font-Bold or Font-Medium or Font-Regular) in web folder and that's it
