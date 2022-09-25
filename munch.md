# Flashing Instructions for POCO F4 / Redmi K40s (munch)

## Notes
- Do not flash gapps, already included in catalyst
- Safetynet is always passed, no need to do anything

## Instructions for new users -
1. Have unlocked bootloader
2. Be on latest miui global firmware
3. reboot to fastboot mode
4. fastboot flash boot boot.img
5. fastboot flash vendor_boot vendor_boot.img
6. reboot to recovery now
7. wipe data because you are changing rom
8. select adb sideload
9. adb sideload CatalystOS-xxxxxxx.zip

## Instructions to update for existing users -
1. Just install OTA update
2. OR just sideload latest build from recovery
