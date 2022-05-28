# POWER ELECTRONICS
In this repo, I will put some *SIMULINK* files to implement some of the ***Power Electronics Circuits*** and I will explain some of them in this readme file

------------------------------------------
## **AC Voltage Control**
- it's about controlling the **RMS value** of voltage by controlling ***trigger angle(α)*** of thyristor
- their are two types of AC voltage control:
    - ON/OFF control (Integral Cycle Control) <!-- 4 spaces for nested list -->
    - Phase angle control

###  **1. ON/OFF control**
- it's used in apps which have high mechanical inertia and high thermal time constant like ***"Industrial heating and speed control of ac motors"*** due to ***ZVS*** and ***ZCS***


###  **2. Phase Angle Control**
- it divides to two types:
    - Half wave control
    - Full wave control

#### **Half wave**
- it consists of one thyristor for forward biased and one diode for reversed biased
- it gives us control over the first half cycle 
- drawbacks:
    - more DC component
    - control over the first half cycle only
    - control over 100% V<sub>s</sub> to 70.7% V<sub>s</sub> only
