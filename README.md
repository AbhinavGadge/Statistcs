# Statistcs
Nakagami Distribution
Any signal undergoing multi-path propagation or changing direction at multiple instances during its whole journey can be genarally treated as random walks. The simple examples are ultrasound signal, communication wireless signals , light wave etc. This is more often seen in the backscattered signal. Backscattering is the reflection of a wave (such as a radio wave, light wave, or acoustic wave) off a surface or interface, in the direction opposite to the direction of the incoming wave.

The envelope of received ultrasonic echo is R which follows following ditributions:
Rayleigh Distribution : X , Y are Gaussian distributed. μ = 0, var = equal.
Pre-Rayleigh Distribution : X, Y are not Gaussian distributed. var = high.
Post-Rayleigh / Rician Distribution : X , Y are Gaussian distributed. μ = unequal, var = equal.

To evaluate the characteristics of envelope R with this distributions is complex in terms of computations as well as time consuming. Therefore shankar consolidated this distributions and provided a model Nakagami distribution.

𝑵(𝒓│𝒎,Ω)=(𝟐𝒎^𝒎 𝒓^(𝟐𝒎−𝟏))/(Γ(𝒎) Ω^𝒎 ) 𝒆𝒙𝒑(−𝒎/Ω 𝒓^𝟐 )𝑼(𝒓)

m = shape parameter , Ω = scale parameter




![image](https://user-images.githubusercontent.com/94117639/211752247-9ec81162-de58-4da5-abd0-877550fe0766.png)
