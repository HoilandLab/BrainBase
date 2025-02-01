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
| Stages 1-3 Pressure Arterial O2 | [co2_paco2_1], [co2_paco2_2], [co2_paco2_3] <br> *Branched logic: show only IF [co2_blood_gas] = 'Yes'*
 | Partial pressure of arterial carbon dioxide during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Hemoglobin Concentration | [co2_hb_1], [co2_hb_2], [co2_hb_3] | Hemoglobin concentration during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Hematocrit Content | [co2_hct_1], [co2_hct_2], [co2_hct_3] | Hematocrit content during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Blood pH | [co2_ph_1], [co2_ph_2], [co2_ph_3] | Blood pH during test stages 1-3 <br> *Text, validation: number (3 decimal places)* |
| Stages 1-3 Bicarbonate Concentration | [co2_hco3_1], [co2_hco3_2], [co2_hco3_3] | Bicarbonate ion concentration during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Blood Glucose  | [co2_glucose_1], [co2_glucose_2], [co2_glucose_3] | Blood glucose during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 Blood Lactate | [co2_lactate_1], [co2_lactate_2], [co2_lactate_3] | Blood lactate during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
| Stages 1-3 End-Tidal CO2 Tension | [co2_petco2_1], [co2_petco2_2], [co2_petco2_3] | End-tidal carbon dioxide tension during test stages 1-3 <br> *Text, validation: number (1 decimal place)* |
|  |  | <br> ** |
|  |  | <br> ** |
|  |  | <br> ** |
|  |  | <br> ** |
| Form Status | [study_information_complete] | Verify completion of the ‘Study Information’ form <br> *Dropdown* <br> *0 = ‘Incomplete’; 1 = ‘Unverified’; 2 = ‘Complete’* |
<br>

**Hypoxic Reactivity Test**
<br>The below table outlines each of the 63 data fields contained in the Hypoxic Reactivity Test form on the REDCap database.
| Data Element | Field | Description |
| :---: | :---: | --- |
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
