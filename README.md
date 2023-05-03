## Citation
If you use this repository, please cite the following paper. 

Li, Y., Dong, P., Yao, S., & Qin, R. (2023). Subject-invariant sEMG Representation Learning for Human-to-Robot Communication in Infrastructure Inspection.arXiv preprint arXiv....

~~~~  
@article{li2023multi,
  title={Subject-invariant sEMG Representation Learning for Human-to-Robot Communication in Infrastructure Inspection},
  author={Li, Yu and Dong, Penghao and Yao, Shanshan and Qin, Ruwen},
  journal={arXiv},
  year={2023},
}
~~~~


## Data

RICKs v2.0 comprises sEMG and audio data of 23 keywords gathered from 11 subjects. The 11 subjects contributed their data to this study, which ages ranged from 19 to 46 years old. Of these participants, four were male, and the remaining seven were female. All subjects spoke English fluently, and four of them were native English speakers. 
In this project, we collected sEMG data and audio data synchronously at a rate of 40000. There were 7 channels for sEMG data, and their locations were attached around the mouth as shown in the figure. Additionally, there were 8 ground electrodes attached to the bones.
<p align="center">
  <img src="https://user-images.githubusercontent.com/44143351/232257152-2bdccfe7-1e5f-4ceb-a210-d1e0208aec15.jpg" alt="sEMG sensor" width="50%" height="auto">
</p>

Raw data can be downloaded from https://www.dropbox.com/s/d3j5usnntsfiajl/RICKs-v2.0.zip?dl=0, the following image is an example of the collected sEMG and audio data. Instruction of the raw data can be found in "Raw data instruction.md" in this project.
<p align="center">
  <img src="https://user-images.githubusercontent.com/44143351/232256546-72b93a57-b373-4281-ba72-448ac82b309a.png" alt="sEMG sensor" width="50%" height="auto">
</p>

## Experiment Results
Experiment results are concluded in the paper, details can be found from "Experiment Results/All Experiments Performance.xlsx" in this repository.

## Note
This paper has just been submitted to the ACM MM conference. The citation will be updated later. 
Raw data can be downloaded now, but the code for data preprocessing and the model will be uploaded after acceptance.
