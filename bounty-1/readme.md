# Use live-server or http-server to run this

-   Please use live-server or http-server to run the file or you will face the error of "Failed to execute 'createMediaKeys' on 'MediaKeySystemAccess': EME use is not allowed on unique origins,".
-   Which is related to Encrypted Media Extensions (EME) and is typically associated with playback of encrypted content, such as videos protected by Digital Rights Management (DRM).
-   The video is encrypted by videojs-contrib-eme plugin.
-   This error often occurs when running your application in an environment where EME is restricted, which can be the case when opening the HTML file directly in Chrome.
