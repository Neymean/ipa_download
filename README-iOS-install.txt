GitHub Pages structure for iOS OTA installation

Upload these files/folders to the repository root:
  index.html
  plist/
  icons_masked/

The 13 Install buttons use:
  itms-services://?action=download-manifest&url=https://neymean.github.io/ipa_download/plist/<file>.plist

Important: the IPA URLs inside the manifests still point to the GitHub Releases assets from the original manifests.
The IPA itself must be correctly signed for the target device (for example, with a valid Ad Hoc profile and registered UDID, where applicable).
