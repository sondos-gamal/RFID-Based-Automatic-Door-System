# RFID-Based-Automatic-Door-System
>A system used to control the movement of a door without the use of a key to solve 
>security problems associated with mechanical locks



We used RFID ID tag and RFID reader , which is used to match the data on tag with the data in the database program which leads to movement of door by confirming whether the data is correct and/or incorrect.

Opening of the door uses servo motor that gets its feed from Arduino board. The opening and closing is based on the flag set by the Arduino response. When the flag is set to 1, the door opens and if it is set to 0, the door remains closed. The LED based on the feed also comes from the Arduino board.

# COMPONENTS AND SUPPLIES

• Arduino UNO

• RFID RC522 HF

• Adafruit Standard LCD -16*2 white on blue

• Servos (Tower pro MG996R)

• RGB LED

• Buzzer

• Resistor 220 ohm

• Breadboard (generic)

• Jumper wires(generic)


# SCHEMATICS

![image](https://github.com/sondos-gamal/RFID-Based-Automatic-Door-System/assets/78621105/b1817bea-0bcc-45c2-99a3-7cd0c25aa10e)

![image](https://github.com/sondos-gamal/RFID-Based-Automatic-Door-System/assets/78621105/3765e1d5-22b4-473c-91f6-9b059d7f30c5)

![image](https://github.com/sondos-gamal/RFID-Based-Automatic-Door-System/assets/78621105/e9bb0c10-a05f-48d3-a3ed-d19f457b7c31)


## RFID Based Automatic Door System

RFID locking systems are contactless, meaning that the credential doesn’t have to touch the reader for it to work. RFID readers work by sending and receiving data,the data is transmitted over radio frequencies. An RFID door locking system requires RFID tags,antennas, an RFID reader, and a transceiver inorder to function as a complete system.

the user’s credential (usually a keycard or fob with an RFIDchip) contains unique identifying information called a tag. When the user comes within proximity of a reader, the reader’s signal locates the information stored on the user’s RFID tag and sends it through antennas and transceivers to authorize the tag in the access control system. Once read, the system will either accept or deny the request to unlock the door. the system will either accept or deny the request to unlock the door. Data from an RFID-enabled system is automatically stored, making it possible to track entry activity in an access control system
