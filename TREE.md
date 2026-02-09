.
|-- .github
|   `-- workflows
|       `-- pre-commit-checks.yml
|-- LICENSE
|-- TREE.md
|-- aosp_diff
|   |-- base_aaos
|   |   `-- packages
|   |       `-- apps
|   |           `-- Car
|   |               |-- DialerPrebuilt
|   |               |   `-- 0001-Add-run-time-permissions-for-CarDialer-application.patch
|   |               `-- Settings
|   |                   `-- 0001-Fix-for-improper-text-alignment-in-bluetooth-rename-.patch
|   |-- caas
|   |   |-- art
|   |   |   `-- 0001-Throw-an-exception-in-JNI-NewObject-for-abstract-cla.patch
|   |   |-- build
|   |   |   `-- make
|   |   |       `-- 0001-Fix-kernel-mismatch-error-in-BOARD_KERNEL_VERSION.patch
|   |   |-- frameworks
|   |   |   |-- av
|   |   |   |   |-- 0001-Code-changes-for-CTS-on-CtsVoiceInteractionTestCases.patch
|   |   |   |   `-- 0001-Enable-AIDL-as-first-option-in-audio-rc-file.patch
|   |   |   |-- base
|   |   |   |   |-- 0003-Defer-remove-splash-screen-while-device-is-locked.patch
|   |   |   |   |-- 0006-Fix-starting-the-activity-with-incorrect-pid-uid.patch
|   |   |   |   |-- 0007-Unexport-ControlsActivity.patch
|   |   |   |   |-- 0008-Don-t-show-dismissible-keyguard-in-app-pinning-mode.patch
|   |   |   |   |-- 0010-Use-consistent-animation-when-forcibly-hiding-non-sy.patch
|   |   |   |   |-- 0011-Do-not-allow-custom-animation-of-untrusted-Toast.patch
|   |   |   |   |-- 0012-Limits-the-display-name-to-1024-characters.patch
|   |   |   |   |-- 0013-Revert-Fix-biometric-prompt-appearing-above-shade.patch
|   |   |   |   |-- 0014-Avoid-mixups-between-different-CPSes-in-ZenModeCondi.patch
|   |   |   |   |-- 0015--Don-t-allow-hiding-SysUi.patch
|   |   |   |   |-- 0016-Prevent-non-system-ShutdownActivity-from-being-launc.patch
|   |   |   |   |-- 0017-Calculate-how-much-memory-is-used-per-account.patch
|   |   |   |   |-- 0018-Don-t-allow-SdkSandbox-to-bypass-systemUid-check.patch
|   |   |   |   |-- 0019-Prevent-root-from-getting-unverified-attributions-fr.patch
|   |   |   |   |-- 0020-Disallow-PINNED-in-setLaunchWindowingMode.patch
|   |   |   |   |-- 0021-Preflight-skip-datasource-validation.patch
|   |   |   |   |-- 0022-Ensuring-valid-packageName-when-granting-slice-permi.patch
|   |   |   |   |-- 0023-DevicePolicyManager-ignore-invalid-proxy-settings.patch
|   |   |   |   |-- 0024-Check-DPC-package-validity-during-package-updates.patch
|   |   |   |   |-- 0025-Trim-oversized-strings-in-setId-and-setConversationI.patch
|   |   |   |   |-- 0026-cleanup-Fix-permission-protection-of-setObservedMoti.patch
|   |   |   |   |-- 0027-cleanup-Fix-permission-protection-of-setObservedMoti.patch
|   |   |   |   `-- 0028-Implement-onNullBinding-in-autofill-service-connecti.patch
|   |   |   |-- native
|   |   |   |   |-- 0001-Allow-gpuservice-to-read-tracefs-entries.patch
|   |   |   |   |-- 0002-update-vulkanhardware-version.patch
|   |   |   |   |-- 0003-Protect-objects-in-Parcel-appendFrom.patch
|   |   |   |   |-- 0004-RPC-Binder-shutdown-on-ENOMEM.patch
|   |   |   |   |-- 0005-RPC-Binder-shutdown-on-SPAN-error.patch
|   |   |   |   |-- 0006-RPC-Binder-clearer-errors-for-wrong-transact-type.patch
|   |   |   |   `-- 0007-Don-t-blur-too-many-layers.patch
|   |   |   `-- opt
|   |   |       `-- telephony
|   |   |           `-- 0001-Remove-get-set-of-voicemail-ringtone-uri-in-shared-p.patch
|   |   |-- hardware
|   |   |   `-- interfaces
|   |   |       `-- 0001-ExternalCameraHAL-Fix-incorrect-nullptr-check-on-buf.patch
|   |   |-- include_preliminary
|   |   |-- packages
|   |   |   |-- apps
|   |   |   |   |-- Camera2
|   |   |   |   |   |-- 0001-WA-ignore-internal-storage-error-for-capture-record.patch_bkup
|   |   |   |   |   `-- 0001-workaround-solution-to-allow-capture-record-even-on-storage_error.patch
|   |   |   |   |-- Contacts
|   |   |   |   |   `-- 0001-Show-account-selection-dialog-when-a-single-account-.patch
|   |   |   |   |-- DocumentsUI
|   |   |   |   |   `-- 0001-Trim-the-application-name-to-make-it-safe-for-presen.patch
|   |   |   |   |-- ManagedProvisioning
|   |   |   |   |   |-- 0001-Fix-confused-deputy-vulnerability-in-termsActivity-t.patch
|   |   |   |   |   `-- 0002-Skip-permission-check-for-SCHEME_ANDROID_RESOURCE.patch
|   |   |   |   `-- Settings
|   |   |   |       |-- 0001-Add-ComponentName-explicitly-to-make-sure-arbitary-i.patch
|   |   |   |       |-- 0002-AppRestrictions-use-vetted-component.patch
|   |   |   |       |-- 0003-Do-not-enable-the-Content-Protection-toggle-for-non-.patch
|   |   |   |       |-- 0004-Drop-PendingIntent-extras-from-external-packages-dur.patch
|   |   |   |       |-- 0005-Use-correct-API-to-get-calling-package-name-in-Crede.patch
|   |   |   |       |-- 0006-Hide-notification-content-in-history.patch
|   |   |   |       |-- 0007-startActivityForResult-with-earlier-new-Intent.patch
|   |   |   |       `-- 0008-Ignore-face-settings-extras-when-called-by-an-extern.patch
|   |   |   |-- modules
|   |   |   |   |-- Bluetooth
|   |   |   |   |   |-- 0001-Remove-flags-for-b-314331379.patch
|   |   |   |   |   `-- 0002-Fix-use-after-free-in-acl_arbiter.patch
|   |   |   |   |-- CellBroadcastService
|   |   |   |   |   `-- 0001-RESTRICT-AUTOMERGE-Update-getDefaultCBRPackageName-f.patch
|   |   |   |   |-- IntentResolver
|   |   |   |   |   `-- 0002-Launch-image-editor-as-sharesheet-launching-user-fla.patch
|   |   |   |   |-- Permission
|   |   |   |   |   `-- 0001-Stop-one-time-sessions-iff-when-no-one-time-permissi.patch
|   |   |   |   |-- Wifi
|   |   |   |   |   `-- 0001-Do-not-treat-SdkSandBox-as-privileges-App.patch
|   |   |   |   `-- adb
|   |   |   |       `-- 0001-Allow-shell-to-read-tracefs-entries.patch
|   |   |   `-- providers
|   |   |       `-- MediaProvider
|   |   |           `-- 0001-RESTRICT-AUTOMERGE-Refactor-PickerDbFacade-queryMedi.patch
|   |   `-- system
|   |       `-- sepolicy
|   |           |-- 0001-Grant-permission-for-mediatranscoding-hal_allocator-.patch
|   |           `-- 0003-Fix-for-Fuzzer-error-with-lunch-caas-ap3a-user.patch
|   `-- preliminary
|       |-- .gitkeep
|       |-- art
|       |   `-- 0001-Throw-an-exception-in-JNI-NewObject-for-abstract-classes-.bulletin.patch
|       |-- bionic
|       |   |-- 0001-Update-libdl-bionic-library.patch
|       |   |-- 0002-WA-Fixed-build-error-in-bionic.patch
|       |   `-- 0003-Adding-header-check-to-resolve-redefinition-error.patch
|       |-- bootable
|       |   `-- recovery
|       |       |-- 01_0001-Support-ota-update-from-udisk.patch
|       |       |-- 02_0002-fastbootd-sleep-several-seconds-to-wait-for-ethernet.patch
|       |       `-- 03_0003-Use-Device-instead-of-RecoveryUI.patch
|       |-- build
|       |   |-- blueprint
|       |   |   `-- 0001-WA-Fix-to-pass-build-error.patch
|       |   |-- make
|       |   |   |-- 0001-Allow-link-to-native-platform-and-vndk_private.patch
|       |   |   |-- 0002-REVERTME-Allow-overrides-for-below-make-variables.patch
|       |   |   |-- 0003-Fix-signapk.jar-path-for-RELEASE_BUILD-true-case.patch
|       |   |   |-- 0004-WA-Revert-Handle-zip64-extra-fields-better.patch
|       |   |   |-- 0007-fix-ota-update-failure-cause-by-vabc-config-change.patch
|       |   |   |-- 0008-Revert-remove-unused-files-in-fake_device_config.patch
|       |   |   `-- 0009-Add-apexd-mainline_patch_level_2-to-PRODUCT_PACKAGES.bulletin.patch
|       |   |-- release
|       |   |   `-- 0001-Update-RELEASE_PLATFORM_SECURITY_PATCH-string.patch
|       |   |-- soong
|       |   |   |-- 0001-Add-support-for-overide_lib_name-for-IA-perf-variant.patch
|       |   |   |-- 0002-Enable-path-restrictions-for-Android-11.patch
|       |   |   |-- 0002-WA-Build-soong-errors.patch
|       |   |   |-- 0004-Adding-the-dpkg-deb-package-needed-to-create-deb.patch
|       |   |   `-- 0006-Allow-build-commands-to-make-Celadon-as-ISO-format-i.patch
|       |   `-- target
|       |       `-- 0001-Add-apexd.mainline_patch_level_2-to-PRODUCT_PACKAGES.patch
|       |-- cts
|       |   `-- 0001-Track-DNG-SDK-1-7-1-API-changes.bulletin.patch
|       |-- development
|       |   `-- python-packages
|       |       `-- 0001-Adding-mako-module-to-python-development-packages.patch
|       |-- external
|       |   |-- angle
|       |   |   |-- 0001-Vulkan-Don-t-require-renderability-in-AHBs.patch
|       |   |   `-- 0002-Vulkan-populate-ycbcr-conversionDesc-for-yuv-VkForma.patch
|       |   |-- boringssl
|       |   |   `-- 0001-WA-Fixed-build-error-in-boringssl.patch
|       |   |-- dng_sdk
|       |   |   `-- 0001-Crude-DNG-SDK-1-7-1-upgrade.bulletin.patch
|       |   |-- drm_hwcomposer
|       |   |   `-- 0001-Use-private-drm_hwcomposer-instead-of-external.patch
|       |   |-- gmmlib
|       |   |   `-- 0001-Use-Intel-internal-gmmlib-instead-of-Google-release.patch
|       |   |-- intel-media-driver
|       |   |   `-- 0001-We-are-using-intel-media-driver.patch
|       |   |-- libdrm
|       |   |   |-- 0001-use-private-libdrm-instead-of-external-libdrm.patch
|       |   |   |-- 0002-Using-private-libs-instead-of-google-libs.patch
|       |   |   `-- 0003-Update-libdrm-to-use-internal-libdrm-instead.patch
|       |   |-- libva
|       |   |   `-- 0001-Updating-libva-build-libs-according-to-latest-Code.patch
|       |   |-- minigbm
|       |   |   `-- 0001-Remove-aidl-libminigbm_gralloc_-and-gralloc.-Android.patch
|       |   |-- selinux
|       |   |   `-- 0001-Init-members-for-avtab_match_args-before-using.patch
|       |   |-- skia
|       |   |   `-- 0001-Backport-DNG-SDK-1-7-1-support-in-SkRawCodec.bulletin.patch
|       |   |-- virglrenderer
|       |   |   `-- 0001-libgbm-is-not-used-by-IA.patch
|       |   `-- wpa_supplicant_8
|       |       `-- 0001-Fix-wifi-connection-failure.patch
|       |-- frameworks
|       |   |-- av
|       |   |   |-- 0001-fixed-audio-crash-issue.patch
|       |   |   |-- 0007-Dynamically-disable-audio-codes.patch
|       |   |   `-- 0008-C2SoftDav1dDec-configure-decoder-to-output-only-one-layer-in-SV.bulletin.patch
|       |   |-- base
|       |   |   |-- 0001-HWUI-Fallback-to-Medium-priority-when-high-is-not-pe.patch
|       |   |   |-- 0002-Avoiding-Error-logs-During-framework-boot.patch
|       |   |   |-- 0003-Defer-remove-splash-screen-while-device-is-locked.bulletin.patch
|       |   |   |-- 0004-Fix-starting-the-activity-with-incorrect-pid-uid.bulletin.patch
|       |   |   |-- 0005-Don-t-show-dismissible-keyguard-in-app-pinning-mode.bulletin.patch
|       |   |   |-- 0006-Unexport-ControlsActivity.bulletin.patch
|       |   |   |-- 0007-Use-consistent-animation-when-forcibly-hiding-non-system-overlay.bulletin.patch
|       |   |   |-- 0008-Do-not-allow-custom-animation-of-untrusted-Toast.bulletin.patch
|       |   |   |-- 0009-Limits-the-display-name-to-1024-characters.bulletin.patch
|       |   |   |-- 0010-Move-BP-window-to-Keyguard_dialog.bulletin.patch
|       |   |   |-- 0011-Avoid-mixups-between-different-CPSes-in-ZenModeConditions.bulletin.patch
|       |   |   |-- 0012-Don-t-allow-hiding-SysUi.bulletin.patch
|       |   |   |-- 0013-Prevent-non-system-ShutdownActivity-from-being-launched-by-Batte.bulletin.patch
|       |   |   |-- 0014-Calculate-how-much-memory-is-used-per-account-.bulletin.patch
|       |   |   |-- 0015-Don-t-allow-SdkSandbox-to-bypass-systemUid-check-.bulletin.patch
|       |   |   |-- 0016-Prevent-root-from-getting-unverified-attributions-from-non-syste.bulletin.patch
|       |   |   |-- 0017-RESTRICT-AUTOMERGE-Disallow-PINNED-in-setLaunchWindowingMode.bulletin.patch
|       |   |   |-- 0018-Ensuring-valid-packageName-when-granting-slice-permission.bulletin.patch
|       |   |   |-- 0019-DevicePolicyManager-ignore-invalid-proxy-settings.bulletin.patch
|       |   |   |-- 0020-Check-DPC-package-validity-during-package-updates.bulletin.patch
|       |   |   |-- 0021-Trim-oversized-strings-in-setId-and-setConversationId.bulletin.patch
|       |   |   |-- 0022-cleanup-Fix-permission-protection-of-setObservedMotionEventSour.bulletin.patch
|       |   |   |-- 0023-PrintSpooler-Require-empty-output-for-PDF.bulletin.patch
|       |   |   |-- 0024-Implement-onNullBinding-in-autofill-service-connection.bulletin.patch
|       |   |   |-- 0025--CDM-Revoke-NLS-when-all-associations-are-removed-.bulletin.patch
|       |   |   |-- 0026-Check-sound-Uri-permission-when-creating-a-notification-channel.bulletin.patch
|       |   |   |-- 0027-Add-resolveActivityAsUserForExplicitType-api-to-pm.bulletin.patch
|       |   |   |-- 0028-Do-not-propagate-WIU-BFSL-for-MediaController-sendCommand.bulletin.patch
|       |   |   |-- 0029-Add-WIU-BFSL-allowlisting-to-MediaButtonReceiverHolder-send.bulletin.patch
|       |   |   |-- 0030-Add-flag-to-exclude-capability-propagation-when-connecting-Media.bulletin.patch
|       |   |   |-- 0031-Delete-updateNotificationChannelGroupFromPrivilegedListener.bulletin.patch
|       |   |   |-- 0032-Cap-the-number-of-channels-that-an-NLS-can-create-for-other-pack.bulletin.patch
|       |   |   |-- 0033-Do-not-recycle-Parcel-when-lazy-value-is-used.bulletin.patch
|       |   |   |-- 0034-Limit-usages-sent-to-safety-center-by-user.bulletin.patch
|       |   |   |-- 0035-Remove-exception-for-Q-apps-from-app-op-validation.bulletin.patch
|       |   |   |-- 0036--CDM-Limit-NLS-revoke-to-applicable-roles-.bulletin.patch
|       |   |   |-- 0037-Make-sure-to-disassociate-all-the-packages-with-shared-UID.bulletin.patch
|       |   |   |-- 0038-GRANT-TRUSTED_OVERLAY-after-PiP-is-entered.bulletin.patch
|       |   |   |-- 0039-Validate-IME-metadata-before-parsing.bulletin.patch
|       |   |   |-- 0040-Prevent-accidental-creation-of-PackagePreferences-for-non-existi.bulletin.patch
|       |   |   |-- 0041-Use-ParceledListSlice-to-paginate-response-from-getPackagesForOp.bulletin.patch
|       |   |   |-- 0042-Protect-shell-overriding-the-carrier-config.bulletin.patch
|       |   |   |-- 0043-Disallow-factory-reset-while-in-DSU-mode.bulletin.patch
|       |   |   |-- 0044-Check-length-of-MBR-component-name-properties.bulletin.patch
|       |   |   |-- 0045-Allow-resetting-the-voice-recognition-service-if-its-package-uni.bulletin.patch
|       |   |   |-- 0046-RESTRICT-AUTOMERGE-Backport-Cut-max-duration-for-default-transi.bulletin.patch
|       |   |   |-- 0047-Do-not-use-BIND_INCLUDE_CAPABILITIES-when-bind-PrintService.bulletin.patch
|       |   |   |-- 0048-Add-onKeyEvent-to-support-KEYCODE_HOME.bulletin.patch
|       |   |   |-- 0049-print-Prevent-cross-user-icon-access.bulletin.patch
|       |   |   |-- 0050-Get-all-accounts-no-matter-the-visibility.bulletin.patch
|       |   |   |-- 0051-Enforce-a-hard-limit-for-the-size-of-images-to-be-decoded.bulletin.patch
|       |   |   |-- 0052-Don-t-allow-3p-apps-to-become-voice-recognizer-automatically.bulletin.patch
|       |   |   |-- 0053-Add-missing-import-in-test.bulletin.patch
|       |   |   |-- 0054-Validate-displayName-for-AssociationRequest.bulletin.patch
|       |   |   `-- 0055-Don-t-allow-read-truncation-or-appending-for-file-operations-.bulletin.patch
|       |   |-- native
|       |   |   |-- 0001-Use-BRGA-as-default-format-for-software-rendering.patch
|       |   |   |-- 0002-InputDevice-Use-location-for-idc-file.patch
|       |   |   |-- 0003-Protect-objects-in-Parcel-appendFrom.bulletin.patch
|       |   |   |-- 0004-RPC-Binder-shutdown-on-ENOMEM.bulletin.patch
|       |   |   |-- 0005-RPC-Binder-shutdown-on-SPAN-error-.bulletin.patch
|       |   |   |-- 0006-RPC-Binder-clearer-errors-for-wrong-transact-type.bulletin.patch
|       |   |   |-- 0007-Don-t-blur-too-many-layers.bulletin.patch
|       |   |   |-- 0008-Set-mDataSize-properly-in-appendFrom.bulletin.patch
|       |   |   `-- 0009-RESTRICT-AUTOMERGE-Backport-When-an-opaque-window-has-alpha-0.bulletin.patch
|       |   `-- opt
|       |       |-- net
|       |       |   `-- wifi
|       |       |       `-- 0001-Add-Intel-Wi-Fi-hal.patch
|       |       `-- telephony
|       |           |-- 0001-Remove-get-set-of-voicemail-ringtone-uri-in-shared-preferences-.bulletin.patch
|       |           `-- 0002--Telephony-Security-Fix-Launch-Browser-only-if-device-is-unloc.bulletin.patch
|       |-- hardware
|       |   |-- interfaces
|       |   |   |-- 0001-Enable-AIDL-interface-for-Light-HAL.patch
|       |   |   |-- 0002-Mark-USB-camera-to-back-camera-always.patch
|       |   |   |-- 0003-Change-Lens-Facing-to-External-for-External-Camera-H.patch
|       |   |   |-- 0004-usb-camera-hot-plug-not-working.patch
|       |   |   |-- 0005-Add-support-for-advanced-USB-3.x-based-Cameras.patch
|       |   |   |-- 0006-Add-the-memtrack-AIDL-HAL-implement.patch
|       |   |   |-- 0007-Fix-for-Camera-Issue.patch
|       |   |   `-- 0008-Fix-to-boot-A15-with-Aidl-Gatekeeper.patch
|       |   `-- libhardware
|       |       `-- 0001-Keymaster-Add-new-keymaster-error-code-for-provision.patch
|       |-- packages
|       |   |-- apps
|       |   |   |-- Camera2
|       |   |   |   |-- 01_0001-Changes-to-support-external-camera.patch
|       |   |   |   |-- 02_0002-Audio-source-selectin.patch
|       |   |   |   |-- 03_0003-Captured-image-show-black-in-image-view.patch
|       |   |   |   |-- 04_0004-Handle-WindowInsets-for-Camera2-Settings-Fragment.patch
|       |   |   |   `-- 05_0005-Apply-Window-Insets-for-MainCameraActivity.patch
|       |   |   |-- Car
|       |   |   |   `-- Settings
|       |   |   |       `-- 0001-Show-IP-address-in-car-settings.patch
|       |   |   |-- CertInstaller
|       |   |   |   `-- 0001-Prevent-settings-impostors-from-installing-CA-certs.bulletin.patch
|       |   |   |-- Contacts
|       |   |   |   `-- 0001-Show-account-selection-dialog-when-a-single-account-exists-.bulletin.patch
|       |   |   |-- DocumentsUI
|       |   |   |   `-- 0001-Trim-the-application-name-to-make-it-safe-for-presentation.bulletin.patch
|       |   |   |-- Launcher3
|       |   |   |   `-- 0001-Send-KEYCODE_HOME-for-home-button-instead-of-startActivity-direc.bulletin.patch
|       |   |   `-- Settings
|       |   |       |-- 0001-AppRestrictions-use-vetted-component.bulletin.patch
|       |   |       |-- 0002-Add-ComponentName-explicitly-to-make-sure-arbitary-intents-aren-.bulletin.patch
|       |   |       |-- 0003-Do-not-enable-the-Content-Protection-toggle-for-non-admin-users-.bulletin.patch
|       |   |       |-- 0004-Drop-PendingIntent-extras-from-external-packages-during-enrollme.bulletin.patch
|       |   |       |-- 0005-Use-correct-API-to-get-calling-package-name-in-CredentialStorage.bulletin.patch
|       |   |       |-- 0006-Hide-notification-content-in-history.bulletin.patch
|       |   |       |-- 0007-startActivityForResult-with-earlier-new-Intent.bulletin.patch
|       |   |       |-- 0008-Ignore-face-settings-extras-when-called-by-an-external-package-.bulletin.patch
|       |   |       |-- 0009-Prevent-SettingsSliceProvider-from-accessing-unused-packages.bulletin.patch
|       |   |       |-- 0010-Hide-sensistive-content-from-locked-profiles.bulletin.patch
|       |   |       |-- 0011-Add-check-to-prevent-privilege-escalation-from-trampoline-added-.bulletin.patch
|       |   |       `-- 0012--nfc-Fix-string-injection-in-default-payment-app-selector.bulletin.patch
|       |   |-- modules
|       |   |   |-- Bluetooth
|       |   |   |   |-- 0001-Enable-NBS-as-sco-driver-supports-it.patch
|       |   |   |   |-- 0002-Fix-use-after-free-in-acl_arbiter.bulletin.patch
|       |   |   |   `-- 0003-Remove-flag-btsec_check_valid_discovery_database.bulletin.patch
|       |   |   |-- IntentResolver
|       |   |   |   |-- 0001-Sanitize-cross-profile-intents-.bulletin.patch
|       |   |   |   |-- 0002-Launch-image-editor-as-sharesheet-launching-user-flag-off-.bulletin.patch
|       |   |   |   |-- 0003-Use-the-new-packageManager-API-to-forward-intents.bulletin.patch
|       |   |   |   `-- 0004-Verify-caller-access-rights-for-the-additional-content-URI-.bulletin.patch
|       |   |   |-- NetworkStack
|       |   |   |   `-- 0001-Fix-for-Android-15-Ip-Provisioning-Failure.patch
|       |   |   |-- OnDevicePersonalization
|       |   |   |   `-- 0001-WA-Fix-build-error-in-OnDevicePersonalization.patch
|       |   |   |-- Permission
|       |   |   |   `-- 0001-Stop-one-time-sessions-iff-when-no-one-time-permission-is-grante.bulletin.patch
|       |   |   `-- Wifi
|       |   |       `-- 0001-Do-not-treat-SdkSandBox-as-privileges-App.bulletin.patch
|       |   |-- providers
|       |   |   `-- MediaProvider
|       |   |       |-- 0001-Revert-Fix-kotlinc-2.0-compiler-warnings-and-move-Ph.patch
|       |   |       `-- 0002-Temporary-patch-to-avoid-photopicker-build-error.patch
|       |   `-- services
|       |       |-- Mms
|       |       |   `-- 0001-Verify-calling-user-on-mms-downloads.bulletin.patch
|       |       |-- Telecomm
|       |       |   `-- 0001-Catch-IllegalArgumentException-when-unbinding-CallRedirectionSer.bulletin.patch
|       |       `-- Telephony
|       |           |-- 0002-fix-Use-permission-check-for-contact-URI-validation.bulletin.patch
|       |           |-- 0004-fix-Use-permission-check-for-contact-URI-validation.bulletin.patch
|       |           |-- 0005-Protect-shell-overriding-the-carrier-config.bulletin.patch
|       |           |-- 0006-Restricting-UserBuild-from-presistent-carrierConfig-Override.bulletin.patch
|       |           `-- 03_0003-Fix-for-android.security.cts.CVE_2023_20913-failure.patch
|       |-- prebuilts
|       |   `-- gcc
|       |       `-- linux-x86
|       |           `-- host
|       |               `-- x86_64-linux-glibc2.17-4.8
|       |                   `-- 01_0001-Using-gcc-bin-fron-Android-12.patch
|       |-- system
|       |   |-- apex
|       |   |   |-- 0001-apexd-loosen-no-overlap-check-on-install.bulletin.patch
|       |   |   `-- 0002-New-Patch-Level-for-android-mainline.bulletin.patch
|       |   |-- core
|       |   |   `-- 01_1-Add-support-for-creation-of-usb-pri.patch
|       |   |-- linkerconfig
|       |   |   `-- 01_0001-add-namespace-change-for-houdini.patch
|       |   |-- media
|       |   |   `-- 0001-Increase-period-size-to-improve-USB-Audio-quality.patch
|       |   |-- sepolicy
|       |   |   |-- 06_0006-prebuilt-Allow-adbd-to-use-vsock_socket.patch
|       |   |   |-- 08_0008-Allow-tcp-socket-permission-for-sensor-domain.patch
|       |   |   |-- 09_0009-Fix-Sensor-related-sepolicy-check.patch
|       |   |   |-- 11_0011-Change-the-memtrack-aidl-hal-service-name.patch
|       |   |   `-- 12_0012-Fixed-Sepolicy-Build-Issue.patch
|       |   `-- vold
|       |       `-- 0001-PATCH-WA-CIV-Vold-SD-and-USB-handling-for-CIV.patch
|       `-- test
|           `-- vts-testcase
|               `-- kernel
|                   `-- gki
|                       `-- 0001-Excluding-gki-testcases-for-android_x86-x86_64.patch
|-- autopatch.sh
|-- bsp_diff
|   |-- caas
|   |   |-- device
|   |   |   `-- intel
|   |   |       |-- build
|   |   |       |   |-- 0001-Fix-build-failure-on-Android-13-widevine.patch
|   |   |       |   |-- 0002-Adding-missing-test-keys-needed-for-A15.patch
|   |   |       |   |-- 0003-Update-the-path-to-utils_vertical-folder.patch
|   |   |       |   `-- 0004-Remove-the-host_pkg.patch
|   |   |       |-- common
|   |   |       |   |-- 0001-Add-linux-iotg-lts2024-kernel-headers.patch
|   |   |       |   |-- 0005-Fix-mtl-binary-compilation-dependency.patch
|   |   |       |   `-- 0006-Configure-rro-overlay-for-connectivity-to-address-CT.patch
|   |   |       |-- mixins
|   |   |       |   |-- 0001-include-lts2024-kernel.patch
|   |   |       |   |-- 0002-Add-kernel-config-6.12.63-for-A16.patch
|   |   |       |   |-- 0003-Fix-LTS2024-conflict-issue.patch
|   |   |       |   |-- 0006-PATCH-CIV-Fix-sensor-mediation-hal-reporting.patch
|   |   |       |   |-- 0007-Use-new-exception-OSError-for-qemu6.0-qmp.py.patch
|   |   |       |   |-- 0008-Enable-zram-swap-for-device-having-4G-ram.patch
|   |   |       |   |-- 0009-Add-new-package-names-of-drm-hwcomposer.patch
|   |   |       |   |-- 0009-update-fine-tuned-values-for-performance.patch
|   |   |       |   |-- 0012-Fix-VTS-issue-for-media_codecs-XMLparsing.patch
|   |   |       |   |-- 0013-update-vulkan-hardware-version-xml-file.patch
|   |   |       |   |-- 0018-PATCH-Add-ttyS4-for-TWL-CRB.patch
|   |   |       |   |-- 0019-usb-gadget-WA-to-fix-mount-EP0-race-condition.patch
|   |   |       |   |-- 0021-WA-Force-reboot-type-for-android.patch
|   |   |       |   |-- 0022-Change-hwcomposer3-service-name.patch
|   |   |       |   |-- 0024-update-fine-tuned-values-for-performance.patch
|   |   |       |   |-- 0027-TWL-Enable-TPM-config-by-default-to-y.patch
|   |   |       |   |-- 0029-Update-clang-version-in-kernel-config.patch
|   |   |       |   |-- 0030-Fix-kernel-release-version-error.patch
|   |   |       |   |-- 0031-Update-the-path-to-utils_vertical.patch
|   |   |       |   |-- 0033-Remove-civ-host-vm-manager-repo.patch
|   |   |       |   |-- 0037-Added-passpoint.xml-to-PRODUCT_COPY_FILES.patch
|   |   |       |   |-- 0039-INIT_RC-Set-Verity_update_state-in-boot-flow.patch
|   |   |       |   |-- 0040-Fix-for-GTS-checkGpuProfilingRequirements-TC.patch
|   |   |       |   |-- 0052-Fix-mtl_dmc-compilation-changes.patch
|   |   |       |   `-- 0064-Include-sample_encode-and-sample_decode-as-part-of-b.patch
|   |   |       |-- project-celadon
|   |   |       |   |-- 0002-Include-lts2024-definition-in-mixins.spec.patch
|   |   |       |   |-- 0003-Mixins-update-Use-new-exception-OSError-for-qemu6.0-.patch
|   |   |       |   |-- 0004-Mixins-update-Enable-zram-swap-for-device-having-4G-.patch
|   |   |       |   |-- 0005-CIV-sensor-hal-wo-static-list.patch
|   |   |       |   |-- 0005-Increase-super_partition_size-for-caas-to-6000.patch
|   |   |       |   |-- 0007-Mixins-update-CIV-Fix-sensor-mediation-hal-reporting.patch
|   |   |       |   |-- 0008-set-dwc3-and-console-controller.patch
|   |   |       |   |-- 0009-CTS-Disable-public-library-support-in-mixins.patch
|   |   |       |   |-- 0024-Mixins-update-WA-Force-reboot-type-for-android.patch
|   |   |       |   |-- 0028-Mixins-update-ADL-update-fine-tuned-values-for-perfo.patch
|   |   |       |   |-- 0041-Added-passpoint.xml-to-PRODUCT_COPY_FILES.patch
|   |   |       |   |-- 0043-Mixinup_INIT_RC-Set-Verity_update_state-in-boot-flow.patch
|   |   |       |   |-- 0044-Mixinup-for-fix-GTS-checkGpuProfilingRequirements.patch
|   |   |       |   |-- 0045-Mixinup-Add-mediatranscode-sepolicy.patch
|   |   |       |   |-- 0046-Mixin-up-patch-for-Media-performace-fix.patch
|   |   |       |   |-- 0047-Mixin-update-for-Media-performance-range-for-ww05.patch
|   |   |       |   |-- 0048-Mixin_update-Changed-vulkan-pastel-to-intel.patch
|   |   |       |   |-- 0051-Mixin-update-Configure-rro-overlay.patch
|   |   |       |   `-- 0052-Enable-serial-log-for-RPL-SR.patch
|   |   |       `-- sepolicy
|   |   |           |-- 0001-Add-new-process-name-of-HWC-service.patch
|   |   |           |-- 0001-VTS-fix-added-additional-nodes-for-usb-passthrough.patch
|   |   |           |-- 0002-Enable-zram-swap-for-device-having-4G-ram.patch
|   |   |           |-- 0003-Fix-net-node-permission-for-ADL-PS-Platform-to-pass-.patch
|   |   |           |-- 0005-Added-permission-for-GPU-access-in-dumpstate.patch
|   |   |           `-- 0008-Add-mediatranscode-sepolicy-rules-to-public.patch
|   |   |-- hardware
|   |   |   |-- intel
|   |   |   |   |-- external
|   |   |   |   |   |-- drm-intel
|   |   |   |   |   |   |-- 0004-tests-amdgpu-add-jpeg-tests-support.patch
|   |   |   |   |   |   |-- 0005-meson-use-dictionary-kwargs.patch
|   |   |   |   |   |   |-- 0006-meson-add-override_dependency-when-possible.patch
|   |   |   |   |   |   |-- 0007-releasing-s-master-main.patch
|   |   |   |   |   |   |-- 0008-intel-Add-support-for-ADL-N.patch
|   |   |   |   |   |   |-- 0009-tests-amdgpu-Add-VCN-test-support-for-Biege-Goby.patch
|   |   |   |   |   |   |-- 0010-use-standard-__typeof__-instead-of-GNU-extension-typ.patch
|   |   |   |   |   |   |-- 0011-amdgpu-update_drm.h-for-new-CTX-OP-to-set-get-stable.patch
|   |   |   |   |   |   |-- 0012-amdgpu-implement-new-CTX-OP-to-set-get-stable-pstate.patch
|   |   |   |   |   |   |-- 0013-tests-amdgpu-add-a-test-for-new-CTX-OP-to-get-set-st.patch
|   |   |   |   |   |   |-- 0014-meson-switch-the-meson-builtin-for-symbol-visiblity.patch
|   |   |   |   |   |   |-- 0015-meson-switch-to-cc.get_supported_arguments.patch
|   |   |   |   |   |   |-- 0016-meson-use-more-standard-formatting-for-better-readab.patch
|   |   |   |   |   |   |-- 0017-meson-use-cc.check_header-instead-of-open-coding.patch
|   |   |   |   |   |   |-- 0018-meson-use-cc.has_function_attribute-instead-of-open-.patch
|   |   |   |   |   |   |-- 0019-meson-use-the-modern-interface-for-pkg.generate.patch
|   |   |   |   |   |   |-- 0020-meson-use-summary-instead-of-message.patch
|   |   |   |   |   |   |-- 0021-drm-atomic-Stable-sort-for-atomic-request-de-duplica.patch
|   |   |   |   |   |   `-- 0022-build-bump-version-to-2.4.110.patch
|   |   |   |   |   |-- mesa3d-intel
|   |   |   |   |   |   `-- 0005-Add-missing-ADL-device-ID.patch
|   |   |   |   |   `-- minigbm-intel
|   |   |   |   |       `-- 0001-Add-RPL-S-ID.patch
|   |   |   |   |-- kernelflinger
|   |   |   |   |   |-- 0001-WA-Fixed-build-error-in-kernelflinger.patch
|   |   |   |   |   `-- 0002-WA-Set-device-to-unlocked-state-to-enable-BM-user.patch
|   |   |   |   `-- sensors
|   |   |   |       `-- mediation
|   |   |   |           `-- 0001-CIV-Support-disabling-of-static-sensor-list.patch
|   |   |   `-- interfaces
|   |   |       |-- 0001-Enable-6.12-kernel-support-in-A15-for-FCM.patch
|   |   |       |-- 0002-Enable-USB-recording.patch
|   |   |       |-- 0003-Disbale-stub-HAL-for-audio.patch
|   |   |       |-- 0004-Add-compatibility-for-6.12-kernel.patch
|   |   |       |-- 0005-Enable-primary-audio-with-AIDL.patch
|   |   |       |-- 0006-Fix-audio-crash.patch
|   |   |       |-- 0007-Added-a-fix-for-Audio-server-crash.patch
|   |   |       `-- 0008-Add-implementations-required-to-enable-audio-on-3.5m.patch
|   |   |-- include_common
|   |   |-- kernel
|   |   |   |-- configs
|   |   |   |   |-- 0001-Add-kernel-6.1-support-for-Android-T.patch
|   |   |   |   |-- 0001-Enable-6.12-kernel-support-in-A15.patch
|   |   |   |   `-- 0003-Add-kernel-config-for-w-dessert.patch
|   |   |   `-- linux-intel-lts2024
|   |   |       |-- 02_0002-Add-linux-iotg-lts2024-kernel-headers.patch
|   |   |       `-- 07_0007-iwlwifi-Vendor-command-support-in-iwlwifi-driver.patch
|   |   `-- vendor
|   |       `-- intel
|   |           |-- external
|   |           |   |-- mediasdk_opensource
|   |           |   |   `-- 0001-Fix-clang-error-caused-by-binary_function.patch
|   |           |   |-- onevpl-intel-gpu
|   |           |   |   `-- 0001-Add-missing-ADL-device-IDs.patch
|   |           |   `-- project-celadon
|   |           |       `-- audio
|   |           |           |-- 0001-Add-getCapturePosition-implementation.patch
|   |           |           `-- 0001-Include-header-file-defining-the-PRIu64-macro.patch
|   |           |-- fw
|   |           |   `-- evmm
|   |           |       `-- 0001-WA-EVMM-reset_platform-on-5.15-host-kernel.patch
|   |           |-- hardware
|   |           |   `-- interfaces
|   |           |       `-- 0001-Added-BAD_VALUE-mSensors.size-is-zero.patch
|   |           `-- mediasdk_c2
|   |               |-- 0001-Fix-for-Vts-MultipleStartStopReset.patch
|   |               |-- 0001-Make-c2-service-64bit.patch
|   |               |-- 0006-Revert-Use-VADRMPRIMESurfaceDescriptor-to-create-sur.patch
|   |               |-- 0010-Fixed-a-regression-with-color-aspects.patch
|   |               `-- 0011-Fixed-Swirl-Image-TCs-are-failing-due-to-height.patch
|   |-- common
|   |   |-- .gitkeep
|   |   |-- device
|   |   |   `-- intel
|   |   |       |-- build
|   |   |       |   |-- 0001-Update-the-clang-lib-patch-for-latest-AOSP.patch
|   |   |       |   `-- 0002-imp-library-is-not-supported-on-python-3.12.patch
|   |   |       |-- mixins
|   |   |       |   |-- 0001-Selinux_fc-is-not-used-anymore-to-be-defined-by-Vend.patch
|   |   |       |   |-- 0002-Fix-conflicts-in-config-lts-lts2023-and-lts2024.patch
|   |   |       |   |-- 0003-Update-latest-sepolicy-version-for-new-dessert.patch
|   |   |       |   |-- 0004-WA-Disable-sepolicy-neverallow-check.patch
|   |   |       |   |-- 0005-Mixins-changes-to-enable-wlan-on-IA.patch
|   |   |       |   |-- 0007-Update-the-FIRST-API-level-back-to-35.patch
|   |   |       |   |-- 0007-Update-the-thermal-and-graphics-composer-HAL.patch
|   |   |       |   |-- 0009-Defining-user-is-necessary-for-service-with-latest.patch
|   |   |       |   |-- 0011-Update-the-first-API-level-to-36-for-Beta3.patch
|   |   |       |   |-- 0012-WA-to-allow-prebuilt-libs-with-page-size-4K.patch
|   |   |       |   `-- 0014-Update-the-target-and-sepolicy-version.patch
|   |   |       `-- sepolicy
|   |   |           `-- 0003-Modify-aidl-BT-HAL-service-in-sepolicy.patch
|   |   |-- hardware
|   |   |   `-- intel
|   |   |       |-- external
|   |   |       |   |-- media
|   |   |       |   |   `-- hdcp
|   |   |       |   |       `-- 0001-WA-Fixed-build-error-in-media-deamon.patch
|   |   |       |   `-- minigbm-intel
|   |   |       |       `-- 0001-Changing-the-enum-values.patch
|   |   |       |-- kernelflinger
|   |   |       |   `-- 0001-Changes-in-kernelflinger-for-A16-boot.patch
|   |   |       `-- wlan
|   |   |           `-- libwifihal
|   |   |               `-- open
|   |   |                   `-- 0001-Add-Android.bp-file-to-compile-with-soong.patch
|   |   `-- vendor
|   |       |-- intel
|   |       |   |-- external
|   |       |   |   |-- mediasdk_opensource
|   |       |   |   |   |-- 0001-Adding-definitions-for-A16.patch
|   |       |   |   |   |-- 0002-mem_fun_ref-is-deprecated.patch
|   |       |   |   |   `-- 0003-Add-preprocessor-fix-for-new-clang-build.patch
|   |       |   |   `-- onevpl-intel-gpu
|   |       |   |       `-- 0001-Add-preprocessor-fix-for-new-clang-version.patch
|   |       |   |-- hardware
|   |       |   |   `-- interfaces
|   |       |   |       |-- 0001-Update-the-health-hal-version-dependency.patch
|   |       |   |       |-- 0002-Adding-Missing-power-hal-virtual-functions.patch
|   |       |   |       |-- 0003-Adding-Missing-health-hal-virtual-functions.patch
|   |       |   |       `-- 0004-Update-the-Thermal-HAL-to-version-3-as-per-A16.patch
|   |       |   |-- mediasdk_omx_il
|   |       |   |   `-- 0001-Adding-changes-for-the-new-dessert.patch
|   |       |   `-- tools
|   |       |       `-- peeknpoke-intel
|   |       |           `-- 0001-Removing-redeclaration-of-C-built-in-type-bool.patch
|   |       `-- linux
|   |           `-- firmware
|   |               |-- 0001-Add-SOF-firmware-and-topology-files.patch
|   |               |-- 0002-Add-the-88-ucode-firmware-for-Wi-Fi.patch
|   |               |-- 0003-Update-WLAN-FW-for-AX211-MA-sample.patch
|   |               |-- 0004-dkms-add-dg2-kernel-modules-as-binary.patch
|   |               `-- LICENCE.Intel
|   `-- file_for_flashfile
|-- vendorsetup.sh
`-- x86_64_defconfig

180 directories, 385 files
