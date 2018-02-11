# 1) Preamble

PizzAOSP is a custom android rom developed by alamo18, ATechnoHazard, raphielscape, JagravNaik, and rm-rfasterisk. This rom aims to be clean, optimised and unique. We thought out the typical rom’s issues and we considered the best case scenario from the user perspective. All the tweaks are thought out carefully to attain the aims of this rom.

## 2) Features:

- **Optimised Base:** 
    Everyone wants a fast phone without lags over time, don't they?
    
- **Preinstalled nano gapps:**
    Because of stability and GAPPS IS A PAIN TO DOWNLOAD AND FLASH
    
- **NO Bloat:**
    We guarantee no bloat, you have the right to choose apps that you want, in gib updater. Just think of it as a clean layer
    of chewy cheese on the pizza.
    
- **OMS**
    Because sometimes having a stock looking interface is terribly boring. Check out the free themes in gib too!
    
- **Toppings:**
    Everyone loves toppings on a pizza, don't they? Toppings are carefully thought out and handcrafted and will include only the             essential in a well organised format.
    
- **Official builds:**
    Every device has the right to be official. As long as the device does not have major issues, the maintainer can just
    provide us with the trees of the device, and update them accordingly. Builds will be done on our server(s) xD
    
- **Weeklies and Monthlies:**
    Love living on the bleeding edge side of android? Out Weeklies are just for you. Or do you prefer a much more stable 
    experience? You will be recieving update once a month with security updates and bug fixes.
    
- **Gib updater:**
    A package manager we will be integrating into the rom. You can pick what you need here, with regards to the #NoBloat                     promise. It will provide you with all the packages you need and it's all free! It is also capable of recommending uninstall of           duplicate apps (like duplicate file managers, etc).
    
- **Hibernate:**
    Hibernate by saving ram contents into a file/swap and reload it when hibernation gets over. Needs kernel support. This can help save     a ton of battery and wake speads are lightning fast too.
    
- **Maintainance:**
    There is no need for those weird booster apps. You can enable on-the-go fstrim and cache clearing in the maintainance app (enabled       by default, app is not installed by default, you have to install the package via gib updater). We also make sure your apps are           always zipaligned. This implementation might be done via a service in the maintainance app or just a simple cron job.

## 3) Dev features:
- **Dynamic vendor:** (to fetch live prebuilts fresh from the daily ci builds on my server ;-;)

- **Gesture/event blob:** To handle FP gestures, taps and front light sensor. (Hoo boi, we becoming OEM-like now, except this blob will be open :3) . We figured implementing native support for such gestures with the capable hardware could reduce power usage as compared to external ones.

## 4) Future features:
- Updates will be sent as patches.

#### Groups
- General
- System
- Navaigation
- Recents
- Lockscreen

Expanded sections list with useful features will be released soon

## 5) Excluded packages that requires gib updater to handle
