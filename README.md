# PUBLICATION REPORT AUTOMATION
Tool to automate publication reports. The tool aims at saving researchers time in filling out such report and highlight the Open Access status of publiations.
* This tool was specifically created to help researchers in filling out the Research/Publications portion of the Annual Activities Questionnaire of the Depatrment of Neurology and Neurosurgery, Faculty of Medecine and Health Sciences, McGill University, for the 2022 report.
* The tool is currently based on an Excel (excel for the web) file with custom scripts that communicates with ORCID (https://orcid.org/) to retrieve a researcher's publications, and Unpaywall (https://unpaywall.org/) to retrieve the Open Access status of each publication.
## Contributors
**Gabriel Pelletier** | Open Science Data Manager @Tanenbaum Open Science Institute, The Neuro
* Questions or comments on how to make this tool better can be sent to gabriel.pelletier@mcgill.ca, or by opening an Issue on this Github repository.
# INSTRUCTIONS
1. Before you start, you must be connected to the McGill network, either from a computer connnected to the McGill internet network (through Wifi or wired connection at McGill) or through the McGill VPN.

2. **Downolad** the Excel [publication_report_autofill_2022.xlsx] file from this Github repository
* Clic on the file name to open the details.
* Clic "Download" to download the file on your computer.

3. **Upload** the file to your McGill OneDrive
* Open and log-on to your McGill Outlook in a **web browser**.
* From the App Launcher in the top left select OneDrive.
* Clic "Upload" and select the Excel file from where it was downloaded on your computer.

4. **Open** the Excel file in the browser from OneDrive and follow the simple instructions to complete your publication report.

## Notes
* The Excel sheet runs automations using custom Office Scripts written by the main Contributors of this repository. The scripts are living on their institutional (McGill) OneDrive and can **only be accessed from the McGill network**, by Excel files on your McGill OnDrive.
* You will need to grant **permission to the scripts** when using them for the first time. You will typically be prompted to allow the scripts when clicking on the "Buttons".
* **Publications are retrieved automatically** from your **ORCID record**. If some publications are missing it is because your ORCID record is not up to date. **If 0 publications are found**, it might be because that information is set to **Private** in your ORCID profile. You can easily change visibility settings (https://support.orcid.org/hc/en-us/articles/360006897614-Visibility-settings).
* **Add publications** to what was automatically retrieved from ORCID simply by copy/pasting the the DOI of the publicaition at the end of the list, and Pressing the Step 2 Button to auto-complete the publication information, including the Open Acces status.
* Once the list is complet, a **publication summary** is computed and a **formatted text** for the entire publicatin list is generated. The text can be copied and **pasted into the Peer Reviewed Publications box** of the Annual Activities Questionnaire, or used for other purposes.

