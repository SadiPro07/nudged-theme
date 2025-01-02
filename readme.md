How to change font's on Mobile in two steps

step1: Make Sure Font's On Mobile Needs to remove "-" from font name e.g if font you downloaded looks like this
"Rubik-Bold.ttf" you need to rename it to "RubikBold.ttf" just remove "-" only for Mobile apps

step2: modify the name of fontFamily in the mobile/index file like so (export const BoldFont = "UbuntuBold") since you download Rubik fonts so we need to rename like so (export const BoldFont = "RubikBold").
