# The JankWheel
### Affordable DIY sim racing wheel + pedals



<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/0e854361-b1cb-41f8-b3a4-bf377db4d847" width="400" height="300" style="object-fit: cover;"></td>
    <td><img src="https://github.com/user-attachments/assets/bc3a2da3-172f-4642-bec8-ea68f714ef6a" width="400" height="300" style="object-fit: cover;"></td>
    <td><img src="https://github.com/user-attachments/assets/e2637b34-727d-4363-9bcd-93c143812c7c" width="400" height="300" style="object-fit: cover;"></td>



  </tr>
</table>
<br>

# What will this project include?

- [ ] Custom firmware to control the motor + read pedal data (with gui)
- [x] All CAD files used to create the JankWheel
- [x] All GERBER files used to create the JankWheelPCB 
- [ ] Step-by-step instructions

# How does it work?

1. The **wheel ESP32** acts as an USB HID device connected to the PC and fetches data from the racing simulator
2. It processes this data and sends torque information to the motor controller (FOC). This generates the force feedback.
3. The **pedal ESP32** sends hall effect sensor data to the **wheel ESP32** via UART (carried through an Ethernet cable)
4. The **wheel ESP32** sends all this data back to the computer and interacts with the simulator


# 🧩 Cad Links (Onshape)


<a href="https://cad.onshape.com/documents/801918117367e1510024d274/w/b760bfe1f718564b3afe7bc0/e/a17cc89e60c8d7dd4e027ee4?renderMode=0&uiState=6a03b4db2263794b42f01eec" style="text-decoration: none;">

  <span style="
    display: inline-flex;
    align-items: center;
    gap: 10px;
    padding: 8px 14px;
    border: 1px solid #d0d7de;
    border-radius: 10px;
    background: #f6f8fa;
    font-weight: 500;
    color: #24292f;
  ">
    <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/onshape.png"
         style="width: 22px; height: 22px;">
    Wheel
  </span>

</a>

<br>

<a href="https://cad.onshape.com/documents/e8e69e42e5c323be1d96a543/w/896691ed5701e6087a640bb3/e/1a314bb926fcceda2337b473?renderMode=0&uiState=6a03b50272a97adea0f72792" style="text-decoration: none;">
  <span style="
    display: inline-flex;
    align-items: center;
    gap: 10px;
    padding: 8px 14px;
    border: 1px solid #d0d7de;
    border-radius: 10px;
    background: #f6f8fa;
    font-weight: 500;
    color: #24292f;
  ">
    <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/onshape.png"
         style="width: 22px; height: 22px;">
    Pedals
  </span>
</a>

<br>


