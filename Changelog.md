NvidiaGraphicsFixup Changelog
=============================
#### v1.2.1
- All patches can be turned off by boot-args (and some of them can be also turned off by using ioreg properties)

#### v1.2.0
- Lilu 1.2.0 compatibility fixes
- NVidiaAudio device to add connector-type, layout-id and other properties for HDMI audio (allows audio for HDMI, DP, Digital DVI ports)
- A new hook for nvAcceleratorParent::SetAccelProperties to add properties "IOVARendererID" and "IOVARendererSubID"
- NVWebDriverLibValFix fix is implemented (csfg_get_platform_binary)

#### v1.1.3
- High Sierra compatibility

#### v1.1.2
- Added OSBundleCompatibleVersion

#### v1.1
- Patch has been improved (vit9696)

#### v1.0.0
- Initial release
