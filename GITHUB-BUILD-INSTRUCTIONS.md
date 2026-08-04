# GitHub se iOS build kaise banayein

1. Is folder ke **andar ki sari files** GitHub repository ke root me upload karein.
2. Repository ka default branch `main` rakhein.
3. GitHub me **Actions** tab kholein.
4. **Build iOS App** workflow select karein.
5. **Run workflow** par click karein.
6. Build complete hone ke baad run ke neeche **Artifacts** se `Kashmir-Travelify-CRM-iOS-Simulator` download karein.

## Important

GitHub workflow abhi unsigned **iOS Simulator build** banata hai. Yeh `.app` simulator ke liye hai; direct physical iPhone par install hone wali `.ipa` nahi hai.

Physical iPhone, TestFlight ya App Store ke liye Apple Developer account, certificate, provisioning profile aur signing setup karna zaroori hai. Xcode project Mac me open karke Team select karke bhi device build kiya ja sakta hai.
