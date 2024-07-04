# Aliro Test Harness Additions

This repo contains the UWB and BLE specific binaries required for the Aliro Test Harness.

## Contents

- [Murata device FW binary](uwb_ble_device_fw-v05.00.00.bin) - FW binary to be downloaded on the **Murata Type 2BP EVK Rev4.1** board. 
  This binary listens to UWB and BLE commands sent over UART and performs the appropriate action.

- [SR150 UWB FW binary](ALIRO_IOT_SR150_FW_v46.42.01.bin) - UWB FW binary to be downloaded to **SR150** UWB module

- [UCI Tool package](ucitool-2.0.1-py3-none-any.whl) - Python package which provides communication access to Murata device binary through UART
  and supports UWB commands
