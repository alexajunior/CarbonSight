

# CarbonSight 🌱
## Offline Use

The app has no runtime internet dependency. The barcode scanner uses a local copy of Quagga, while challenges and leaderboard data are stored in `localStorage`.

1. Install Node.js once, then run `npm install` in this folder.
2. Start the local server with `npm start`.
3. Open `http://localhost:8080` in Chrome or Edge and allow camera access.

Keep the local server running while scanning. Camera access is generally blocked when the page is opened directly as a `file://` URL. The first `npm install` downloads the scanner library once; after that, the app can run without internet.

## How to Use
 
1.  Go to the live demo link
 
- Access the application through the provided demo URL.
2.  Click 'Start Scanner'
 
- Tap the scan button to activate your camera.
3.  Center a retail product barcode in the scan box
 
- Point your device at any product barcode and align it within the frame.
4.  Instantly view the carbon footprint result
 
- See the environmental impact data displayed in real-time.
5.  Complete challenges to earn points
 
- Participate in sustainability challenges to boost your score.
6.  Watch your score update in leaderboard
 
- Track your progress and compete with the community.
##   Features
-   📱 AR product scanning with live carbon footprint overlay
-   ⛓️ Blockchain verification on Polygon network
-  🏆 Reward system and community leaderboard
- 💚 Store challenges for sustainability improvements
##   Tech Stack
-   React Native + ARCore/ARKit
-   Polygon blockchain + Smart Contracts
-  Node.js backend + Carbon APIs
- Real-time geolocation integration
 
## Copyright
© 2025 Alex Junior. All rights reserved. This work is the original creation of Alex Junior and is protected under copyright law.
