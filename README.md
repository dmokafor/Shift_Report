# Shift Report
## Project Overview
Enhanced Version:
This dashboard delivers a comprehensive summary of on-going Shift Performance tailored for both operations teams and non-operations stakeholders (i.e middle management). It is designed to:
- Enhance situational awareness across teams
- Enable data-driven, proactive decision-making
- Strengthen accountability and ownership
- Streamline cross-functional coordination
- Facilitate efficient and effective shift handover
- Optimize service delivery performance

Below is the main page of the Report:
<p align="left"><img src="https://github.com/dmokafor/Shift_Report/blob/main/screenshots/Shift_Report.png" alt="Main Page"></p>

## Dashboard Components
The dashboard provides a structured view of shift performance, beginning with the **current shift details** and the **responsible personnel**.  

Following this, **four visual cards** highlight critical operational areas—**vessel, barge, gate, and rail**—displaying container moves and the number of carriers handled.

Beneath these, **mini cards display essential KPIs**, including:  
- **Safety incidents**: Number of safety incidents that occured during the shift.   
- **Port hours saved**:  The percentage reduction in the total time a vessel spends in port compared to a baseline or expected duration.
- **Containers Moved Per Hour (CMPH)**: The average CMPH of all cranes that worked on vessels during the shift.
- **Truck turn time**: Total time a truck spends inside the terminal from entry to exit.
- **Yard utilization**: The percentage of available yard space that is currently occupied by containers in the terminal. 

The **bar chart** below the mini cards illustrates overall **Shift Change Performance** which measured the duration between the last container lift of the previous shift to the first container lift of the current shift.  

Next, a **Container Handling Equipment (CHE) Performance table** presents insights by equipment type (MHC, RTG, TT, RS, EH), detailing:  
- **Moves per hour**: Averag moves per hour per equipment.
- **Availability**: measures the percentage of time an equipment is available for operations.
- **Utilization**: measures the percentage of time an equipment is actually used.

The **Vessel Performance table** provides details on **active and departed vessels during the shift**, tracking key metrics such as:  
- Total moves: Total container moves planned on the vessel.
- Shift moves: Total container moves executed during the shift.
- Balance moves: Total remaining moves to be executed on the vessel.
- Estimated time of completion (ETC).
- Estimated and required time of departure.
- Estimated port hours saved.

The **Crane Performance table** provides details on **working cranes**, tracking key metrics such as: total moves, shift moves, balance moves, first and last lift timestamps, crane hours, Shift CMPH, and ETC for each crane.

Additional KPIs displayed include:  
- **Truck service time**  
- **Percentage of trucks serviced for more than 90 minutes**  
- **Open terminal delivery orders**  
- **Number of containers examined by customs**  

This structured layout ensures comprehensive visibility into shift efficiency, operational bottlenecks, and overall terminal performance.
## Data Model
<p align="left"><img src="https://github.com/dmokafor/Shift_Report/blob/main/screenshots/data_model.png" alt="Data Model"></p>
