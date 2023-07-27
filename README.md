# SST
Synthetic Sampling Technique
The provided text discusses the Synthetic Sampling Technique (SST) software designed to address uncertainty in the hospital environment. The SST simulates the hospital with basic medical information, creating a realistic representation of the hospital setting. In the hospital environment, uncertainty plays a crucial role due to various unpredictable factors, such as patient arrivals, emergency cases, and staff availability.

Figure shows a 20 x 20 pixel bitmap representing time on the x-axis and room space on the y-axis. Each pixel represents a 30-minute interval of a person's stay in a selected room. However, the actual duration of stay for a patient, nurse, or doctor may vary due to unexpected events or delays. Uncertainty in hospital operations can affect the movement patterns and timing of individuals within the facility.

<img width="585" alt="Screen Shot 2023-07-27 at 1 56 35 PM" src="https://github.com/syntizen/SST/assets/10936385/dff456b3-5d62-47f4-9cb6-f4ed9299127e">

The different colors in Figure represent specific patterns of footprints for patients, nurses, and doctors as they move through the hospital. These patterns can be subject to changes caused by uncertainty, such as a patient's visit to a specific doctor being delayed due to an emergency case.

Additionally, the staff's footprints, represented by yellow and green colors, show consistent stay patterns in specific rooms, but uncertainties in their schedules and tasks might lead to deviations in their movement patterns.

By incorporating uncertainty into the simulation, the SST software can generate more realistic and robust synthetic footprint data. This data will better reflect the challenges hospitals face in managing patient flow, resource allocation, and overall operational efficiency in the presence of uncertainty. Utilizing this data to train machine learning algorithms will lead to more accurate analysis and decision-making in hospital management, helping healthcare institutions adapt and respond effectively to uncertain situations.
