The BroadStreet Institute
====================

## Introduction

[BroadStreet](http://www.broadstreet.io) is a data and software company for social good. We believe that all people deserve access to the best information possible. BroadStreet builds our software for those working towards community change. We strive to ensure that data is accessible, affordable, and delightful to explore. BroadStreet has thousands of members all over the country. Members include students, non-profit leaders, and executives of multi-state and national organizations. We are proud of the range of our members.

BroadStreet’s COVID-19 Data Project began as an in-house project by BroadStreet to collect county-level coronavirus case (#) and death (#) totals. The COVID-19 Data Project grew to become a non-profit, The BroadStreet Institute which began tThe Community Data Project. The Community Data Project  started as small action teams looking beyond COVID data and has expanded to become multiple tracks and teams focused on collecting data on important public health topics outside of the pandemic.

The Policy Track of the COVID-19 Data Project first created and piloted this concept to create a qualitative dataset about the contents of Community Health Needs Assessments (CHNAs). By comparing health needs, priorities, and other contents, the CHNAs can be systematically analyzed and geographically compared without regard to the specific health system or size. Since its inception, the CHNA Track has moved to the growing Community Data Project, where it has grown to include five data entry (DE) teams, a quality assurance (QA) team, and a data release (DR) team.

##Structure of Dataset

The data is structured and defined in the following way below:
<ul>
<li>Healthcare_Name: Hospital/hospital system name</li>
<li>Street_Address: Street address of hospital/hospital system</li>
<li>City: City where the health entity resides</li>
<li>Zipcode: Zipcode where the health entity resides</li>
<li>State: State where the health entity residess</li>
<li>Associated_Health_System: What health system is associated with this hospital? (if applicable)</li>
<li>Nonprofit: Yes, No, or Blank if unknown</li>
<li>CHNA_Year: What year was the most recent CHNA released?</li>
<li>Service_Area_Type: Choose from the following options based on available info in CHNA</li>
<ul style="list-style-type:circle;">
<li>List of Counties: Service area defined by counties only in CHNA</li>
<li>List of Zip Codes: Service area defined by zip codes only in CHNA</li>
<li>List of Places: Services area defined by cities, villages, or towns in CHNA</li>
<li>Combination: Any combination of the above options</li></ul>
<li>Service_Area_Counties: List of Counties, if applicable (N/A if not applicable)</li>
<li>Service_Area_Zip: List of Zip Codes, if applicable (N/A if not applicable)</li>
<li>Service_Area_Places: List of Places, if applicable (N/A if not applicable)</li>
<li>Health_Needs: List of Health Needs as identified in CHNA</li>
<li>Health_Priorities: List of Health Priorities as identified in CHNA or Implementation Plan</li>
<li>CHNA_URL: Link to CHNA (N/A if not available)</li>
<li>Implementation_URL: Link to Implementation Plan (N/A if not available)</li>
<li>Contact: Contact Name, Email, or Phone Number for CHNA information (N/A if not available)</li>
</ul>
Codebook


##Methods
<ul><li><strong>Data Burst Format</strong></li>
<ul style="list-style-type:circle;"><li>The CHNA Track completes data entry using a data burst format. Data bursts are once-per-week, weekly, synchronous team meetings during which each team member works on the data collection process. During the scheduled time, the team can work together on a Zoom call with their fellow teammates and Team Lead or Assistant Lead. In the event that an intern cannot attend a weekly data burst, he or she communicates closely with the Team Lead and Assistant Lead to ensure that assignments can be completed asynchronously for that particular week. Ultimately, the goal is to create a collaborative work environment where interns feel supported as they complete their weekly data entry assignments.<li></ul>
<li><strong>Data Entry Process</strong></li>
<ul style="list-style-type:circle;"><li>At the beginning of the intern onboarding process, interns are given a comprehensive Data Entry Guide and instructional video detailing how to complete CHNA data entry. They are then placed onto one of five data entry teams, each working on the CHNAs from a different state. Given that no two CHNAs look alike, interns are instructed to emphasize quality over quantity as they complete their assignments. To help achieve this, the CHNA Track utilizes an internal ranking of confidence that interns fill out to indicate their confidence level regarding a particular CHNA data entry assignment (1 = very unsure, 3 = questioning, 5 = positive). These confidence levels are taken into close consideration by the QA Team, which is described in further detail below.</li></ul>
<li><strong>QA Process</strong></li>
<ul style="list-style-type:circle;"><li>The CHNA QA Team was designed as a way to ensure consistency and quality in the data we collect and share. While special attention is paid to CHNA data entries with low confidence level (3 and lower), the QA Team aims to ensure quality and consistency across all of CHNA data. Interns on the QA Team recheck each cell of our spreadsheet for accuracy, utilizing spreadsheet comments and color coding to ensure that all data has been carefully checked. Once this has been done, the QA Team passes along the dataset to the Data Release Team, which is described in further detail below.</li></ul>
<li><strong>Modifications for Release</strong></li>
<ul style="list-style-type:circle;"><li>The CHNA Data Release Team is responsible for taking data that has passed through QA and preparing it for data release on GitHub. The following modifications are made by the Data Release Team:</li>
<ul style=”list-style-type:square;”>
<li>Making sure everything transfers over to a .csv file well</li>
<li>Delete columns that are only relevant for internal communications during the DE process, then shift columns with hospital information to the front of the dataset</li>
<li>Delete interns' names</li>
<li>Rename each column header to be more concise</li>
<li>Make sure punctuation is consistent in health needs/priorities</li>
<li>Remove QA check box</li>
</ul></ul></ul>

##Data Challenges/Changes in Process

The biggest challenge to ensuring quality data is to ensure consistency in our data collection procedures. As an initiative with only a few months of experience, the CHNA Track has continued to undergo tremendous infrastructure change and development in an effort to standardize the way we collect, correct, and clean up data. As we look to the future of the CHNA Track, we look to improve upon the collaborative efforts between our data entry, quality assurance, and data release teams to ensure that our data is clear and accessible to those who access it.

##Future Releases

The CHNA Track is dedicated to continuous improvement as it continues to grow and serve as an increasingly prominent track under BroadStreet’s Community Data Project. As a result, the track is looking forward to exploring several additional initiatives in the coming months. For example, given the wide variety in terminology used by CHNAs to identify health needs and priorities, we are exploring ways to categorize these identifiers under broader categories of health as established by Healthy People 2030. Additionally, we are interested in developing a data visualization team to create visual datasets that help elucidate the relationship between geographic location and health needs and priorities. Finally, we are looking to dive deeper into Implementation Plans to see how well CHNAs translate into actionable outcomes for the communities being served by each hospital or hospital system.

##Suggested Citation
When using data images, downloaded data, or shared document formats, please attribute BroadStreet as well as the original source, when applicable. For examples and more information, review this article which answers the question ["How do I cite BroadStreet?"](https://help.broadstreet.io/article/citations/)


##Contributors

Arslon Humayun, Brenna Jarvis MPH, Kari Schoettler
A full list of the Broadstreet Institute volunteers can be found at [https://covid19dataproject.org/team-2/](https://covid19dataproject.org/team-2/)

##Questions / Feedback

Email the primary contributors at: hello@broadstreet.io
