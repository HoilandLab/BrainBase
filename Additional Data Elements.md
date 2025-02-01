**CO<sub>2</sub> Reactivity**
<br> The below table outlines each of the 83 data fields contained in the CO2 Reactivity Test form on the REDCap database.
| Data Element | Field | Description |
| :---: | :---: | --- |
| CO2 Reactivity Method | [co2_reactivity_method] | Identify the CO2 reactivity test method <br> *Radio* <br> *1 = ‘Fixed fractional CO2’; 2 = ‘End-tidal forcing’; 3 = ‘Other’; 4 = ‘Rebreathing’* |
| Specific CO2 Reactivity Method | [co2_reactivity_method_other] <br> *Branched logic: show only IF [co2_reactivity_method] = ‘Other’* | Specify the CO2 reactivity test method <br> *Text* |
| Blood Gases Collected | [co2_blood_gas] <br> *Branched logic: show only IF [co2_reactivity_method] = 'End-tidal forcing' or [co2_reactivity_method] = 'Fixed fractional CO2'* | Indicate whether blood gases were collected <br> *Radio* <br> *1 = ‘Yes’; 2 = ‘No’* |
| Stages 1-3 O2 Partial Pressure | [co2_pao2_1], [co2_pao2_2], [co2_pao2_3] <br> *Branched logic: show only IF [co2_blood_gas] = 'Yes'* | Partial pressure of arterial oxygen during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Peripheral O2 Saturation | [co2_sao2_1], [co2_sao2_2], [co2_sao2_3] | Peripheral oxygen saturation during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Arterial O2 Content | [co2_cao2_1], [co2_cao2_2], [co2_cao2_3] | Arterial oxygen content during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Pressure Arterial O2 | [co2_paco2_1], [co2_paco2_2], [co2_paco2_3] <br> *Branched logic: show only IF [co2_blood_gas] = 'Yes'* | Partial pressure of arterial carbon dioxide during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Hemoglobin Concentration | [co2_hb_1], [co2_hb_2], [co2_hb_3] | Hemoglobin concentration during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Hematocrit Content | [co2_hct_1], [co2_hct_2], [co2_hct_3] | Hematocrit content during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Blood pH | [co2_ph_1], [co2_ph_2], [co2_ph_3] | Blood pH during test stages 1-3 <br> *Text, validation: number (3 decimal places)* |
| Stages 1-3 Bicarbonate Concentration | [co2_hco3_1], [co2_hco3_2], [co2_hco3_3] | Bicarbonate ion concentration during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Blood Glucose  | [co2_glucose_1], [co2_glucose_2], [co2_glucose_3] | Blood glucose during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Blood Lactate | [co2_lactate_1], [co2_lactate_2], [co2_lactate_3] | Blood lactate during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 End-Tidal CO2 Tension | [co2_petco2_1], [co2_petco2_2], [co2_petco2_3] | End-tidal carbon dioxide tension during test stages 1-3 <br> *Text, validation: number (1 decimal place)*|
| Stages 1-3 MAP | [co2_map_1], [co2_map_2], [co2_map_3] | Mean arterial pressure during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 MCA Velocity | [co2_mcav_1], [co2_mcav_2], [co2_mcav_3] | Middle cerebral artery velocity during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| MCA Reactivity | [co2_mca_react] | Middle cerebral artery reactivity (cm / second / mmHg) <br> *Text, validation: number (1 decimal place)* |
| MCA Reactivity 2 | [co2_mca_react_2] | Middle cerebral artery reactivity (% / mmHg) <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 PCA Velocity | [co2_pcav_1], [co2_pcav_2], [co2_pcav_3] | Posterior cerebral artery velocity during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| PCA Reactivity | [co2_pca_react] | Posterior cerebral artery reactivity (cm / second / mmHg) <br> *Text, validation: number (1 decimal place)* |
| PCA Reactivity 2 | [co2_pca_react_2] | Posterior cerebral artery reactivity (% / mmHg) <br> *Text, validation: number (1 decimal place)* |
| ICA Side | [co2_ica_side] | Internal carotid artery side <br> *Dropdown* <br> *1 = ‘Right’; 2 = ‘Left’* |
| Stages 1-3 ICA Velocity | [co2_icav_1], [co2_icav_2], [co2_icav_3] | Internal cerebral artery velocity during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 ICA Diameter | [co2_ica_diameter_1], [co2_ica_diameter_2], [co2_ica_diameter_3] | Internal carotid artery diameter during test stages 1-3 <br> *Text, validation: number (2 decimal places)* |
| Stages 1-3 ICA Flow | [co2_ica_flow_1], [co2_ica_flow_2], [co2_ica_flow_3] | Internal carotid artery flow during test stages 1-3 <br> *Calculated* <br> *Calculation: round(3.14159265359 * ([co2_ica_diameter_1]*0.5*0.1)^(2) * 60 * ([co2_icav_1]/2), 2); round(3.14159265359 * ([co2_ica_diameter_2]*0.5*0.1)^(2) * 60 * ([co2_icav_2]/2), 2); round(3.14159265359 * ([co2_ica_diameter_3]*0.5*0.1)^(2) * 60 * ([co2_icav_3]/2), 2)* |
| ICA Reactivity | [co2_ica_react] | Internal carotid artery reactivity (cm / second / mmHg) <br> *Text, validation: number (1 decimal place)* |
| ICA Reactivity 2 | [co2_ica_react_2] | Internal carotid artery reactivity (% / mmHg) <br> *Text, validation: number (1 decimal place)* |
| VA Side | [co2_va_side] | Vertebral artery side <br> *Dropdown* <br> *1 = ‘Right’; 2 = ‘Left’* |
| Stages 1-3 VA Velocity | [co2_vav_1], [co2_vav_2], [co2_vav_3] | Vertebral artery velocity during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 VA Diameter | [co2_va_diameter_1], [co2_va_diameter_2], [co2_va_diameter_3] | Vertebral artery diameter during test stages 1-3 <br> *Text, validation: number (2 decimal places)* |
| Stages 1-3 VA Flow | [co2_va_flow_1], [co2_va_flow_2], [co2_va_flow_3] | Vertebral artery flow during test stages 1-3 <br> *Calculated* <br> *Calculation: round(3.14159265359 * ([co2_va_diameter_1]*0.5*0.1)^(2) * 60 * ([co2_vav_1]/2), 2); round(3.14159265359 * ([co2_va_diameter_2]*0.5*0.1)^(2) * 60 * ([co2_vav_2]/2), 2); round(3.14159265359 * ([co2_va_diameter_3]*0.5*0.1)^(2) * 60 * ([co2_vav_3]/2), 2)* |
| VA Reactivity | [co2_va_react] | Vertebral artery reactivity (cm / second / mmHg) <br> *Text, validation: number (1 decimal place)* |
| VA Reactivity 2 | [co2_va_react_2] | Vertebral artery reactivity (% / mmHg) <br> *Text, validation: number (1 decimal place)* |
| Time On Bag | [co2_time_on_bag] <br> *Branched logic: show field IF [co2_reactivity_method] = 'Rebreathing’* | Time on bag (minutes) <br> *Text, validation: number* |
| Peak CO2 | [co2_peak_co2] <br> *Branched logic: show field IF [co2_reactivity_method] = 'Rebreathing’* | Peak CO2 achieved (mmHg) <br> *Text, validation: number* |
| Delta CO2 | [co2_delta_co2] <br> *Branched logic: show field IF [co2_reactivity_method] = 'Rebreathing’* | Delta CO2 (mmHg) <br> *Text, validation: number* |
| CO2 Reactivity Data File | [co2_csv_file_upload] | CO2 Reactivity Test Raw Data File (.csv) <br> *File* |
| Form Status | [study_information_complete] | Verify completion of the ‘Study Information’ form <br> *Dropdown* <br> *0 = ‘Incomplete’; 1 = ‘Unverified’; 2 = ‘Complete’* |
<br>

**Hypoxic Reactivity Test**
<br>The below table outlines each of the 63 data fields contained in the Hypoxic Reactivity Test form on the REDCap database.
| Data Element | Field | Description |
| :---: | :---: | --- |
| O2 Reactivity Method | [o2_reactivity_method] | Select the hypoxic reactivity test method <br> *Radio* <br> *1 = ‘Fixed fractional change in FIO2 (Douglas Bag Method)’; 2 = ‘End-tidal forcing’; 3 = ‘Other’* |
| Specify O2 Reactivity Method | [o2_reactivity_method_other] <br> *Branched logic: show field IF [o2_reactivity_method] = ‘Other’* | Specify the hypoxic reactivity test method <br> *Text* |
| Blood Gases Collected | [o2_blood_gas] | Indicate if blood gases were collected <br> *Radio* <br> *1 = ‘Yes’; 2 = ‘No’* |
| Oxygen Tension | [o2_pao2] <br> *Branched logic: show field IF [o2_blood_gas] = ‘Yes’* | <br> Partial pressure of arterial oxygen *Text, validation: number (1 decimal place)* |
| Saturation of Arterial Oxygen | [o2_sao2] | The saturation of arterial oxygen <br> *Text, validation: number (1 decimal place)* |
| Arterial oxygen content | [o2_cao2] | Patient’s arterial oxygen content <br> *Text, validation: number (1 decimal place)* |
| Carbon Dioxide Tension | [o2_paco2] <br> *Branched logic: show field IF [o2_blood_gas] = ‘Yes’* | Partial pressure of arterial carbon dioxide <br> *Text, validation: number (1 decimal place)* |
| Hemoglobin Concentration | [o2_hb] | Patient’s hemoglobin concentration <br> *Text, validation: number (1 decimal place)* |
| Hematocrit | [o2_hct] | Patient’s hematocrit <br> *Text, validation: number (1 decimal place)* |
| Blood pH | [o2_ph] | Patient’s blood pH <br> *Text, validation: number (1 decimal place)* |
| Bicarbonate ion | [o2_hco3] | Patient’s bicarbonate ion level <br> *Text, validation: number (1 decimal place)* |
| Blood Glucose | [o2_glucose] | Patient’s blood glucose level <br> *Text, validation: number (1 decimal place)* |
| Blood Lactate | [o2_lactate] | Patient’s blood lactate level <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 End-Tidal CO2 Tension | [o2_petco2_1], [o2_petco2_2], [o2_petco2_3] | End-tidal carbon dioxide tension during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 End-Tidal O2 Tension | [o2_peto2_1], [o2_peto2_2], [o2_peto2_3] | End-tidal oxygen tension during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Saturation of Peripheral O2 | [o2_spo2_1], [o2_spo2_2], [o2_spo2_3] | Saturation of peripheral oxygen during test stages 1-3 (%) <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 MAP | [o2_map_1], [o2_map_2], [o2_map_3] | Mean arterial pressure during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 MCA Velocity | [o2_mcav_1], [o2_mcav_2], [o2_mcav_3] | Middle cerebral artery velocity during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
|  |  | <br> ** |
|  |  | <br> ** |
|  |  | <br> ** |
|  |  | <br> ** |
|  |  | <br> ** |
|  |  | <br> ** |
|  |  | <br> ** |
|  |  | <br> ** |
|  |  | <br> ** |
| Form Status | [study_information_complete] | Verify completion of the ‘Study Information’ form <br> *Dropdown* <br> *0 = ‘Incomplete’; 1 = ‘Unverified’; 2 = ‘Complete’* |
<br>

**Transient CO<sub>2</sub> Reactivity Test**
<br>The below table outlines each of the 43 data fields contained in the Transient CO2 Reactivity Test form on the REDCap database.
| Data Element | Field | Description |
| :---: | :---: | --- |
|  |  | <br> ** |
| Form Status | [study_information_complete] | Verify completion of the ‘Study Information’ form <br> *Dropdown* <br> *0 = ‘Incomplete’; 1 = ‘Unverified’; 2 = ‘Complete’* |
<br>

**Blood Chemistry**
<br>The below table outlines each of the 36 data fields contained in the Blood Chemistry form on the REDCap database.
| Data Element | Field | Description |
| :---: | :---: | --- |
|  |  | <br> ** |
| Form Status | [study_information_complete] | Verify completion of the ‘Study Information’ form <br> *Dropdown* <br> *0 = ‘Incomplete’; 1 = ‘Unverified’; 2 = ‘Complete’* |
<br>

**Cerebral Autoregulation**
<br>The below table outlines each of the xx data fields contained in the Cerebral Autoregulation form on the REDCap database.   
| Data Element | Field | Description |
| :---: | :---: | --- |
|  |  | <br> ** |
| Form Status | [study_information_complete] | Verify completion of the ‘Study Information’ form <br> *Dropdown* <br> *0 = ‘Incomplete’; 1 = ‘Unverified’; 2 = ‘Complete’* |
<br>

**Cardiorespiratory Fitness**
<br>The below table outlines each of the xx data fields contained in the Cardiorespiratory Fitness form on the REDCap database.   
| Data Element | Field | Description |
| :---: | :---: | --- |
|  |  | <br> ** |
| Form Status | [study_information_complete] | Verify completion of the ‘Study Information’ form <br> *Dropdown* <br> *0 = ‘Incomplete’; 1 = ‘Unverified’; 2 = ‘Complete’* |
<br> 
