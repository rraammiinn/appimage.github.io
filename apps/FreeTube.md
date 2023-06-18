---
layout: app

permalink: /FreeTube/
description: A private YouTube client

icons:
  - FreeTube/icons/scalable/freetube.svg

screenshots:
  - FreeTube/screenshot.png

authors:
  - name: FreeTubeApp
    url: https://github.com/FreeTubeApp

links:
  - type: GitHub
    url: FreeTubeApp/FreeTube
  - type: Download
    url: https://github.com/FreeTubeApp/FreeTube/releases

desktop:
  Desktop Entry:
    Name: FreeTube
    Exec: AppRun --no-sandbox %U
    Terminal: false
    Type: Application
    Icon: freetube
    StartupWMClass: FreeTube
    X-AppImage-Version: 0.18.0
    Comment: A private YouTube client
    MimeType: x-scheme-handler/freetube
    Categories: Network
  AppImageHub:
    X-AppImage-Signature: 'keybox ''/home/runner/.gnupg/pubring.kbx'' created [don''t
      know]: invalid packet (ctb=0a) no signature found the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.'
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  version: 0.18.0
  license: AGPL-3.0-or-later
  main: "./dist/main.js"
  private: true
  author:
    name: PrestonN
    email: FreeTubeApp@protonmail.com
    url: https://github.com/FreeTubeApp/FreeTube
  repository:
    type: git
    url: git+https://github.com/FreeTubeApp/FreeTube.git
  bugs:
    url: https://github.com/FreeTubeApp/FreeTube/issues
  dependencies:
    "@fortawesome/fontawesome-svg-core": "^6.2.0"
    "@fortawesome/free-brands-svg-icons": "^6.2.0"
    "@fortawesome/free-solid-svg-icons": "^6.2.0"
    "@fortawesome/vue-fontawesome": "^2.0.8"
    "@freetube/youtube-chat": "^1.1.2"
    "@freetube/yt-comment-scraper": "^6.2.0"
    "@freetube/yt-trending-scraper": "^3.1.1"
    "@silvermine/videojs-quality-selector": "^1.2.5"
    autolinker: "^4.0.0"
    browserify: "^17.0.0"
    browserify-zlib: "^0.2.0"
    electron-context-menu: "^3.5.0"
    http-proxy-agent: "^5.0.0"
    https-proxy-agent: "^5.0.0"
    lodash.debounce: "^4.0.8"
    lodash.isequal: "^4.5.0"
    marked: "^4.1.1"
    nedb-promises: "^6.2.1"
    opml-to-json: "^1.0.1"
    process: "^0.11.10"
    socks-proxy-agent: "^6.0.0"
    video.js: 7.18.1
    videojs-contrib-quality-levels: "^2.1.0"
    videojs-http-source-selector: "^1.1.6"
    videojs-mobile-ui: "^0.8.0"
    videojs-overlay: "^2.1.4"
    videojs-vtt-thumbnails-freetube: 0.0.15
    vue: "^2.7.13"
    vue-i18n: "^8.28.1"
    vue-observe-visibility: "^1.0.0"
    vue-router: "^3.6.5"
    vuex: "^3.6.2"
    youtube-suggest: "^1.2.0"
    yt-channel-info: "^3.2.1"
    yt-dash-manifest-generator: 1.1.0
    ytdl-core: "^4.11.2"
    ytpl: "^2.3.0"
    ytsr: "^3.8.0"
---