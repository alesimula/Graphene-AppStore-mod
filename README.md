GrapheneOS store mod with unlocked repository access.

Allows you do download the Vanadium browser and the Messaging app (the latter has package name "com.android.messaging" and will fail to install on ROMs where the messaging app has the same package name).

You can also install and enable the Vanadium webview using the MyWebView xposed module, which allows you to select any webview in developer options after enabling it and rebooting.

WARNING: although the client allows you to install Google Play Services, these are just vanilla non-sandboxed play services, as sandboxing would require the Sandboxed Google Play compatibility layer (GmsCompat), which is part of the GrapheneOS system; GmsCompatConfig only contains configuration data and nothing more
