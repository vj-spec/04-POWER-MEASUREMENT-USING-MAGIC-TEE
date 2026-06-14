# 04-POWER-MEASUREMENT-USING-MAGIC-TEE

# A.Aim:

To measure isolation between E and Harms of the magic tee and Demonstrate 3 dB powerdivision in the arm of magic tree.

# B.Apparatus Used:

Klystron power supply, Klystron Mount, Isolator, Attenuator, Frequency meter, VSWR meter,magic tee and matched terminations.

# C.Experimental Setup:

<img width="701" height="358" alt="image" src="https://github.com/user-attachments/assets/8619d64e-d78f-49e2-b0f8-2e2dc038f6c9" />

# D.Theory:

A four port junction which is a combination of an E-plane and H-plane tee is called Hybrid Tee.When matched elements are introduced to reduce the reflections, it is called a magic Tee.
It has four arms or ports which have the names indicated in figure 9.

<img width="288" height="232" alt="image" src="https://github.com/user-attachments/assets/826d1e4f-cdf8-496a-b571-a34130bcd30b" />

The arm which makes an H-plane tee with the collinear arm is called H-arm or Shunt arm. The fourth arm which makes E-plane tee with the collinear arms is called E- arm or series arm. The shunt and series arms are polarized. i.e. the voltage vectors in these two arms are perpendicular toeach other. Therefore as long as there is nothing within the junction to rotate
the polarization, there can be no coupling between the two arms. The E and H arms are matched byemploying posts and irises to minimize reflections from these two ports.
The magic associated with the hybrid junction is the way in which the power is divided in the various arms. The signal fed into the shunt or H-arms divides its ~ If equally and in phase in the twoside arms with no coupling in E-arm. When the signal is fed into the series or E-arm it also divides itself equally in the two arms, but this time two halves are 180o out of phase ad there is no coupling to the H-arm. If the power is fed into one of the arms, it divides equally in the shunt and series arm and there is no coupling in the other side arm. That is to finally that in a magic tee, opposite arms are isolated.
A magic tee can also be used as a signal combiner. If the signals are fed to both the side arms, theywill combine in phase in H-arm and 180o out of phase in E-arm.

# A magic tee is normally characterized by two quantities:

1.	Isolation between E and H arms
2.	Power division in collinear arms

# Isolation between E and H arms

If the power flowing into E arm is taken as PE and power flowing out of H-arm as PH thenIsolation(dB) = -10 log10 PH/ PE This assumes that both the collinear arms are match terminated.



# Power division

The power fed in either the E or H arm should divide itself equally in both the side arms, when the opposite port is match terminated. If we designate the power entering the E arm as PE and power in side arms as PC1 and PC2 then the ratio of the power coupled in side arms to that entering inthe E-arm is given by the relation.
Coupling (dB) = 10 log10 PC1/ PH = -10 log10 PC2/ PH.

# E.Procedure: General

1.	Set up the equipment as shown in fig 9a.
2.	Keep the control knobs of Klystron Power Supply as belowMode Switch	: AM
    Beam Voltage Knob : Fully Anti Clockwise
    Repeller Voltage Knob	: Fully Clockwise Meter Switch	: Cathode Voltage Position
3.	Measurement or isolation between E and H arms
    3.1	Set the attenuator around 20dB. Let this setting be (A1) dB
    3.2	Achieve a state reference reading on the SWR meter, preferably in 40dB range of theSWR meter
    3.3	Disconnect and setup as shown in fig 9b
    3.4	Reduce the attenuation till the SWR meter reads the value obtained in step 3.2 notethe attenuation setting (A2) dB. The difference in the attenuator setting (A1-A2) dB gives the isolation in dB.
4.	Experimental setup for demonstrating the 3 dB power division in the collinear arms.
    4.1	Now the power input be either E or H arms.
    4.2	Set the attenuator to get reference reading on SWR meter without the componentunder test. Note the attenuator setting (A1) dB
    4.3	Connect the component under test(Magic tee)
    4.4	Reduce the attenuation to get the reference reading obtained in step 4.2
    4.5	Note down the attenuator setting (A2) dB

The difference in the attenuator settings gives the ration of the
power coupled to thecollinear to that in the main arm, in dB. This value is around 3dB.

**F.	Observation: 



# Isolation measurement 

<img width="1076" height="204" alt="image" src="https://github.com/user-attachments/assets/55243931-1e61-4086-a239-10e380280b0b" />



# Measurement of power division

<img width="1080" height="224" alt="image" src="https://github.com/user-attachments/assets/1d004d4b-8bfa-46d1-b4fe-e511012f75e7" />



# G.Analysis of Results: 

Isolation = A₁ − A₂ = 20.0 − 1.0 = 19.0 dB. Interpretation: only ~1/79 of the power fed into the E-arm appears at the H-arm (good isolation). Power division (coupling to collinear arm) = A₁ − A₂ = 20.0 − 17.0 = 3.0 dB. Interpretation: input power splits equally between the two collinear arms (each receives ≈ half the power).

# H.Conclusions: 

Isolation between E and H arms (dB) = (A1 – A2) dB
Coupling between collinear arms and E/H arms (dB) = (A1 – A2) dB

# Precautions:

•	Check the connections before switching on the kit.
•	Connections should be done properly.
•	Observation should be taken properly.

# Result:
Isolation between E and H arms ≈ 19 dB,

power division in the collinear arms ≈ 3 dB (equal split).

Thus, the experiment executed successfully.
