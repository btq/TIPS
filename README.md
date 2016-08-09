# TIPS

## Compliance Rate
 
 Who is and isn't showing up?
 
 87.5% is the given value - check this

## Effect of Program
 
 Hypothesis: program doesn't change BP & SPo2

 Effect of the Program by condition & # of conditions
 
 5 Question metrics - look at these

## Hospitalization

 Is the program reducing rehospitalization?
 
 Medicare/medicaid
 
 Hospital stay length
 
 Hospital stay reason - for a chronic condition
 
 Number of ER visits

## How long until patient 'feels' better?

## People to meet

 Linda Gerber

## Give every patient an Elixhauser comorbidity score ##
---
## Files list and description

all data files in /data:

**BP_HR_Readings.xlsx** - 1 sheet, record of BP for each visit
*	EndUserId - TIPS ID
*	Diastolic
*	Systolic
*	HeartRate

**Demographic_Info2.xlsx** - demographics on all TIPS participants use '_btqedit' version

**Demographic_Info2_btqedit.xlsx** - 2 sheets, only use the first
*	TIPS_Number - TIPS ID
*	Age
*	Gender - 1=?, 2=?
*	CHF
*	COPD
*	Diabetes
*	Hypertension
*	Stroke
*	Hypoglycemia
*	Falls
*	Liver Disease
*	Hypotension
*	Obesity
*	Coronary Artery Disease
*	Fractures
*	Renal
*	Alzheimers
*	Depression

**demographics 6-22-16.xlsx** - 3 sheets, first is enrollees
 * *Enrollees*
  *	PIN - external PIN
  *	Status - A/D = active/discharged
  *	Gender
  *	DOB
  *	Age
  *	Language
  *	Living Set-Up
  *	Medicaid
  *	Hospitalized ?
  *	RPM Hospitalized ?
  *	RPM Falls ?
  *	Rehospitalized ?
  *	RPM Rehospitalized ?
  *	CHF
  *	COPD
  *	Diabetes
  *	Hypertension
  *	Stroke
  *	Hypoglycemia
  *	Falls
  *	Liver Disease
  *	Hypotension
  *	Obesity
  *	Coronary Artery Disease
  *	Fractures
  *	Renal
  *	Alzheimers
  *	Depression
*  *Sheet2*
  *  	PIN
  *  	Enrolled/Discharged & reason column

**messages 6-22-16.xlsx** - responses from 5 questions, 3 sheets
*  *messages*
  *  	EndUserId - TIPS ID
  * 	RespondedOn
  *  	Question
  *  	Response
*  *NewMessages* - not sure how this is different from messages sheet
  *    EndUserId
  *    RespondedOn
  *    Question
  *    Response
  *    ID - patient PIN
  *    Date
  *    Month
  *    UniqueVisit
*  *IDLookup*
  *  	EndUserId - TIPS ID
  *  	KioskPin - patient PIN

**Messages_reworked.xlsx** - responses from 5 questions recoded, not too useful

**Pre-TIPS_Hospitalization_record.xlsx**
* *Sheet1*
  * TIPS Number
  * PIN
  * Medicaid - ? 0/1/2 not sure the coding here
  * PostTIPS Hospitalized - ? 1/2 also called rpm_hospitalized
  * PostTIPS Rehospitalization - ? 1/2 also called rpm_rehospitalized
  * PreTIPS Hospitalized - ? 0/1/2 also called hospitalized
  * PreTIPS Rehospitalized - ? 0/1/2 also called rehospitalized
**readings 6-22-16.xlsx**
* *Key* - guide to the sheets in the file
* *RawReadings*
  * EndUserId - TIPS ID
  * ReadingId
  * TIPS ID - NOT TIPS ID - EXTERNAL ID
  * ReadingType
  * ReadingDate
  * Systolic
  * Diastolic
  * HeartRate
  * Weight
  * SP02
  * HeartRate_SP02
  * ReadingSuppressedOn
  * Steps
**SpO2_HR_Readings.xlsx**

**Weight_Readings.xlsx**
