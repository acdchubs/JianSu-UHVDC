# Hyper-scale (2GW) Flexible Power Control Driven by a Multi-Terminal UHVDC System with LCC-VSC Hybrid Cascaded Structure

Known as the first of its kind, the JianSu-UHVDC system takes full advantage of both LCC and VSC technologies from stability enhancement and economic operation perspectives, which develops a cross-regional, large-scale power reciprocity control system and realizes the world’s largest (2 GW) bidirectional, flexible, and rapid power flow control, effectively alleviating the severe power shortage pressure in East China without increasing short-circuit current levels. This paper presents the novel architecture design, key modules, control strategies in normal and power reciprocity modes, stability enhancement, and economic benefits of the system.

Through high-fidelity simulation studies and a series of real-world commissioning experiments, stable operation of the JianSu-UHVDC system is achieved that can reliably deliver 4 GW power at the sending end and enable flexible power reciprocity at a maximum capacity of 2 GW among the three VSCs at the receiving end operating at their full capacity. 

This novel multi-terminal UHVDC system provides **a new solution** to hyper-scale, flexible, and rapid power flow control for secure electricity delivery to heavy load centers without building new power plants.

## Milestones of real-world commissioning experiments

<details open>
<summary>
Before the long-term operation of the JianSu-UHVDC system with power reciprocity, a series of commissioning experiments were designed and conducted to ensure the correct and reliable operation of the system. 
</summary>

<br>
The commissioning experiments are listed below:

### :one: `200MW` Commissioning Experiment
On April 21st, 2023, at 9:53 AM, the power reciprocity function was first put into operation with the maximal power reaching 200 MW, extracting power from northern Suzhou that is transferred to the southern areas of Suzhou with severe power deficiencies. It marked a remarkable milestone in enabling large-scale, flexible power flow control across large regions. 

### :two: `1000MW` Commissioning Experiment
In the second commissioning test, for the entire day, June 29th, 2023, the JianSu-UHVDC system stably operated at the power reciprocity control mode with a fixed power command of 1 GW. The actual measurements of DC power are captured and depicted in Figure 6. (Video available at: https://github.com/acdchubs)

![Commissioning Experiment1](https://github.com/acdchubs/JianSu-UHVDC/blob/main/milestoneSet/1000.gif)

### :three: `2000MW` Commissioning Experiment
During the period, March 1st, 2024, 1:30 AM - 2:30 AM, the sending end transferred a total amount of 4 GW power and the power reciprocity control successfully reached a maximum of 2 GW for the first time and the other two VSCs also reached their maximum design capacities (2 GW each), effectively alleviate the power shortage issue in the southern load center. The operation data of the JianSu-UHVDC system is shown in Figure 7, marking a milestone of the first-ever implementation of large-capacity, flexible power flow in AC-DC hybrid interconnected grids. (Video available at: https://github.com/acdchubs)

![Commissioning Experiment2](./milestoneSet/2000.gif)

</details>

## Long-term operational logs under various conditions

<details open>
<summary>
From April 21st, 2023, to November 18th, 2024, the JianSu-UHVDC system was partially converted to the power reciprocity control mode to relieve the power shortage burden in the southern load center. A detailed operational log is provided in Table 3, including the activation time of the power reciprocity mode, DC power command, the actual DC power measurements for power reciprocity, and the total energy delivered to the southern load center.
</summary>

### :ballot_box_with_check: power reciprocity: `fix`

From November 13th to November 18th, 2024, the power transfer at the sending end varied from 800 MW to 3500 MW; at the receiving end, a total power reciprocity command was fixed at 800 MW. The time-series DC power curve is depicted in Figure 8. (Data and video available at: https://github.com/acdchubs)

![Commissioning Experiment2](https://github.com/acdchubs/JianSu-UHVDC/blob/main/operationLog/fix.gif?raw=true)

### :white_check_mark: power reciprocity: `change`

From March 1st to March 18th, 2024, the power transfer at the sending end varied from 800 MW to 1414 MW; at the receiving end, a total power reciprocity command was set to three levels, including 1200 MW, 1600MW, and 600 MW. The time-series DC power curve is depicted in Figure 9. (Data and video available at: https://github.com/acdchubs)

![Commissioning Experiment2](./operationLog/change-1.gif?raw=true)

</details>

> [!NOTE]
> Data and video(gif format) for paper.

> [!TIP]
> And you can see [a interactive introduction](https://jiansu.streamlit.app target="_blank")
> 
