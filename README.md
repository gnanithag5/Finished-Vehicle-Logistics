# Finished-Vehicle-Logistics

## **Overview**

Efficient vehicle logistics management is vital in auto manufacturing plants to streamline operations and reduce resource waste. However, locating vehicles in large holdings is challenging due to constant inventory movement and the lack of systematic tracking. To address this, an IoT solution was developed to help employees quickly identify vehicle locations, enhancing efficiency. After evaluating cutting-edge technologies, including Bluetooth Low Energy (BLE) and RFID with Real-Time Location Systems (RTLS), the RFID-RTLS solution was chosen for its superior range, readability, and scalability.

## **Code**

The code has 4 modules primarily,

**Module 1: Generating RFID Readings**
- Simulates RFID tag readings with unique tag IDs.
- Assigns timestamps in a specified timezone.
- Creates parking logs with manufacturing dates and parking statuses.

**Module 2: Estimating RFID Tag Location Using DOA**
- Estimates the Cartesian location of RFID tags based on DOA (Direction of Arrival) angles.
- Converts angles from degrees to radians and calculates positions.
- Constrains tag locations within specified warehouse dimensions.

**Module 3: Managing a Parking Lot System**
- Handles parking space allocation dynamically based on availability.
- Maintains a parking log table with car IDs and assigned spaces.
- Visualizes the parking lot layout using a grid representation.

**Module 4: Advanced Parking Visualization**
- Visualizes a parking lot with detailed dimensions and sections.
- Highlights inner and outer boundaries of the parking area.
- Displays rows and columns in grid format for better understanding of the layout.
