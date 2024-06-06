# README: Human-Robot Interaction (HRI) Experiment - Collaborative Shared LEGO Assembly Task

## Introduction

This README file provides an overview of our HRI experiment, which focused on a collaborative shared LEGO assembly task. We evaluated the performance of three different conditions, namely Audio, ASAP, and JIT, in this context. The experiment aimed to understand how these conditions impacted the participants' assembly tasks. We collected both quantitative and qualitative data for evaluation.

## Experiment Details

- **Participants**: We conducted the experiment with a total of 30 participants.
  - We collected information on participants' demographics, including sex, age, dominant hand, and the order of exposure to the three conditions (Audio, ASAP, JIT) was randomized for each participant.

- **Scenes**: We designed and used nine different LEGO assembly scenes for the experiment.

- **Task Setup**: Each participant performed the LEGO assembly task three times, once for each of the three conditions (Audio, ASAP, JIT), using three different scenes for each condition. This resulted in nine assembly tasks per participant.

## Data Files

We have prepared several data files to capture the experiment's results and participant responses:

1. **start_end.csv**: Contains participant ID, the questionnaire type (start or end), and common questions for comparison (asked both before and after the experiment).

2. **asap_jit.csv**: Contains participant ID, the block type (ASAP or JIT), and common questions (without audio) for comparison between the two conditions.

3. **audio_asap_jit.csv**: Contains participant ID, the block type (ASAP, JIT, or ASAP), and common questions (with audio) for comparison among the three conditions.

4. **end_alone.csv**: Contains participant ID and questions that appear only in the end questionnaire.
 
5. **audio_asap_jit_end.csv**: Contains participant ID, the block type (Audio, ASAP, JIT, or END).

6. **action_data.csv**: Contains participant ID, the condition, the scene_id, the sequence of correct(0) and incorrect (1) actions, and the list of timings for each action.
## Data Analysis

We plan to conduct both quantitative and qualitative evaluations of the experiment:

- **Quantitative Evaluation**:
  - We will analyze participants' time to complete and error counts for each condition and scene combination.

- **Qualitative Evaluation**:
  - We will assess participants' experiences using five-point Likert scale questionnaires.
  - Questionnaires include:
    - "Start" (before the experiment) compared with "End" (end of the experiment).
    - Audio, ASAP, and JIT conditions (3 questionnaires each), typically administered after their respective blocks.
