# vr

To Start
http-server -S -C cert.pem

BRANCH: LOOPERS
Once you draw a worm, it keeps repeating itself.

---

Playing with creating and casting magic with hand motions. With controllers for now.

WebVR project.

Only tested on Oculus Quest 1.

Surf to this URL in your Browser in your VR device.

## Controls

Trigger: Glow trails.

A/X: Increment Color

B/Y: Prevent trail connection. Set Beat with 2 clicks.

Grip Buttons: Increments Size

## TODO

Touching trigger brings up wand.

When starting to draw - by default - do not connect. DONE.
Light comes from hand always. DONE.
tip indicates drawing always. DONE.
Tip color changes. DONE.

Way to erase scene or line.
thumbstick to change length. DONE
thunbstick to change color. DONE
Only one Beat Button. DONE
16 beats.

## WISH LIST

Networking - Dance parthy
Sharing creations - drawings with others easily

# BENDING

## LOG

Working on steering water once it is launched.

## TODO

Sommon the water back.
Start with a small water - energize it by spinning it.
Add texture /shader to water surface.

## Run Locally



https://127.0.0.1:8080/?PLAY
USB Debugging:
https://developer.oculus.com/documentation/web/browser-remote-debugging/#usb-debugging-on-oculus-quest-without-odh
https://developer.chrome.com/docs/devtools/remote-debugging/

Go to chrome://inspect#devices

Firebase:
https://console.firebase.google.com/project/vr-magic-hands/database/vr-magic-hands-default-rtdb/data

FIrebase Docs:
https://firebase.google.com/docs/database/web/read-and-write?authuser=0

---- GIT TIP

git checkout glowsticks-beat-2
git merge -s ours main
git checkout main
git merge glowsticks-beat-2

NOT WORKING
When you run it on Quest.
Then run it in Browser.
Then run it on Quest again.

TRIED

- disable write to firebase
- disabled avatar-recorder
- moved hand triggering to top of declaratrive section.
- got rid of sky and cursor listener.

Restarting app in Quest then works.

A-Frame Version: 1.2.0 (Date 2021-02-05, Commit #b220fa00)
index.js:94 THREE Version (https://github.com/supermedium/three.js): ^0.125.1
index.js:96 WebVR Polyfill Version: ^0.10.12

browser.js:111 components:raycaster:warn [raycaster] For performance, please define raycaster.objects when using raycaster or cursor components to whitelist which entities to intersect with. e.g., raycaster="objects: [data-raycastable]".

(index):90 My Client ID K735
(index):96 initUser K735

(index):927 START - end of code
(index):157 STARTUP!
(index):189 STARTUP Complete
(index):164 (2) [Array(399), Array(399)]
(index):185 START game loop

(index):197 fb hand:0
(index):96 initUser K263
(index):433 draw: K263 part:0
(index):197 fb hand:1
(index):96 initUser K948
(index):433 draw: K948 part:0

WORKING:

index.js:93 A-Frame Version: 1.2.0 (Date 2021-02-05, Commit #b220fa00)
index.js:94 THREE Version (https://github.com/supermedium/three.js): ^0.125.1
index.js:96 WebVR Polyfill Version: ^0.10.12

(index):90 My Client ID K919
(index):96 initUser K919

(index):927 START - end of code 2
(index):157 STARTUP!
(index):189 STARTUP Complete
browser.js:111 components:raycaster:warn [raycaster] For performance, please define raycaster.objects when using raycaster or cursor components to whitelist which entities to intersect with. e.g., raycaster="objects: [data-raycastable]".

2(index):649 button-listener - init

(index):164 (2) [Array(399), Array(399)]
(index):185 START game loop

(index):197 fb hand:0
(index):96 initUser K263
(index):433 draw: K263 part:0
(index):197 fb hand:1
(index):96 initUser K948
(index):433 draw: K948 part:0
2(index):730 thumbstickmoved
