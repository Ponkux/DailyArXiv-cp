# Daily Papers
The project automatically fetches the latest papers from arXiv based on keywords.

The subheadings in the README file represent the search keywords.

Only the most recent articles for each keyword are retained, up to a maximum of 100 papers.

You can click the 'Watch' button to receive daily email notifications.

## Getting Started
To customize the keywords or run this project locally:
1. Clone the repository: `git clone https://github.com/your-username/DailyArXiv-cp.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Edit `config.yaml` to add or remove your preferred search keywords.
4. Run the script: `python main.py`

Last update: 2026-03-27

## Embodied AI
| **Title** | **Date** | **Abstract** | **Comment** |
| --- | --- | --- | --- |
| **[Towards Embodied AI with MuscleMimic: Unlocking full-body musculoskeletal motor learning at scale](https://arxiv.org/abs/2603.25544v1)** | 2026-03-26 | <details><summary>Show</summary><p>Learning motor control for muscle-driven musculoskeletal models is hindered by the computational cost of biomechanically accurate simulation and the scarcity of validated, open full-body models. Here we present MuscleMimic, an open-source framework for scalable motion imitation learning with physiologically realistic, muscle-actuated humanoids. MuscleMimic provides two validated musculoskeletal embodiments - a fixed-root upper-body model (126 muscles) for bimanual manipulation and a full-body model (416 muscles) for locomotion - together with a retargeting pipeline that maps SMPL-format motion capture data onto musculoskeletal structures while preserving kinematic and dynamic consistency. Leveraging massively parallel GPU simulation, the framework achieves order-of-magnitude training speedups over prior CPU-based approaches while maintaining comprehensive collision handling, enabling a single generalist policy to be trained on hundreds of diverse motions within days. The resulting policy faithfully reproduces a broad repertoire of human movements under full muscular control and can be fine-tuned to novel motions within hours. Biomechanical validation against experimental walking and running data demonstrates strong agreement in joint kinematics (mean correlation r = 0.90), while muscle activation analysis reveals both the promise and fundamental challenges of achieving physiological fidelity through kinematic imitation alone. By lowering the computational and data barriers to musculoskeletal simulation, MuscleMimic enables systematic model validation across diverse dynamic movements and broader participation in neuromuscular control research. Code, models, checkpoints, and retargeted datasets are available at: https://github.com/amathislab/musclemimic</p></details> |  |
| **[VideoWeaver: Multimodal Multi-View Video-to-Video Transfer for Embodied Agents](https://arxiv.org/abs/2603.25420v1)** | 2026-03-26 | <details><summary>Show</summary><p>Recent progress in video-to-video (V2V) translation has enabled realistic resimulation of embodied AI demonstrations, a capability that allows pretrained robot policies to be transferable to new environments without additional data collection. However, prior works can only operate on a single view at a time, while embodied AI tasks are commonly captured from multiple synchronized c