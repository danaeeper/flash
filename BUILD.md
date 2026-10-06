# Build

If you have XcodeGen installed:

```sh
./Scripts/fetch_ruffle.sh
xcodegen generate
open FlashBox.xcodeproj
```

Then select your iPhone and Run. For SideStore/LiveContainer, archive/export the resulting app as an unsigned/ad-hoc-compatible IPA according to your signing workflow.
