### Hardware Setup

- **Sensor Used:** Linear analog Hall-effect sensor  
- **Supply Voltage:** 5V (compatible with ADC range)  
- **Output:** Analog voltage proportional to magnetic field intensity  
- **Magnet:** Neodymium magnet mounted on moving platform  
- **Input Pin on TMS320:** ADCIN3 (mapped to J3.26)  

![image](https://github.com/user-attachments/assets/91ca8396-f56f-4046-90fb-43ca75fadc04)


### Basic Wiring

| Sensor Pin | Connected To              |
|------------|---------------------------|
| VCC        | 3.3V                      |
| GND        | GND                       |
| OUT        | ADCIN3 (GPIO32 / J1.6)    |


![image](https://github.com/user-attachments/assets/95e318fd-8dff-422d-a2bb-10fc6581101b)

![image](https://github.com/user-attachments/assets/448f9cc5-c843-43f6-8aff-1096ccc129a6)


# Build Instructions for TMS320F28379D 

### Requirements

- Code Composer Studio (CCS) v12+
- C2000Ware installed
- Target: TMS320F28379D LaunchPad

### Steps

1. Open CCS and import this project.
2. Ensure you link `C2000Ware` in your project's properties:

![Screenshot 2025-06-12 154853](https://github.com/user-attachments/assets/b9639c03-d400-4df1-a79c-0fc89abe9439)

![image](https://github.com/user-attachments/assets/6acafe46-d9ae-4a99-880c-cf2291f071c6)


