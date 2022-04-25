## parcel-threejs-oculus-boilerplate
Boilerplate for a fast start with three.js on Oculus Quest 2 VR headset.
- only tested on Oculus Quest 2
- movement is controlled with joystick on Oculus controler
- use orbit controls to move camera on desktop or smartphone

#### GitHub Page
https://birdlaketree.github.io/parcel-threejs-oculus-boilerplate/

#### 1. How to deploy for github pages
```bash
rm -r build
npm run build
npm run deploy
```

#### 2. How to inspect in immersive mode
- Open Oculus Developer Hub (it automatically runs ADB and you can use it over WiFi)
- Use Oculus browser to run content (not tested with Firefox Reality)
- Use Chrome to debug `chrome://inspect/#devices`
