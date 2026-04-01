# EDC Blink Code Diagnostics

**Source:** Screenshot from documentation (Screenshot 2024-11-15 at 11.46.29.png)

The Iveco 8140.43P engine uses an EDC (Electronic Diesel Control) system that communicates fault codes via a blink-code system using the EDC warning light on the dashboard.

## Reading Blink Codes

1. Turn the ignition **OFF**
2. Press the diagnosis button
3. Two series of EDC warning light flashes, separated by a brief pause, indicate the code of the first error memorized
4. Press the button again to move on to the next error
5. When the last error is reached, the first is repeated
6. The error list contains **all memorized errors**, not just the active ones
7. The order of error presentation follows the **chronological order** in which they occurred

## Clearing Error Codes

To erase the list of errors from the control board memory:

1. With the ignition **OFF**, press the diagnosis button
2. With the button still depressed, turn **ON** the ignition
3. Keep the button depressed for **5 seconds**
4. Release the button
5. Switch off the ignition

## Notes
- The diagnosis button location should be referenced in the Service Manual Section 8 (Body Electrical System)
- Error codes consist of two flash sequences: first sequence = tens digit, second sequence = units digit (e.g., 2 flashes + 3 flashes = code 23)
- A complete list of EDC error codes for the 8140.43P engine would be found in Iveco documentation
