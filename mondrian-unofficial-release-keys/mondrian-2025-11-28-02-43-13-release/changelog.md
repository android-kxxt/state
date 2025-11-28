- `packages/apps/SetupWizard`: SetupWizard: Actually remove 2 button nav leftovers<br>
  2025-11-02T00:52:17Z by [pnguyen879](mailto:howardson2001@gmail.com) [d470698baff6](https://github.com/LineageOS/android_packages_apps_SetupWizard/commit/d470698baff6)  [Review](https://review.lineageos.org/q/I939906cd89fac2b3b9bc778148e5947b04a100d1)
- `vendor/lineage`: build: Fix sourcing envsetup from anywhere<br>
  2025-11-17T17:26:41Z by [Michael Bestas](mailto:mkbestas@lineageos.org) [c4e86b6e4a39](https://github.com/LineageOS/android_vendor_lineage/commit/c4e86b6e4a39)  [Review](https://review.lineageos.org/q/Id1ee24e89a554c8de42366f9f0f5da03d3c86143)
- `hardware/qcom-caf/sm8750/display/core`: Reapply &quot;Revert^2 &quot;sdm: add support for DS merge mode&quot;&quot;<br>
  2025-11-18T15:49:05Z by [Giovanni Ricca](mailto:giovanniricca@proton.me) [dc857522011e](https://github.com/LineageOS/android_vendor_qcom_opensource_display-core/commit/dc857522011e)  [Review](https://review.lineageos.org/q/I2ba56dfa868d43f3a2f7e4fc5216d72a41486401)
- `lineage/hudson`: hudson: Promote dre to 23.0<br>
  2025-11-19T00:21:18Z by [Nick Reuter](mailto:nreuter85@gmail.com) [661ad5b7a63c](https://github.com/LineageOS/hudson/commit/661ad5b7a63c)  [Review](https://review.lineageos.org/q/I8667e3f35a762adbfb68b1114f679d49d60ce46b)
- `device/xiaomi/mondrian`: mondrian: Update blobs and firmware from OS2.0.208.0.VMNMIXM<br>
  2025-11-20T12:50:56Z by [Arian](mailto:arian.kulmer@web.de) [0377ab689255](https://github.com/LineageOS/android_device_xiaomi_mondrian/commit/0377ab689255)  [Review](https://review.lineageos.org/q/Iccdfdbfec4f58c1c34f6ba3ad3a85608b75c0108)
- `vendor/xiaomi/mondrian`: mondrian: Update blobs and firmware from OS2.0.208.0.VMNMIXM<br>
  2025-11-20T12:51:06Z by [Arian](mailto:arian.kulmer@web.de) [daa1fdcab02c](https://github.com/TheMuppets/proprietary_vendor_xiaomi_mondrian/commit/daa1fdcab02c) 
- `hardware/qcom-caf/sm8750/display/core`: Revert &quot;display-core: Make IsGPUHWAvailable() non-virtual and force it to true&quot;<br>
  2025-11-20T13:51:17Z by [Bruno Martins](mailto:bgcngm@gmail.com) [4a213555352d](https://github.com/LineageOS/android_vendor_qcom_opensource_display-core/commit/4a213555352d)  [Review](https://review.lineageos.org/q/I90bee7abe59771dfa6a2c7238f54d5ca59608c9c)
- `hardware/qcom-caf/sm8750/display/core`: Merge tag &#x27;DISPLAY.LA.5.0.r1-06900-pakala.0&#x27; of https://git.codelinaro.org/clo/la/platform/vendor/opensource/display-core into HEAD  <details>
    <summary>Merge Details</summary>

      DISPLAY.LA.5.0.r1-06900-pakala.0
      
      * tag 'DISPLAY.LA.5.0.r1-06900-pakala.0' of https://git.codelinaro.org/clo/la/platform/vendor/opensource/display-core:
        sdmclient: Add logs for layer marked as skip
        sdm: Avoid null commit at the start of TUI in VHM
        sdm: Support AgingSurface loading
        sdm: Bypass compilation for Aiqe
        display-core: Bypass compilation for formats
        snapalloc: Set graphics metadata on auxiliary buffer at allocation time
        Fix non-constant-expression build time error
        sdm: Avoid disconnecting WFD while initiating secure session
        sdm: Avoid config change when transitioning to active mode
        sdmclient: Reset the first_cycle flag in Postcommit.
        sdmclient: Update SetDisplayBrightness API
        sdmclient: Don't wait for VM reclaim during TUI end.
        sdm: Wait for VM reclaim event before handling TUI end.
        snapalloc: Update non-fatal error logs to warning in Metadata APIs
        sdm: Wait for VM reclaim event before handling TUI end.
        display-core: Skip ABC files export for secondary panel
        sdmclient: Add helper API for Layer Command BufferSlotsToClear
        snapalloc: Update non-fatal error logs to warning in Metadata APIs
        display-core: Export ABC config files during re-config
        sdm: Add check for mode change before setting bit_clk_rate_
        sdmclient: Fix CheckLayerBufferBinding definition dependency
        snapalloc: Close the fence FD after use in lock
        sdmclient: destroy pluggable displays during TUITransitionPrepare
        sdmclient: add definition for SetAIScalerMode API


    </details>

  2025-11-20T20:02:25Z by [Bruno Martins](mailto:bgcngm@gmail.com) [5c18ca2afe7c](https://github.com/LineageOS/android_vendor_qcom_opensource_display-core/commit/5c18ca2afe7c)  [Review](https://review.lineageos.org/q/I67e5a77999c4eee6384bca2eb58b4c668270d786)
- `hardware/qcom-caf/sm8750/display/hal`: Merge tag &#x27;DISPLAY.LA.5.0.r1-06900-pakala.0&#x27; of https://git.codelinaro.org/clo/la/platform/hardware/qcom/display into HEAD  <details>
    <summary>Merge Details</summary>

      DISPLAY.LA.5.0.r1-06900-pakala.0
      
      * tag 'DISPLAY.LA.5.0.r1-06900-pakala.0' of https://git.codelinaro.org/clo/la/platform/hardware/qcom/display:
        display: add soc ids for Sun iot
        gralloc: Increase allocator binder thread priority
        gralloc : Bypass compilation for formats not supported on neo
        init: add enable_snapalloc prop for neo61
        hw_fence: Conditional compilation of hw_fence for composerv3 and above
        init: Enable null-display for neo61 LA
        composer: Adapt SetDisplayBrightness API to new interface
        config: Set Blur property based for canoe target


    </details>

  2025-11-20T20:02:43Z by [Bruno Martins](mailto:bgcngm@gmail.com) [572019cf2315](https://github.com/LineageOS/android_hardware_qcom_display/commit/572019cf2315)  [Review](https://review.lineageos.org/q/I4c0de4eb2a72f1368d280cd72b44491948f0fa27)
- `hardware/qcom-caf/sm8750/display/intf`: Merge tag &#x27;DISPLAY.LA.5.0.r1-06900-pakala.0&#x27; of https://git.codelinaro.org/clo/la/platform/vendor/opensource/display-intf into HEAD  <details>
    <summary>Merge Details</summary>

      DISPLAY.LA.5.0.r1-06900-pakala.0
      
      * tag 'DISPLAY.LA.5.0.r1-06900-pakala.0' of https://git.codelinaro.org/clo/la/platform/vendor/opensource/display-intf:
        display-intf: Add VIEW_ID Metadata type
        display-intf: Add 1K aligned format & modifier
        display-intf: add deinit method to lifecycle
        sdmclient: Update SetDisplayBrightness API
        display-intf: Enumerate MIPMAP formats and modifiers
        display-intf: Add CheckLayerBufferBinding API interface
        display-intf: Add support for HDR/SDR ratio
        common: Add support for UBWC 6.0
        common: Add support for UBWC 6.0
        sdmclient: Add new API for AI Scaler in AIQE display interface


    </details>

  2025-11-20T20:03:11Z by [Bruno Martins](mailto:bgcngm@gmail.com) [19b5c055b40b](https://github.com/LineageOS/android_vendor_qcom_opensource_display-intf/commit/19b5c055b40b)  [Review](https://review.lineageos.org/q/I64642d123e323772033a465d36f5d07c41457f75)
- `device/qcom/sepolicy_vndr/sm8550`: BOARD_SYSTEM_EXT_PREBUILT_DIR is obsolete. Use BOARD_SYSTEM_EXT_SEPOLICY_PREBUILT_DIRS<br>
  2025-11-21T01:51:44Z by [Ankit Lathiya](mailto:alathiya@qti.qualcomm.com) [c2a16e970877](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/c2a16e970877)  [Review](https://review.lineageos.org/q/Ibab1dd25e4db1505c2dcb2f8cd852daf7416e0db)
- `state`: Save state of mondrian-2025-11-21-02-51-47-release<br>
  2025-11-21T03:27:18Z by [kxxt](mailto:rsworktech@outlook.com) [bf5ffb4c5d7b](https://github.com/android-kxxt/state/commit/bf5ffb4c5d7b) 
- `state`: Generate changelog for mondrian-2025-11-21-02-51-47-release<br>
  2025-11-21T03:28:01Z by [kxxt](mailto:rsworktech@outlook.com) [376e09a4b408](https://github.com/android-kxxt/state/commit/376e09a4b408) 
- `ota`: Update OTA metadata for mondrian (UNOFFICIAL, Release)<br>
  2025-11-21T03:35:13Z by [kxxt](mailto:rsworktech@outlook.com) [1313fb0af661](https://github.com/android-kxxt/ota/commit/1313fb0af661) 
- `device/qcom/sepolicy_vndr/sm8450`: BOARD_SYSTEM_EXT_PREBUILT_DIR is obsolete. Use BOARD_SYSTEM_EXT_SEPOLICY_PREBUILT_DIRS<br>
  2025-11-21T22:26:32Z by [Ankit Lathiya](mailto:alathiya@qti.qualcomm.com) [3cf5bcbc1052](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/3cf5bcbc1052)  [Review](https://review.lineageos.org/q/Ibab1dd25e4db1505c2dcb2f8cd852daf7416e0db)
- `device/qcom/sepolicy_vndr/sm8650`: BOARD_SYSTEM_EXT_PREBUILT_DIR is obsolete. Use BOARD_SYSTEM_EXT_SEPOLICY_PREBUILT_DIRS<br>
  2025-11-21T22:26:50Z by [Ankit Lathiya](mailto:alathiya@qti.qualcomm.com) [2c83259538a5](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/2c83259538a5)  [Review](https://review.lineageos.org/q/Ibab1dd25e4db1505c2dcb2f8cd852daf7416e0db)
- `device/qcom/sepolicy_vndr/sm8750`: BOARD_SYSTEM_EXT_PREBUILT_DIR is obsolete. Use BOARD_SYSTEM_EXT_SEPOLICY_PREBUILT_DIRS<br>
  2025-11-21T22:26:59Z by [Ankit Lathiya](mailto:alathiya@qti.qualcomm.com) [dd8ebd72c21d](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/dd8ebd72c21d)  [Review](https://review.lineageos.org/q/Ibab1dd25e4db1505c2dcb2f8cd852daf7416e0db)
- `packages/apps/LineageParts`: LineageParts: Set group key for contributors cloud IA<br>
  2025-11-22T23:27:38Z by [LuK1337](mailto:priv.luk@gmail.com) [5b14bf8c2437](https://github.com/LineageOS/android_packages_apps_LineageParts/commit/5b14bf8c2437)  [Review](https://review.lineageos.org/q/I544d216da86a107d4901ce752cbd79a425500c7a)
- `packages/apps/LineageParts`: ChargingControlSettings: Ditch DropDownPreference and use ListPreference<br>
  2025-11-23T12:15:28Z by [Bruno Martins](mailto:bgcngm@gmail.com) [31662bd36c81](https://github.com/LineageOS/android_packages_apps_LineageParts/commit/31662bd36c81)  [Review](https://review.lineageos.org/q/Ib4a82e9c66e5d8606ad8845fa71eeb894b535a94)
- `lineage-sdk`: LineagePreferenceLib: RIP DropDownPreference type<br>
  2025-11-23T12:15:38Z by [Bruno Martins](mailto:bgcngm@gmail.com) [60d0477f66f4](https://github.com/LineageOS/android_lineage-sdk/commit/60d0477f66f4)  [Review](https://review.lineageos.org/q/I780009571b9bde2e7655a77c8d683f66225ab6ad)
- `device/qcom/sepolicy-legacy-um`: legacy: Disallow system_server from loading kernel modules<br>
  2025-11-23T16:14:09Z by [LuK1337](mailto:priv.luk@gmail.com) [a6b7ae68c751](https://github.com/LineageOS/android_device_qcom_sepolicy/commit/a6b7ae68c751)  [Review](https://review.lineageos.org/q/I20560c2d7305ee351ca5105aa282357105003e6a)
- `device/qcom/sepolicy_vndr/legacy-um`: legacy: Disallow system_server from loading kernel modules<br>
  2025-11-23T16:15:04Z by [LuK1337](mailto:priv.luk@gmail.com) [f06f20f3a902](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/f06f20f3a902)  [Review](https://review.lineageos.org/q/I20560c2d7305ee351ca5105aa282357105003e6a)
- `lineage/wiki`: devices: dre: Promote to 23.0<br>
  2025-11-23T16:58:46Z by [Nick Reuter](mailto:nreuter85@gmail.com) [444f8d07712d](https://github.com/LineageOS/lineage_wiki/commit/444f8d07712d)  [Review](https://review.lineageos.org/q/I831d3939252f0f943e419e8b13c0b186fb183268)
- `device/qcom/sepolicy-legacy-um`: legacy: Grant sys_module cap for correct wifi/wigig domains<br>
  2025-11-23T18:53:45Z by [LuK1337](mailto:priv.luk@gmail.com) [b28a32c46c67](https://github.com/LineageOS/android_device_qcom_sepolicy/commit/b28a32c46c67)  [Review](https://review.lineageos.org/q/Ie3b183d600390baca71851d9a45e14648a9172ae)
- `device/qcom/sepolicy_vndr/legacy-um`: legacy: Grant sys_module cap for correct wifi/wigig domains<br>
  2025-11-23T18:54:49Z by [LuK1337](mailto:priv.luk@gmail.com) [ac205a3f1585](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/ac205a3f1585)  [Review](https://review.lineageos.org/q/Ie3b183d600390baca71851d9a45e14648a9172ae)
- `device/xiaomi/sm8250-common`: sm8250-common: Convert overlays to RRO<br>
  2025-11-23T23:02:58Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [1f60b5ddd2de](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/1f60b5ddd2de)  [Review](https://review.lineageos.org/q/Id0226559b81e115a6340591e7a107d25d7ad6848)
- `device/xiaomi/lmi`: lmi: Convert overlays to RRO<br>
  2025-11-23T23:52:18Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [6efad5a890a2](https://github.com/xiaomi-sm8250-devs/android_device_xiaomi_lmi/commit/6efad5a890a2) 
- `lineage/wiki`: wiki: Update gauguin maintainer list<br>
  2025-11-25T01:50:02Z by [Penguin766](mailto:p7040647@gmail.com) [4b134c267cf0](https://github.com/LineageOS/lineage_wiki/commit/4b134c267cf0)  [Review](https://review.lineageos.org/q/I697b6458cacc14b8d815061f1a81fddbd1ac6d86)
- `packages/apps/LineageParts`: LineageParts: Add MD3 styling to Trust notification<br>
  2025-11-25T08:13:50Z by [pnguyen879](mailto:howardson2001@gmail.com) [f74caaf24ddc](https://github.com/LineageOS/android_packages_apps_LineageParts/commit/f74caaf24ddc)  [Review](https://review.lineageos.org/q/I74e6c0f6c915dce3be680768cbb100e4432c17ef)
- `lineage/mirror`: Updated to 25-Nov-2025 11:01 UTC<br>
  2025-11-25T11:01:39Z by [Tim Schumacher](mailto:timschumi@gmx.de) [2074512360c3](https://github.com/LineageOS/mirror/commit/2074512360c3)  [Review](https://review.lineageos.org/q/Ia5435bc394a9b0a45a3251932601f81829e5e6ab)
- `hardware/qcom-caf/sm8450/audio/pal`: Revert &quot;ResourceManager: fix activeStreams check&quot;<br>
  2025-11-25T11:29:34Z by [Fiqri Ardyansyah](mailto:fiqri191002@gmail.com) [0ab95e9be6aa](https://github.com/LineageOS/android_vendor_qcom_opensource_arpal-lx/commit/0ab95e9be6aa)  [Review](https://review.lineageos.org/q/Ieaa95b8f4b5f3e2d47edc3372d7054661b6e5be3)
- `lineage/hudson`: Regenerate device dependency mappings<br>
  2025-11-25T23:30:51Z by [LineageOS Infra](mailto:infra@lineageos.org) [4eb5ef00ae90](https://github.com/LineageOS/hudson/commit/4eb5ef00ae90)  [Review](https://review.lineageos.org/q/I99dc4358147a7a31fea3dcf326ff0e286759e73a)
- `packages/apps/LineageParts`: DisplayRotation: Use new method to listen for preference changes<br>
  2025-11-26T00:57:39Z by [Bruno Martins](mailto:bgcngm@gmail.com) [3cc78273c510](https://github.com/LineageOS/android_packages_apps_LineageParts/commit/3cc78273c510)  [Review](https://review.lineageos.org/q/I7a31cbdb8b68fc9e851c040f6b056bf7bfa5d2a8)
- `lineage/hudson`: Time is money<br>
  2025-11-26T04:33:18Z by [pnguyen879](mailto:howardson2001@gmail.com) [8496bac150ad](https://github.com/LineageOS/hudson/commit/8496bac150ad)  [Review](https://review.lineageos.org/q/Ib091879b51f0856b04da0b3c3587a816ff9e24f4)
- `lineage/wiki`: wiki: devices: Add LG V60 ThinQ (timelm)<br>
  2025-11-26T05:18:49Z by [pnguyen879](mailto:howardson2001@gmail.com) [e7987ee6ffb4](https://github.com/LineageOS/lineage_wiki/commit/e7987ee6ffb4)  [Review](https://review.lineageos.org/q/I9330eaca1d959e64a7c9af2264a6a950cc3294bb)
- `lineage/wiki`: wiki: Update alioth maintainer list<br>
  2025-11-26T18:46:27Z by [Christian Hoffmann](mailto:chrmhoffmann@gmail.com) [e880e36eb3c9](https://github.com/LineageOS/lineage_wiki/commit/e880e36eb3c9)  [Review](https://review.lineageos.org/q/If042a18215033b998d0e69765b770ca184c8e68b)
- `lineage/hudson`: sake: Promote to 23.0<br>
  2025-11-27T10:07:02Z by [Michael Zh](mailto:mikooomichael@gmail.com) [b3b5d56215eb](https://github.com/LineageOS/hudson/commit/b3b5d56215eb)  [Review](https://review.lineageos.org/q/I38d35a4b8154813d949419da80f5a2c2ed22a19c)
- `lineage/wiki`: wiki: Promote sake to 23.0<br>
  2025-11-27T10:07:31Z by [Michael Zh](mailto:mikooomichael@gmail.com) [ea98db60f69a](https://github.com/LineageOS/lineage_wiki/commit/ea98db60f69a)  [Review](https://review.lineageos.org/q/Ia48305d39ddf69bac85a80305de7668b201e63b0)
- `lineage/wiki`: wiki: Allow A16 FW for dodge and erhai<br>
  2025-11-27T14:43:54Z by [LuK1337](mailto:priv.luk@gmail.com) [42682e474ae0](https://github.com/LineageOS/lineage_wiki/commit/42682e474ae0)  [Review](https://review.lineageos.org/q/I5cd4827dacd3b4f0ac21b30e2e8d3096381e0aff)
