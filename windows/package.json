{
  "name": "ban-chim",
  "version": "1.0.0",
  "description": "Game ban chim dong que",
  "author": "BanChim",
  "main": "main.js",
  "scripts": {
    "dist": "electron-builder --win nsis --publish never"
  },
  "devDependencies": {
    "electron": "^31.0.0",
    "electron-builder": "^24.13.3"
  },
  "build": {
    "appId": "com.banchim.game",
    "productName": "BanChim",
    "files": ["main.js", "www/**/*"],
    "directories": { "output": "dist" },
    "win": { "target": "nsis" },
    "nsis": { "oneClick": false, "allowToChangeInstallationDirectory": true }
  }
}
