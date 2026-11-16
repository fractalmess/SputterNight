Circuit to drive:
1)  Pivotal and Tylan MFCs
2)  Front panel information display from the MFCs
3)  "Duckbill" illuminated panel switches
5)  Gas valves:
    a)  Roughing isolation
    b)  Turbo isolation
    c)  Gas supply line A
    d)  Gas supply line B
    e)  Process gas inlet
    f)  Chamber vent
    g)  Manometer inlet

Presumed Inputs:
1)  Existing +/- 15V modular power supply
2)  Existing +24V modular power supply

Versions:

20261102:  Initial version which supports 8 illuminated switches which control 8 gas valves,
and drives the Pivotal MFC.  Three MFC controls are supported:  (1) Flow override, (2) flow 
setpoint and (3) flow feedback which is scaled up to +/- 10V for presentation on a panel-
mounted volt meter.  This version uses KiCad 8.0.

20261107:  Included analog support for the Tylan MFC, which is very similar to the Pivotal.
version uses KiCad 10.0.
