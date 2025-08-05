
# Nicole MRes Project README

All code used for **EthoVision** behavioural analysis and **Keypoint-MoSeq** behavioural analysis pipeline is available on the lab GitHub account.  
Larger files, such as the **RNAscope** images and videos for Keypoint-MoSeq , can be found on the University long-term storage, either by clicking the link below or via Map Network (`X:\nj35\MRes`). 
For RNAscope, all images captured using Zeiss 3.9 software on Jeeves PCs, stored in `Documents/Nicole/` and are uploaded to the long-term storage.

**Allodi Lab GitHub Repository:**  
https://github.com/Allodi-Lab

**University Long-Term Storage:**  
[file://cfs.st-andrews.ac.uk/shared/AllodiLabs/](file://cfs.st-andrews.ac.uk/shared/AllodiLabs/) *(for Windows)*

---

## Language

- **Behavior_Analysis** – Keypoint-MoSeq *(Python + R)* – EthoVision *(R)*
- **RNAscope_Analysis** – *(GraphPad Prism)*

---

## Version

- **DeepLabCut + Model Zoo Package** – 3.0  
- **Keypoint MotionSequence** – 0.5.0  
- **GraphPad Prism** – 10.7

---

> **Note:**  
> For `Ethovision_analysis`, Ethovision outputs (raw) were compiled into excel files for each group (control, post_w1, post_w2) for eac paradigm. The `summary excel files` were used for analysis, which is a compilation of the raw excel files. model statistics were first determined, then raincloud plots were produced, which were used in the thesis.  
> For the `MoSeq_analysis`, model statistics were first determined, then the SE values were determined. The SE values were then ordered by control frequency. The `ordered_SE` data was used for the thesis. GEELM model was just for testing and can be ignored.  
> For `RNAscope_analysis`, data used in the thesis was analysed in GraphPad Prism, using a Nested T-Test. `blind` excel file is the raw values from Zeiss, renamed. `macros` excel file is the averaged excel file, aided by excel macros for automation of calculations. `processed` excel file formats the values easier for GraphPad Prism, with `trnapose` excel file being the same file but transposed. Example images, which were also reported in the thesis, can be found under the Zeiss folder.
> The cropped versions of the behavioural videos were used for DeepLabCut + Keypoint-MoSeq to prevent model training on paradigm reflections. There are only folders for Cohort 1 + 3, as cohort 2 only had one mouse and so was combined into cohort 3.
> Download .html files to view all outputs for R-coding notebooks.

