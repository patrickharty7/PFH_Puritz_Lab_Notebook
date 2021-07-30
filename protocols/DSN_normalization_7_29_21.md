---
layout: post
title: DSN_normalization_7_29_21
date: '2021-07-29'
categories: Goals
tags: 
---

7-29-2021
### DSN Normalization

DSN normalization is critical ensuring an even distribution of coverage across probes.  There are a genes that are highly expressed in all cells and DSN normalization helps to remove these high abundance probes and transcripts.  

#### DSN needs to be properly dilued and should be tested for activity levels before proceeding

#### The protocol below was taken from Illumina's recommendations [LINK](https://github.com/MarineEvoEcoLab/EecSeq/blob/master/DSN_Normalization_SamplePrep_Guide_15014673_B.pdf)
#### Reagents

| Reagent| Supplier|
|----------|--------------|
|1 M HEPES buffer solution|Invitrogen, part # 15630‐080 |
|5 M NaCl solution|Ambion, part # AM9760G|
|KAPA HiFi HotStart PCR kit with dNTPs|Kapa, part #KK2502|
|Strip tubes|General lab supplier|
|DSN Kit|Evrogen, part # EA001 Sigma Aldrich, part # E7023|
|Ethanol 200 proof (absolute) for molecular biology (500 ml)|AB, part # 4333764F|
|10X KAPA Library Amplification Primer Mix (Universal primer mix)|Included in KAPA stranded mRNA kit|
|SPRI beads|KAPA Pure Beads, part #KK8000|
|Nuclease-free water|General lab supplier|

#### Equipment
* Thermocycler (2!)
* Magentic stand compatible with strip tubes

#### Procedure

1. First pool individual RNA libraries in equal quantities to create a single pool, we have experimented with 500 ng total or 200ng of each library, the final volume of this should not exceed 13.5 μl. If many probes are desired, multiple probe synthesis reactions can be done, and pooled at the end before hybridization

2. Create a 4X hybridization solution (this amount is excess of what is needed):

|Component|Volume|
|---------|------|
|1 M HEPES buffer solution| 200 𝜇l|
|5 M NaCl solution| 400 𝜇l|
|Nuclease‐free water| 400 𝜇L|
|**Total Volume**|**1000 𝜇**L|

3.  Use two thermocyclers and set one to hold at 68°C
4. Prepare the following reaction mix in a separate, sterile, nuclease‐free 200 μl PCR tube on ice for each pool of cDNA to be normalized. If the pooled cDNA is less than 13.5 μl, increase the volume to 13.5 μl with nuclease free water:

|Component|Volume|
|---------|------|
|Sample library | 13.5 𝜇l|
|4X Hybridization buffer| 4.5 𝜇l|
|**Total Volume Per Sample**|**18 𝜇L**|

5. Gently pipette the entire volume up and down 10 times, then centrifuge briefly to mix
6. Transfer the entire volume of reaction mix directly to the bottom of a new, sterile, nuclease‐free 200 μl PCR tube, using a pipette. Do not let the sample contact the side of the tube during the process
7. Incubate the reaction mix tube on the thermal cycler using the following PCR cycling conditions:

|Step|Temp|Duration|
|----|----|--------|
|Initial denaturation|98 °C|2 min|
|Treatment|68 °C|5 hours|

* **Caution**- Following incubation, keep the thermal cycler lid closed and the temperature held at 68°C. Do not remove the reaction mix tube from thermal cycler prior to and during DSN treatment.
8. Dilute the 10X DSN Master buffer supplied in the DSN kit to 2X with nuclease‐ free water by combining 16 μl nuclease free water and 4 μl 10X DSN master buffer for a total volume of 20 μl
9. Pre‐heat the 2X DSN buffer on the pre‐heated heat block (or another thermocycler) at 68°C
  * **Note:** Do not remove the 2X DSN buffer from the heat block during DSN treatment, pipette from the block or thermocycler
10. Quickly add 20 μl of pre‐heated 2X DSN buffer to the first reaction mix tube
13. With the reaction mix tube remaining within the thermal cycler, gently pipette the entire volume up and down 10 times to mix thoroughly using a pipette set to 40 μl.
  * **Note**:Pipette the solution directly to the bottom of the PCR tube and do not let the sample contact the side of the tube during the process.
  * **Note**: It is important to keep the thermal cycler closed, except for the time necessary to add the 2X DSN buffer and mix. When preparing more than one reaction mix tube, keep the thermal cycler lid closed when extracting the 2X DSN buffer from its tube, then open the thermal cycler lid only for the time necessary to add and mix the 2X DSN buffer.
14. Repeat steps 2 and 3 for each reaction mix tube
15. Incubate the reaction mix tubes on the thermal cycler at 68°C for 10 minutes.
16. Quickly add 2 μl of DSN enzyme to the first reaction mix tube using a 2 μl pipette
17. With the reaction mix tube remaining within the thermal cycler, gently pipette the entire volume up and down 10 times to mix thoroughly using a pipette set to 40 μl
  * **Note**:Pipette the solution directly to the bottom of the PCR tube and do not let the sample get stuck on the side of the tube during the process
18. Repeat steps 6 and 7 for each reaction mix tube
19. Incubate the reaction mix tubes on the thermal cycler at 68°C for 25 minutes
20. Add 40 μl of 2X DSN stop solution (should be thawed but on ice) to each reaction mix tube. Gently pipette the entire volume up and down to mix thoroughly, then place the tubes on ice

---

### Safe Stopping Point
This is a safe stopping point. If you are stopping, store your sample at ‐15° to ‐25°C.

---
### 1.6X Cleanup

1. Bring KAPA Pure Beads to room temperature by taking out of the 4 degree ~30 minutes before use and swirl to mix
2. Perform a 1.6X bead cleanup by adding 128 μl of KAPA Pure Beads to each DSN treated pool
3. Thoroughly resuspend the beads by pipetting up and down multiple times
4. Incubate the plate/tube at room temperature for 15 min to allow the DNA to bind to the beads, if the samples can be placed on an orbital shaker at 200rpm this is ideal
5. Place the plate/tube on a magnet to capture the beads. Incubate until the liquid is clear
6. Carefully remove and discard ~200 μl of supernatant
7. Keeping the plate/tube on the magnet, add 200 μl of 80% ethanol
8. Incubate the plate/tube at room temperature for ≥30 sec.
9. Carefully remove and discard the ethanol
10. Keeping the plate/tube on the magnet, add 200 μl of 80% ethanol
11. Incubate the plate/tube at room temperature for ≥30 sec
12. Carefully remove and discard the ethanol. Try to remove all residual ethanol without disturbing the beads
13. Dry the beads at room temperature, until all of the ethanol has evaporated. **Caution: over-drying the beads may result in dramatic yield loss**
14. Remove the plate/tube from the magnet
15. Thoroughly resuspend the beads in 25 μl of 10 mM Tris-HCl (pH 8.0)
16. Incubate the plate/tube at room temperature for 5 min to allow the DNA to elute off the beads, if the samples can be placed on an orbital shaker at 200rpm this is ideal
17. Place the plate/tube on a magnet to capture the beads. Incubate until the liquid is clear
18. Transfer 24 μl of the clear supernatant to a new plate/tube and proceed to next step

### PCR Enrichment of DSN Normalized Library

1. Create the reaction mix by combining these components on ice _note, if more than 1 DSN normalization took place, you can do multiple enrichments, or you could have combined them before in the cleanup step above and adjusted the cleanup volume_:

|Component|Volume|
|---------|------|
|DSN Treated Library | 30 μl|
|2X KAPA HiFi HotStart ReadyMix| 25 μl|
|10X KAPA Library Amplification Primer Mix| 5 μl|
|**Total Volume per sample**| **50 μl**|

2. Mix well by pipetting up and down several times
3. Amplify the library using the following thermal cycling protocol:

|Step|Temp|Duration|Cycles|
|----|----|--------|------|
|Initial denaturation|98 °C|45 sec|1|
|Denaturation|98 °C|15 sec|12|
|Annealing*|60 °C|30 sec|12|
|Extension|72 °C|30 sec|12|
|Final Extension|72 °C|5 min|1|
|Hold|10 °C | ∞|1|

### 1.6X Cleanup of DSN Treated and Amplified Pooled cDNA

1. Bring KAPA Pure Beads to room temperature by taking out of the 4 degree ~30 minutes before use and swirl to mix
2. Perform a 1.6X bead cleanup by adding 80 μl of KAPA Pure Beads to each DSN treated pool
3. Thoroughly resuspend the beads by pipetting up and down multiple times
5. Incubate the plate/tube at room temperature for 15 min to allow the DNA to bind to the beads, if the samples can be placed on an orbital shaker at 200rpm this is ideal
6. Place the plate/tube on a magnet to capture the beads Incubate until the liquid is clear
7. Carefully remove and discard 115 μl of supernatant
8. Keeping the plate/tube on the magnet, add 200 μl of 80% ethanol
9. Incubate the plate/tube at room temperature for ≥30 sec
10. Carefully remove and discard the ethanol
11. Keeping the plate/tube on the magnet, add 200 μl of 80% ethanol
12. Incubate the plate/tube at room temperature for ≥30 sec
13. Carefully remove and discard the ethanol. Try to remove all residual ethanol without disturbing the beads
14. Dry the beads at room temperature, until all of the ethanol has evaporated. **Caution: over-drying the beads may result in dramatic yield loss**
15. Remove the plate/tube from the magnet
16. Thoroughly resuspend the beads in 22 μl of 10 mM Tris-HCl (pH 8.0)
17. Incubate the plate/tube at room temperature for 5 min to allow the DNA to elute off the beads, if the samples can be placed on an orbital shaker at 200rpm this is ideal
18. Place the plate/tube on a magnet to capture the beads. Incubate until the liquid is clear
19. Transfer 22 μl of the clear supernatant to a new plate/tube and proceed to next step

## Quant DSN Treated and Amplified Pooled cDNA
**Procedure (Standard HS DNA protocol)**
1. Set up the required number of 0.5-mL tubes for standards and samples. The Qubit® RNA HS Assay requires 2 standards
2. Label the tube lids
3. Prepare the Qubit® working solution by diluting the Qubit® DNA HS Reagent 1:200 in Qubit® DNA HS Buffer. Use a clean plastic tube each time you prepare Qubit® working solution. **Do not mix the working solution in a glass container**
4. Add 190 μL of Qubit® working solution to each of the tubes used for standards
5. Add 10 μL of each Qubit® standard to the appropriate tube, then mix by vortexing 2–3 seconds. Be careful not to create bubbles
6. Add Qubit® working solution to individual assay tubes so that the final volume in each tube after adding sample is 200 μL (we use 199μL solution to 1 μL sample)
7. Add each sample to the assay tubes containing the correct volume of Qubit® working solution, then mix by vortexing 2–3 seconds. The final volume in each tube should be 200 μL
8. Allow all tubes to incubate at room temperature for 2 minutes
9. On the Home screen of the Qubit® 3.0 Fluorometer, press DNA, then select DNA: High Sensitivity as the assay type. The “Read standards” screen is displayed. Press Read Standards to proceed
10. Insert the tube containing Standard #1 into the sample chamber, close the lid, then press Read standard. When the reading is complete (~3 seconds), remove Standard #1
11. Insert the tube containing Standard #2 into the sample chamber, close the lid, then press Read standard. When the reading is complete, remove Standard #2
12. Press Run samples
13. On the assay screen, select the sample volume and units
14. Insert a sample tube into the sample chamber, close the lid, then press Read tube. When the reading is complete (~3 seconds), remove the sample tube
15. Repeat step last step until all samples have been read

---

## If you want to sequence the probes you can split finished DSN treated cDNA Pools
* One tube for sequencing
* One tube for probe synthesis

#### Note that this step is optional as sequening the probes directly is not necessary for exome capture analysis.  Alternatively, a portion of the mRNA library can be saved before DSN normalization for sequencing. After this step the adapters are taken off the libraries, so they cannot be read on a sequencer anymore.

---

### Safe Stopping Point
This is a safe stopping point. If you are stopping, store your sample at ‐15° to ‐25°C.

---