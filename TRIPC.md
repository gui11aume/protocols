4C on barcoded kc167 cells
==========================

_Adapted from Stadhouders et al. (Nature protocols, 2013) by Arantxa Rosado._

1. I take 10M cells at 1M/ml density in 10 ml.
1. Add 0.275 ml (1% final) of 37% formaldehyde per 10 ml suspension.
1. Incubate for 10 min. at room temperature (RT) under rotation.
1. To 10 ml of cell suspension + formaldehyde, add 0.60 ml of a 2.5 M Glycin stock (Glycine stocks are prepared in MilliQ, filtered and stored for max. 1 month at RT).
1. Incubate for 5 min at RT under rotation.
1. Fixed cells are transferred to ice and kept cold from now on.
1. Pellet the cells at 300 g for 5 min at 4C.
1. Discard all the supernatant and resuspend pellet in cold PBS (1ml/5-million cells). Transfer to 1.5 ml safe-lock tubes.
1. Pellet the cells at 300 g for 5 min at 4C, discard supernatant.  
   _Optional: At this point cells might be store by  snap-freezing the pellets in liquid nitrogen. Store at -80C._
1. Gently resuspend the cell pellet in 0.25 ml freshly prepared ice-cold Hi-C lysis buffer:
1. To prepare 5 ml of Hi-C lysis buffer combine:
 * 50 ul 1M Tris-HCl pH8.0
 * 10 ul 5M NaCl
 * 100 ul 10% Igepal CA630
 * 100 ul 50x Roche complete protease inhibitors (in PBS or MilliQ)
 * 4.74 ml MilliQ water
1. Incubate the cells for at least 15 min on ice.
1. Centrifuge at 1000 g for 5 min at 4C.
1. Wash pelleted nuclei with 500 ul cold  lysis buffer.
1. Gently resuspend pellet in 50 ul of 0.5% SDS in 1x NEB2 buffer (5 ul 10x CutSmart buffer + 42.5 ul nuclease-free water + 2.5 ul 10% SDS) and incubate at 62C for 10 min.
1. Remove tubes from the heating block, add 170 ul of 1x CutSmart buffer containing 25 ul of 10% Triton X-100 (17 ul 10x CutSmart buffer + 128 ul nuclease-free water + 25 ul 10% TX-100) to quench the SDS. Mix well by pipetting, avoiding excessive foaming.
1. Incubate at 37C for 15 min.
1. Add 25 ul of 1X CutSmart buffer, mix by inverting and take a 8 ul control aliquot. Add 100 U of NlaIII restriction enzyme (10ul of a 10U/ul stock) to the remaining nuclei and digest chromatin for 3-4 hours at 37C under rotation.  
1. After 3-4 hours, add another 100 U and incubate under rotation overnight at 37C.  
 _Optional:Take 8ul aliquote and de-crosslink it by adding 80ul of TE buffer and 5ul of prot K (20mg/ul), heat at 65C for 1h and run on a 1% agarose gel._
1. Add another 50 U of enzyme to the samples and incubate for 3-4 more hours at 37C under rotation 
1. Heat-inactivate the NlaIII enzyme 20 min at 65C Spin 5 min at 1000 g, remove sup and resuspend pellet in 300 ul of fresh 1X NEB2.
1. Add 900 ul ligation buffer and 5 ul of Roche T4 DNA Ligase (5U/ul)  incubate overnight at 16C under rotation.
1. Add 50ul of proteinase K (20mg/ul) and 10 ul of RNAse A, incubate 1h at 55C and then 4h at 65C.
1. Split each sample in two 600ul aliquotes and purify with 1:1 phenol-chloroform-isoamylalcohol, then precipitate by adding:
  * 2ul glycogen + 60ul NaAC 3M + 2.5 volumes of absolute ethanol.  
  _Optional: Samples might be stored at -80C._
1. Centrifuge at max speed for 25 min.
1. Wash the pellet with 500 ul 75% EtOH, and resuspend the pellet in 100 ul water, take 8ul aliquot and run on gel to check if ligation worked.
1. Put together the 2 aliquots and digest with 50 U MluCI in 300 ul total volume overnight at 37C.
1. MluCI cannot be heat inactivated so it is necessary to do a purification:
1. Add 500 ul Phenol–Chloroform and mix vigorously; 
1. Spin 10 min at 16400 g at RT; 
1. Transfer the aqueous phase to a fresh tube and add:
  * 50 ul 2 M NaAc pH 5.6 and 950 ul 100% EtOH;  Incubate at 80C until completely frozen.
1. Spin 20 min 16400 g at 4C.
1. Remove supernatant and add 150 ul cold 70% ethanol.
1. Spin 10 min 16400 g at 4C.
1. Resuspend the pellet in 150 ul of water.
1. Transfer sample to a 50 ml tube and add: 
  * 12.1 ml Milli-Q
  * 1.4 ml 10x Ligation buffer (home-made) 
  * 100 U T4 DNA Ligase
  * Ligate overnight at 16C.
1. Precipitate the ligation by adding: 
  * 1.4 ml 3M NaAc
  * 35 ml absolute EtOH
  * 10 ul glycerol.
1. Mix well and keep at -80C for at least 2h.  
   _Optional: Samples might be stored at -80C for later processing._
1. Centrifuge for 45 min.
1. Wash with 10 ml cold 75% EtOH.
1. Resuspend in 150 ul TE and purify with Quiagen PCR purification kit.
1. Elute twice in 50ul EB.
1. For the PCR 200 ng of purified DNA are amplified with Expand™ Long Template PCR System
  * 50ul DNA (200 ng)
  * 2ul dNTPs 10 mM
  * 2ul GAT024 primer 25 uM
  * 2ul AR60-64 primer 25 uM
  * 10ul 10X buffer1
  * 1.5ul Polymerase
  * 32.5 water.
1. PCR program:
  * 94C 2 min 
  * 94C 15 sec//55C 1 min//68C 3 min - 27 Cycles 
  * 68C 7 min 

In order to have enough coverage a total of 4 PCRs reactions are pooled for each sample. 
Before sequencing samples are purified with Agencourt beads 
Primer sequences:

ARO60 
CAAGCAGAAGACGGCATACGAGATCGTGATGTGACTGGAGTTCAGACGTGTGCTCTTCC
GATCTTAAAGGCAATGCTACCAAATACT

GAT024
AATGATACGGCGACCACCGAGATCTACACTCTTTCCCTACACGACGCTCTTCCGATCT

