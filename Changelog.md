
# Changelog

## 01.04.00
- UWB SR150 FW updated (v46.43.14)
- Round index computation bugfix. 

  NOTE - this may cause ranging timeout when used against an old FW.
  User should upgrade to latest FW on both controller and controlee devices

- License updated

## 01.03.02
- UWB SR150 FW updated (v46.43.A3) with CSA OUI support and blockIndex value in ranging notification

## 01.03.01
- ucitool update (v02.00.04) to support secure ranging with dynamic STS
- Added new API set_wrapped_rds to inject derived URSK
- Changed session type from SESSION_CCC to SESSION_CSA

## 01.03.00
- ucitool updated to v02.00.03
- Murata FW update
- Firmware for Murata board is updated to support 2M PHY on BLE

## 01.02.00
- UWB SR150 firmware updated to v46.42.02

## 01.01.00
- Updated ucitool (v02.00.02)
- Bugfixes in ucitool

## 01.00.00
- FW binaries for Aliro Test Harness
- Added Murata device FW binary (v05.00.00) which provides access to UWB and BLE
- Added SR150 FW binary (v46.42.01) for UWB
- Added ucitool wheel package (v02.00.01) to be used with Test Harness and provides UCI interface and UART communication interface
