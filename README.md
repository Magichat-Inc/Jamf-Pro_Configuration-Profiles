# Jamf-Pro_Configuration-Profiles

## 概要(Overview)
mac 管理のための便利な構成プロファイル集 <br/>
A collection of useful configuration profiles for mac management

## コンテンツ(Contents)
 | Filename | Preference Domain | Description(J/E) |
 | --- | --- | --- |
 | DisableCloudPhotoLibrary | com.apple.applicationaccesss | iCloud 写真を無効化 <br /> Disable iCloud Photos |
 | DisableFMM | com.apple.icloud.managed | 「探す」を無効化 <br/> Disable Find My Mac |
 | DisableSiri | com.apple.assistant.support | 「"Siri に頼む"を有効にする」の無効化 <br/> Disable Siri |
 | DisableSiriMenuBar | com.apple.Siri | 「メニューバーに Siri を表示」の無効化 <br/> lock Siri’s menubar icon |
 | DisableiTunesFileSharing | com.apple.applicationaccess | mac にiPhone ( iPad ) 接続時、Finder に「ファイル」タブを表示させない <br/> Don't show File tab in Finder when iPhone (iPad) is connected to mac |
 | MajorUpgradePostponement | com.apple.applicationaccess | macOSメジャーアップグレードの延期 <br/> delays user visibility of major upgrades to OS Software. Available in macOS 11.3 and later. |

## 使い方(Usage)

- plist <br/>
Jamf Pro のコンピュータ > 構成プロファイル > アプリケーションとカスタム設定 > アップロードからアップロードしてください <br/>
Upload to Computers > Configuration Profiles > Application & Custom Settings > Upload <br/>

e.g. <br/>
<img width="834" alt="upload" src="https://user-images.githubusercontent.com/90596025/170526866-22b3d239-a0a5-4c34-afde-732f5aa63025.png"> <br/>

- mobileconfig <br/>
ファイルを開いてシステム環境設定の「プロファイル」からインストールしてください <br/>
Open the file and install from Profiles preferences in System Preferences <br/> <br/>
