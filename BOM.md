# General Component List

- **RX5808**: 5.8GHz receiver. Needs to have the SPI mod in order to be SPI-controllable
- **SMA connector**:
  - **RP SMA** = reverse polarity. The polarity of the antenna connector and the PCB connector just need to be opposite
- **MCU**: Anything works; I'm using an XIAO RP2040
- **Antenna**: Has to be 5.8GHz. The drone antenna is a dipole, so the circular one I have now isn't perfect. 
- **Video Out**: TBD. Ideally I would have a capture circuit on the PCB but that may be too difficult

# BOM

| Name | Quantity | Link | Total Price |
| - | - | - | - |
| SMA Connector | 1 | [AliExpress](https://www.aliexpress.com/item/3256804056009500.html) | $1.39 |
| 5.8GHz RHCP Antenna | 1 | [AliExpress](https://www.aliexpress.com/item/3256803558054206.html) | $4.34 |
| RX5808 5.8GHz receiver module | 1 | [AliExpress](https://www.aliexpress.com/item/3256808477588223.html) | $23.01 |
