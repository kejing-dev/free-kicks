# Validation / 验证记录

- Release build: **v0.16.0**, versionCode **16**, arm64-v8a, non-debuggable.
- Tests: **75 passed**, 0 failures, 0 errors.
- APK signature verified with Android apksigner. Public certificate: [signature.txt](signature.txt).
- APK SHA-256: `05cbffe3624af4a05d9fb76160278d6b571bbffa0b4ab68215c692afafcbd012`.
- Only this game's runtime media is included; other games' simulation code remains in the shared regression library.
- Native screenshots come from accepted development builds (v0.16). Release compilation, signature, manifest and tests were checked separately. Physical hand tracking, ray dragging and long-session performance are not claimed as release acceptance.

本次生成独立项目、正式签名的 release APK。已核对构建类型、签名、包名、资源范围和 75 项测试。截图来自此前已验证开发版；发行包的真实手势仍需设备验收。

See [machine-readable evidence](build-verification.json).
