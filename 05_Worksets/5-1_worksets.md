## DPS Worksets Best Practices

DPS has adopted a methodology for worksets that utilizes **UniFormat** to logically name worksets. The portion that applies is specifically the **Top Level** of UniFormat, with a discipline designator as a prefix.

**Naming and Organization System** ![Uniformat](images/01-uniformat.png "Logo Title Text 1")
* Based on Top Level of Uniformat
* Prefixed with a Discipline Designator
>Example: **A_Shell**

 ![View Parameters](images/4-1/00-sheetParams.png)

 *gray indicates an unmodified value. All DPS sheets should appear this way*

* **Sheet Discipline** Allows for a header to be placed in the sheetlist. And by leading with a 3 digit number you can easily insert specialty consultants as needed.

* **Sheet Discipline Order** establishes the first order of
sorting within the drawing list.
##### The following parameters are additional and to be used on an "as-needed basis"
>* **Sheet Suborder** This allows support of a second order of sorting.
>* **Drawing Package Submittal** This allows for you to break up your sheets into multiple submittals. *eg. Foundation Package, Construction Documents*
>* **Sheet Submitted** This parameter exists solely for our typical MEP consultant, Bridgers & Paxton. Since the "Include in Sheet List" parameter is not schedule-able in Revit, they utilize this to have their designers pick what is going out. **DPS does not need to modify this value at all for our sheets.**

---
### Typical Values for Parameters

![Typical Values](images/4-1/01-dataSample.png)

---
### Addtional Notes:
Sheet Number is the last sorting of numbering after all of the other parameters.

>Please note however that as you make new sheets they will appear in a folder with a question mark:
![Unsorted](images/4-1/02-questionMark.png)

### Example Scenario
>If you have a food service consultant or a radiation consultant that has their own drawing series you can place them anywhere within the sheet list to suit your project. Perhaps the food service is assigned a 061-FOOD SERVICE **Sheet Discipline Order** parameter or maybe its 071-FOOD SERVICE – it’s entirely up to you and your project team.

### Enjoy
Your clean project browser and Drawing index.

![Sorted](images/4-1/03-projectBrowserSheets.png)

### If you have any questions, please consult with Revit Support.
