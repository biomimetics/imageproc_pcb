ImageProc 2.5 Errata

=Revision C=


=Revision B=
* SCL1 and SDA1 are transposed on the dsPIC33 footprint

=Revision A=

*V_batt plane connecting to the vregs.

Symptom:
The voltage regulators do not draw power from the battery

Reason:
The V_batt source does not connect to the portion of the V_batt plane that the voltage regulators draw power from. This occurs because the V_batt plane was cut off due to the vias that power IC7. This connection is made in Eagle, but the gerbers that the manufactuer uses exlucded the connection.

Short term resolution: Airwire between one of the three isolated vias (one each for the two vregs, one for the top H-bridge chip), and a portion of v_batt that is connected (typically, the other v_batt via for IC7).

Long Term Resoultion: Re-route those two wires that are cutting the majority of the plane off.

* Programming Connector pinouts

Symptom: The dsPIC cannot be programmed with legacy programming adaptors

Reason: The programming connector does not have the same pinouts as the programming connector on ImageProc 2.4

Short Term Resolution: Plug in the prog connector with the cable, and ensure that the cable is upside down on the connector. Then, before the final connector interfaces with the pic kit, use male-female wires to rearrange the pins to the correct orientation.

Long Term Resolution: re-do the connector on the schematic and board files.

* IC7 ground pin

Symptom: IC7, one of the two motor controllers, does not work.

Reason: One of its three ground pins, specifically, pin 11, is soldered to a pad that is in fact not connected with ground.

Short Term Resolution: Airwire between than pad and a source of ground.

Long Term Resoultion: A new route that connects ground.

* C40 and C37 mix-up

Symptom: C40, the bypass capacator for the flash mem, and C37, the bypass capacator for the IMU, have been mislabled as eachother.

Short Term resolution: Populate both C37 and C40.  Both C37 and C40 have the same value.

Long Term: Re-lable the eagle file.
