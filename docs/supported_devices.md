# Supported devices

Support new devices: [contribute/porting.md](/docs/contribute/porting.md)  

### Quick-picks
- **modules:** AVATTO, Aubess, iHseno
- **switches:** Moes 1-3gang (any design)

### Careful with
- generic 1-gang modules - might not support OTA conversion
- BSEED switches - too many variants (can't know which you'll receive)

### Legend

| Symbol | Meaning  |                    |                     |                |                |          |
| :----: | -------- | ------------------ | ------------------- | -------------- | -------------- | -------- |
|   🚧️   | Status   | 🟩️ Fully supported | 🟨️ Mostly supported | 🟧️ In progress | 🟥️ Unsupported |          |
|   📦️   | Build    | ✔️ Available       | ❌️ Unavailable      |                |                |          |
|   💡️   | Category | 🇲️ Module          | 🇸️ Switch           | 🇴️ Outlet      | 🇷️ Remote      | 🇧️ Board |
|   ⚡️   | Power    | 🔌️ Mains           | 🔋️ Battery          | 🔱️ USB         |                |          |
|   📲️   | Install  | 🛜️ Wireless        | ➿️ By wire          | ❓️ Unknown     |                |          |
|   🏭️   | MCU      | `TL` Telink        | `SL` Silicon Labs   | `NXP` NXP      |                |          |
|   🅰   | Variant  | 🅰                  | 🅱                  | 🅲             | 🅳              | 🅴       |

<!-------------------------------------------------------------------
  `supported.md` is generated. 
  
  Do not edit it directly! Instead, edit:
  - `device_db.yaml`             - add or edit devices
  - `supported_devices.md.jinja` - update the template
  - `make_supported_devices.py`  - update generation script

  Generate with: `make tools/update_supported_devices`
-------------------------------------------------------------------->

> [!IMPORTANT]  
> Identify your device by **Zigbee Manufacturer** and linked threads/stores!  
> *Z2M pages are sometimes generic.*

### Device list

| 🚧 | 📦 | 💡 | ⚡️ | 📲 |  🏭  | Zb&nbsp;Manufacturer <br> Zb&nbsp;Model | Name <br> Z2M&nbsp;page&nbsp;🔗 | Store | Threads | Status |
| -- | -- | -- | -- | -- | :--: | :-------------------------------------- | :------------------------------ | ----: | ------: | :----- |
| 🟧 | ✔️ | 🇴 | 🔌 | 🛜 | **TL** | `_TZ3000_gvn91tmx` <br> `TS011F` | [AUBESS PM outlet](https://www.zigbee2mqtt.io/devices/TS011F_plug_1_2.html) |   |   | PM not implemented | 

Data from [`device_db.yaml`](/device_db.yaml)
