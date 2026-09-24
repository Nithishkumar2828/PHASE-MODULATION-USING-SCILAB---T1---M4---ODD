# PHASE-MODULATION-USING-SCILAB---T1---M4---ODD


## Aim
To implement and analyze Phase Modulation (PM) using Scilab.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
Phase Modulation (PM) is a technique where the phase of the carrier wave is varied in proportion to the instantaneous amplitude of the input signal (message signal). Unlike Frequency Modulation (FM), where the frequency is varied, in Phase Modulation, the phase angle of the carrier wave changes with the amplitude of the message signal.

### Mathematical Representation
The general form of a Phase Modulated signal $s(t)$ is given by:

$$s(t) = A_c \cos(2\pi f_c t + k_p m(t))$$

Where:
* $A_c$ : Amplitude of the carrier wave
* $f_c$ : Carrier frequency
* $m(t)$ : Message signal, typically $m(t) = A_m \cos(2\pi f_m t)$
* $k_p$ : Phase deviation sensitivity (in radians/volt)

---

## Algorithm
1. **Initialize Parameters:**
   * Define carrier amplitude ($A_c$), carrier frequency ($f_c$), message frequency ($f_m$), sampling frequency ($f_s$), and phase sensitivity ($k_p$).
2. **Generate Time Axis:**
   * Create a time array $t$ with suitable sampling steps over the signal duration.
3. **Generate Message Signal:**
   * Compute the message signal vector $m(t)$ using the cosine function.
4. **Generate Carrier Signal:**
   * Compute the unmodulated carrier signal vector $c(t) = A_c \cos(2\pi f_c t)$.
5. **Generate PM Signal:**
   * Compute the phase-modulated signal $s(t) = A_c \cos(2\pi f_c t + k_p m(t))$.
6. **Plot the Signals:**
   * Use Scilab's plotting commands (`subplot`, `plot`, `xtitle`, `xgrid`) to display message, carrier, and modulated signals.

---
## TABULATION

<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 34 46 PM" src="https://github.com/user-attachments/assets/8cdc286e-1003-4679-8cca-be9c021b410b" />

## PROGRAM

<img width="1600" height="1594" alt="WhatsApp Image 2026-09-24 at 3 34 57 PM" src="https://github.com/user-attachments/assets/c04d61ec-bb39-4cf4-a5df-71d5a90a6662" />

<img width="1364" height="1600" alt="WhatsApp Image 2026-09-24 at 3 35 11 PM" src="https://github.com/user-attachments/assets/d22e8b72-bc34-4b0e-9fcd-3176c17688e7" />

## GRAPH
<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 35 15 PM" src="https://github.com/user-attachments/assets/5c8fae8d-c45b-46fd-b42a-1b46b0897fdc" />

## RESULT 

<img width="1599" height="726" alt="WhatsApp Image 2026-09-24 at 3 35 25 PM" src="https://github.com/user-attachments/assets/e759a9ac-9992-4670-a412-694e3b8417a4" />

## MARK ALLOCATION
<img width="1426" height="461" alt="WhatsApp Image 2026-09-24 at 3 35 40 PM" src="https://github.com/user-attachments/assets/bcc20f74-008a-4b43-92d0-db3120249f8f" />



