How does the program work?
1. User Input:
The flexible pavement design tool initiates by prompting the user to enter crucial information:
•	Type of axle
•	Assumed Structural Number (SN)
•	Quantity of loads
•	Magnitude of load

These inputs guide the tool through the design process.

2. W18 Design Calculation:
The program utilizes tables provided in Excel to match the magnitude of the load and the assumed SN. It calculates the "W18 Design" based on these inputs. In case the magnitude of loads is an odd number, the program performs interpolation to find the corresponding "W18 Design."

3. W18 Calculated Calculation:
Next, the user provides additional inputs such as Reliability (R), Standard Deviation (So), Subgrade Resilient Modulus (MR), Initial Serviceability (PSI), and Terminal Serviceability (TSI). The program uses these values to calculate "W18 Calculated" for various SNs.

4. SN Determination:
The tool iteratively compares the calculated "W18" values with the "W18 Design" until a match is found. This determines the correct Structural Number (SN) for the given inputs.


5. Desired D Calculation:
Once the SN is determined, the user specifies the type of wearing surface, subbase, and base, and enters the values of M2 and M3. The program uses the formula SN=a1D1+a2D2M2+a3D3M3, where the user chooses the known Ds. The tool then calculates and rounds up the desired D to the nearest 0.5 inch.

6. Results Display:
Finally, the tool displays the determined SN and corresponding desired D value. Users can review the results to ensure that the pavement design meets their specifications.
Through these steps, the flexible pavement design tool provides a systematic and user-friendly approach to calculate critical design parameters for flexible pavements according to AASHTO procedures.
