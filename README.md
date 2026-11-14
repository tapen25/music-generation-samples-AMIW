# music-generation-samples-AMIW

## Generated music samples
This repository contains MIDI samples generated during our research on controllable music generation. The samples were produced by our model to illustrate how generated music changes with the Complexity and Intensity settings.

## Generation settings 
For each prompt, we generated music at five Complexity levels(1,25,50,75, and 100),each combined with three Intensity levels(low, mid and high).
To compare Intensity levels with the same prompt and Complexity setting, each file includes generated sections in the order low→mid→high.

## Prompts
For evaluation, we used four-bar excerpts from 10 test pieces not used for training
as prompts. This document presents two of these prompts and their generated
continuations.
The number following p in each filename identifies the input prompt. For example, p1
refers to Prompt 1.

## Filename Convention
Example:p1_C25_low_mid_high.mid
| Component  | Meaning |
| ------------- | ------------- | 
| p1  | Uses prompt 1  |
| C25  | Complexity set to 25  |
| low_mid_high  | sections at low, mid, and high Intensity, in that order |

## MIDI File Structure
Each MIDI file consists of five sections totaling 20 bars. Complexity is fixed across
the generated sections, which are presented in the order of low, mid, and high
Intensity.
| Section  | Content | Length |
| ------------- | ------------- | ------------- |
| 1 | Input prompt | 4bars |
| 2 | low Intensity | 4bars |
| 3 | Input prompt repeated | 4bars |
| 4 | mid Intensity | 4bars |
| 5 | Input prompt repeated | 4bars |
| 6 | high Intensity | 4bars |

## Demo Videos

The following videos demonstrate the generated music.

- [Complexity = 1: Low → Mid → High Intensity](https://drive.google.com/file/d/1reRAXwgClrB81fw3vCp98EYZranjTXl6/view?usp=drive_link)
- [Complexity = 100: Low → Mid → High Intensity](https://drive.google.com/file/d/1FUVkAaaDSKW9m_Wwt-d6oGYk5_K8i5fG/view?usp=drive_link)
