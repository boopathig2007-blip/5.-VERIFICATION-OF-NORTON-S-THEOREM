# 5.VERIFICATION-OF-NORTON-S-THEOREM

**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**

**To measure IL**
![ex5](https://github.com/user-attachments/assets/f11bc483-1bc1-4b77-9fcc-bcee1d658dcf)


**To measure RTh or RN**

![ex5a](https://github.com/user-attachments/assets/bfc343be-5ddc-47ba-9865-951f1cc09065)


**To measure IN or Isc**

 ![ex5b](https://github.com/user-attachments/assets/2cc45c1b-d79e-4c3f-a7f3-0a5e337963c2)

**Thevenin’s equivalent circuit**
![ex5c](https://github.com/user-attachments/assets/30054df3-62ce-438e-b5c9-cdcc4ec0e5b2)


**Norton’s equivalent circuit**

![ex5d](https://github.com/user-attachments/assets/7de76ef6-f178-4cad-a029-71ee5c462819)

**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 1**
To measure I L	qwsdgf,./[''
![ex5e](https://github.com/user-attachments/assets/b755f767-33e2-450d-bf0c-bdc6d750bb6d)

Vi (volts)	IL (amps)

**TABULAR COLUMN:2**

To measure RTh or RN
![ex5f](https://github.com/user-attachments/assets/797bf559-ee6f-4ee4-9ca7-ac4679248bcb)

Vi (volts)	RTh (Ω)


**TABULAR COLUMN:3**

To measure IN or Isc
![ex5g](https://github.com/user-attachments/assets/0b486515-75ae-40cc-b4df-99490615f633)

Vi (volts)	IN (amps)
	
**MODEL CALCULATION:**
![ex5h](https://github.com/user-attachments/assets/e57a0dae-dce2-4281-a250-5289a776ba9d)

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**
![ex5i](https://github.com/user-attachments/assets/33832a4e-c616-4dce-8d1d-237bee20aae8)

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
 


**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
