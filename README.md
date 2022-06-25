# MegaUp Anti AdBlock Bypass
Bypass MegaUp's Anti AdBlock And Wait Timer

## Link
You Can Add This Script By Yourself Using This Button - [Subscribe](https://gist.githubusercontent.com/Exhigh/a454e2cd6cc055a6e2a9f7c7428cdd16/raw/MegaUp-Anti-AdBlock-Bypass.user.js)

Userscript Gist Page: https://gist.github.com/Exhigh/a454e2cd6cc055a6e2a9f7c7428cdd16

`Note`: To fix the single ad img shown in megaUp add this to your filter in Ublock Origin or any other AdBlock extension

    megaup.net##.metaRedirectWrapperBottomAds > div > a > img:style(height: 250px !important; width: 0px !important; visibility: hidden !important;)
        
This ad is allowed by Ublock to bypass the anti-adblock detection from MegaUp, but since we bypass it anyway this hack isn't necessary
## Requirements
Greasemonkey / Tampermonkey

## Acknowledgements
* https://greasyfork.org/en/scripts/391977-megaup-net-anti-adblock-nuke
