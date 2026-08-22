### Procedure

* Seed an appropriate number of cells in the 96-well round-bottom plate.
* After 12 hours, prepare 10-fold serial dilutions of the virus (e.g., $10^{-1}$ to $10^{-8}$).
* Add 900 µL of serum-free medium to each tube.
* Add 100 µL of virus stock to the first tube to make a $10^{-1}$ dilution.
* Mix well, then transfer 100 µL from this tube to the next to prepare further serial dilutions.
* Remove growth medium from the wells and add a fixed volume (e.g., 100 µL) of each virus dilution to multiple replicate wells, usually 3-4.
* Incubate the plate for 72 hours at 37 °C with 5% CO₂.
* Observe the cells for cytopathic effects (CPE) and record the number of CPE-positive and CPE-negative wells for each dilution [2].

#### Calculation of TCID₅₀ by Reed–Muench Method

##### Example Data
| Virus Dilution | No. of wells infected (CPE +) / Total wells |
| :---: | :---: |
| $10^{-3}$ | 4/4 (100%) |
| $10^{-4}$ | 3/4 (75%) |
| $10^{-5}$ | 2/4 (50%) |
| $10^{-6}$ | 1/4 (25%) |
| $10^{-7}$ | 0/4 (0%) |

##### Steps for Reed–Muench Calculation
1. **Identify the dilution where percentage positive is just above 50%**
   * $10^{-4}$ ($75\%$)

2. **Identify the dilution where percentage positive is just below 50%**
   * $10^{-6}$ ($25\%$)

3. **Calculate the Proportionate Distance (PD)**
   $$\text{PD} = \frac{\% \text{ positive above } 50 - 50}{\% \text{ positive above } 50 - \% \text{ positive below } 50}$$

   $$\text{PD} = \frac{75 - 50}{75 - 25} = \frac{25}{50} = 0.5$$

4. **Calculate TCID₅₀ dilution**
   $$\log_{10}(\text{TCID}_{50} \text{ endpoint}) = \log_{10}(\text{dilution above } 50\%) + (\text{PD} \times \log_{10}(\text{dilution factor}))$$

   $$\log_{10}(\text{TCID}_{50} \text{ endpoint}) = \log_{10}(10^{-4}) + (0.5 \times 1)$$

   $$\log_{10}(\text{TCID}_{50} \text{ endpoint}) = -4 + 0.5 = -3.5$$

##### Final Result
- **TCID₅₀ endpoint** = $10^{-3.5}$ per inoculation volume

If $0.1\text{ mL}$ of virus was inoculated per well:
$$\text{TCID}_{50}/\text{mL} = 10^{-3.5 + 1} = 10^{-2.5}$$

Alternatively expressed as:
$$\text{TCID}_{50}/\text{mL} = 10^{2.5} \approx 316 \text{ TCID}_{50}/\text{mL}$$

<iframe width="315" height="560" src="https://www.youtube.com/embed/-KfOVTUFGd4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="max-width: 100%; display: block; margin: 20px auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);"></iframe>