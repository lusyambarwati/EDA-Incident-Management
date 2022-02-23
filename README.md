# EDA-Incident-Management
##  Incident Management

In ITIL terminology, an ‘incident’ is defined as:<br/> 

An unplanned interruption to an IT service or reduction in the quality of an IT 
service. Failure of a configuration item that has not yet impacted service is also 
an incident, for example failure of one disk from a mirror set.<br/>

Incident Management is the process for dealing with all incidents; this can 
include failures, questions or queries reported by the users (usually via a 
telephone call to the Service Desk), by technical staff, or automatically detected 
and reported by event monitoring tools.

###  Purpose/goal/objective
The primary goal of the Incident Management process is to restore normal 
service operation as quickly as possible and minimize the adverse impact on 
business operations, thus ensuring that the best possible levels of service quality 
and availability are maintained. ‘Normal service operation’ is defined here as 
service operation within SLA limits.

### Value to business 

The value of Incident Management includes:<br/>
- The ability to detect and resolve incidents which results in lower downtime to the business, which in turn means higher availability of the service. This means that the business is able to exploit the functionality of the service as designed. 
- The ability to align IT activity to real-time business priorities. This is because Incident Management includes the capability to identify business priorities and dynamically allocate resources as necessary. 
- The ability to identify potential improvements to services. This happens as a result of understanding what constitutes an incident and also from being in contact with the activities of business operational staff. 
- The Service Desk can, during its handling of incidents, identify additional service or training requirements found in IT or the business.

Incident Management is highly visible to the business, and it is therefore easier to 
demonstrate its value than most areas in Service Operation. For this reason, 
Incident Management is often one of the first processes to be implemented in 
Service Management projects. The added benefit of doing this is that Incident 
Management can be used to highlight other areas that need attention – thereby 
providing a justification for expenditure on implementing other processes

### Metrics 
The metrics that should be monitored and reported upon to judge the efficiency
and effectiveness of the Incident Management process, and its operation, will 
include: 
- Total numbers of Incidents (as a control measure) 
- Breakdown of incidents at each stage (e.g. logged, work in progress, closed etc) 
- Size of current incident backlog 
- Number and percentage of major incidents 
- Mean elapsed time to achieve incident resolution or circumvention, broken down by impact code 
- Percentage of incidents handled within agreed response time (incident response-time targets may be specified in SLAs, for example, by impact and urgency codes) 
- Average cost per incident 
- Number of incidents reopened and as a percentage of the total 
- Number and percentage of incidents incorrectly assigned 
- Number and percentage of incidents incorrectly categorized 
- Percentage of Incidents closed by the Service Desk without reference to other levels of support (often referred to as ‘first point of contact’) 
- Number and percentage the of incidents processed per Service Desk agent 
- Number and percentage of incidents resolved remotely, without the need for a visit 
- Number of incidents handled by each Incident Model 
- Breakdown of incidents by time of day, to help pinpoint peaks and ensure matching of resources.
##### In this notebook, I will perform Exploratory Data Analysis (EDA) on Incident management process enriched event log Data Set by using some metrics above
