set(SOURCES Addon.cpp
            AddonBuilder.cpp
            BinaryAddonCache.cpp
            AddonDatabase.cpp
            AddonInfo.cpp
            AddonInstaller.cpp
            AddonManager.cpp
            AddonStatusHandler.cpp
            AddonSystemSettings.cpp
            AddonVersion.cpp
            AudioDecoder.cpp
            AudioEncoder.cpp
            ContextMenuAddon.cpp
            ContextMenus.cpp
            FilesystemInstaller.cpp
            GameResource.cpp
            GUIDialogAddonInfo.cpp
            GUIViewStateAddonBrowser.cpp
            GUIWindowAddonBrowser.cpp
            ImageDecoder.cpp
            ImageResource.cpp
            InputStream.cpp
            LanguageResource.cpp
            PluginSource.cpp
            PVRClient.cpp
            Repository.cpp
            RepositoryUpdater.cpp
            Scraper.cpp
            ScreenSaver.cpp
            Service.cpp
            Skin.cpp
            UISoundsResource.cpp
            VFSEntry.cpp
            Visualization.cpp
            Webinterface.cpp)

set(HEADERS Addon.h
            AddonBuilder.h
            AddonEvents.h
            BinaryAddonCache.h
            AddonDatabase.h
            AddonInfo.h
            AddonInstaller.h
            AddonManager.h
            AddonStatusHandler.h
            AddonSystemSettings.h
            AddonVersion.h
            AudioDecoder.h
            AudioEncoder.h
            ContextMenuAddon.h
            ContextMenus.h
            DllLibCPluff.h
            FilesystemInstaller.h
            GameResource.h
            GUIDialogAddonInfo.h
            GUIViewStateAddonBrowser.h
            GUIWindowAddonBrowser.h
            IAddon.h
            ImageDecoder.h
            ImageResource.h
            InputStream.h
            LanguageResource.h
            PluginSource.h
            PVRClient.h
            Repository.h
            RepositoryUpdater.h
            Resource.h
            Scraper.h
            ScreenSaver.h
            Service.h
            Skin.h
            UISoundsResource.h
            VFSEntry.h
            Visualization.h
            Webinterface.h)

core_add_library(addons)
