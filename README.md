# Modal Cognition in Rhesus Macaques - Open Science Repository

This repository contains the data, analysis scripts, and procedure demonstration videos for our study on modal cognition in nonhuman primates.

## Experiments Overview
We conducted **four experiments** that systematically examine how macaques track and distinguish representations of certainty and mere possibility.

### **Experiment 1: 3 (minus one) cup task**
- **Goal**: Test whether macaques prefer a guaranteed reward over a potentially rewarding location.  
- **Procedure**:  
  - Macaques were shown a reward hidden in one cup (certain reward).  
  - On the other side, two cups were presented, but only one contained a reward. The other contained a rock. 
  - Before choosing, one of the cups on the paired-cup side was removed.  
- **Key Question**: Can macaques differentiate between a certain and a possible reward?  
- **Results**: Macaques overwhelmingly preferred the certain reward, performing significantly above chance.  


### **Experiment 2: Controlling for minimal representation**  
- **Goal**: Test whether macaques’ performance in Experiment 1 was due to simply guessing the location of a hidden reward.  
- **Procedure**:  
  - Instead of a possible reward, a guaranteed non-reward (a rock) was placed in one cup.  
  - If macaques were guessing in Experiment 1, accuracy should improve.  
- **Key Question**: Do macaques’ choices reflect an understanding of modal contrast, or were they just guessing about the location of the apple on the paired-cup side?  
- **Results**: Performance remained stable, ruling out the possibility that subjects were merely simulating one possible location.


### **Experiment 3: Avoidance vs. modal cognition**  
- **Goal**: Rule out procedural artifacts or avoidance heuristics driving behavior in Experiments 1 and 2.  
- **Procedure**:  
  - The guaranteed reward on the single-cup side was replaced with a non-reward (a rock).  
  - The only remaining possibility for a reward was on the uncertain side.  
- **Key Question**: Would macaques switch their preference and now choose the side with possible rewards?  
- **Results**: Macaques **preferred the possible reward**, confirming they were not simply avoiding objects like the rock.


### **Experiment 4: 3 cup task - original**  
- **Goal**: Test whether macaques’ success in the first three experiments was due to the removal of an empty cup as a possibility.  
- **Procedure**:  
  - Reintroduced an empty cup as an option in the 3-cup setup.  
  - Tested whether macaques could still choose correctly when the uncertain side could contain either a reward or nothing.  
- **Key Question**: Can macaques reason about an empty possibility, or does this challenge their ability to contrast certain vs. possible rewards?  
- **Results**: Performance dropped to **chance level**, suggesting that macaques struggle when required to consider the possibility of an empty location.


## Repository Contents
This repository includes the following materials:
- **`/data/`** – Raw and processed data from each experiment.
- **`/analysis/`** – Python and R scripts for preprocessing and statistical analysis.
- **`/demos/`** – Videos demonstrating the experimental procedure.
- **`/preregistrations/`** – Our anonymized preregistrations for Experiments 1, 2, and 4 (see note below).

## Note on Demonstration Videos  
This repository includes a selection of **pre-approved demonstration videos** that illustrate the procedure of each experiment. These trial videos were approved for release in accordance with **Cayo Santiago Biological Field Station policies**. While these examples are representative of the demonstrations used in all trials, full video records are not publicly available under site regulations.

## Note on Preregistration for Experiment 2
We do not have a preregistration for Experiment 2 because it was initially conducted as a small-scale pilot to confirm that our approach paradigm was effective and that monkeys were receptive to engaging with the apparatus. As our study progressed, we expanded this experiment into a full design alongside Experiment 1. The role that Experiment 2 plays in the paper was formulated only after developing intuitions about optimal performance in this population. Given its exploratory origins, preregistration was not part of our process for this experiment. 

## Noted Deviations from Preregistrations
#### **Preregistration for Experiment 4: Citation Error**  
We initially cited Mody & Carey (2016) in reference to previous research on this question in nonhuman primates (Call, 2004, 2006; Ferrigno, Huang, & Cantlon, 2021), describing the results as inconclusive. While these studies have indeed yielded inconclusive findings, we are not aware of any claim in Mody & Carey (2016) that directly characterizes primate results in this way.  

#### **Preregistration for Experiment 4: Observation Period Change**  
We erroneously preregistered a 1-minute observation period but ultimately used a **30-second observation period**. This change was made prior to data collection based on Experiments 1 and 2, where no subjects approached after 30 seconds. At the time of testing, we observed no indication that subjects who had not approached within 30 seconds were preparing to do so.  


## How to Use This Repository
1. **Clone this repository** to your local machine:
   ```bash
   git clone https://github.com/your-username/WildPossibilities.git

