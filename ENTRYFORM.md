



# Hackathon Submission Entry form

## Team name

Team - InSpire

## Category

Best addition to the MVP Sitecore site

## Description
 - **Module Name**: MVP+

 - **Module Purpose**
 
This module objective to make user's life easy by adding additional feature on mentor program page and enhanced search experience on Directory Page. 

**ENHANCEMENTS**:
1. **Mentor-Program**: Now mentee can directly apply for Mentor Program from mvp website. On click of Apply now on Mentor Program page after providing email-ID, an email will be sent to [mvp-program@sitecore.com](mailto:mvp-program@sitecore.com?subject=Mentor%20Program) . 
2. **Directory**: Restrict users to search only string on Directory Page. Prior to this enhancement - user were able to search special & numeric characters.


 **- What problem was solved**
 
Earlier from MVP Site, user can get only mentor program details. And to request for Mentor - user were sending email from another url/tab/platform.
Now we are making it simple and single click to request for Mentor.

On Directory Page, we noticed that there were issues like results are coming on search of special characters, numbers.

**How does this module solve it**
 
Firstly, we have made html & JS change by extending existing data/logic.
and then written send email WEB API Logic.

## Video link

[MVP+ Video Url](https://www.youtube.com/watch?v=1g-WiI6LalA)


## Pre-requisites and Dependencies

- Dependencies

1. Sitecore 10.2 & CLI using Docker
2. Sitecore MVP Base Setup
3. SMTP details

## Installation instructions

- Setup Sitecore MVP Site [Setup Instructions](https://github.com/Sitecore/MVP-Site#readme)



### Configuration


## Usage instructions

Open Sitecore MVP Site and go to Mentor Program Page.
To request for Mentor, Please fill your email address and send request.

On Directory Page,
User can feel the magic that - now will not able to search special characters, numeric keys - Only can search string.

Below are the screenshots in sequence for reference

![Mentor Program Page](docs/images/mentor-program-page.PNG?raw=true "Mentor Program Page")

![Directory Page](docs/images/directory-page.PNG?raw=true "Directory Page")


## Comments
