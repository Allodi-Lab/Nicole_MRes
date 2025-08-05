
# Nicole MRes Project README

All code used for **EthoVision** behavioural analysis and **Keypoint-MoSeq** behavioural analysis pipeline is available on the lab GitHub account.  
Larger files, such as the **RNAscope** images, can be found on the University long-term storage, either by clicking the link below or via Map Network (`X:\nj35\MRes`). 
RNAscope data includes all images captured using Zeiss 3.9 software on Jeeves PCs, stored in `Documents/Nicole/` and uploaded to the long-term storage.

**Allodi Lab GitHub Repository:**  
https://github.com/Allodi-Lab

**University Long-Term Storage:**  
[file://cfs.st-andrews.ac.uk/shared/AllodiLabs/](file://cfs.st-andrews.ac.uk/shared/AllodiLabs/) *(for Windows)*

---

## Language

- **Behavior_Analysis** – Keypoint-MoSeq *(Python)* – EthoVision *(R)*
- **RNAscope_Analysis** – *(R)*

---

## Version

- **DeepLabCut + Model Zoo Package** – 3.0  
- **Keypoint MotionSequence** – 0.5.0  
- **GraphPad Prism** – 10.7

---

> **Note:**  
> For `Ethovision_analysis`, Ethovision outputs (raw) were compiled into excel files for each group (control, post_w1, post_w2) for eac paradigm. The `summary excel files` were used for analysis, which is a compilation of the raw excel files. model statistics were first determined, then raincloud plots were produced, which were used in the thesis.  
> For the `MoSeq_analysis`, model statistics were first determined, then the SE values were determined. The SE values were then ordered by control frequency. The `ordered_SE` data was used for the thesis. GEELM model was just for testing and can be ignored.  
> For `RNAscope_analysis`, attempted replication of the code used in GraphPad Prism, but was unsuccessful. Data used in the thesis was analysed in GraphPad Prism instead, using a Nested T-Test.

