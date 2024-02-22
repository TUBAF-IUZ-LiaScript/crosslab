<!--
author:   Mark Jacob
email:    mark.jacob@iuz.tu-freiberg.de
version:  0.1.0
language: en
narrator: US English Female

comment:  This is the second update for colleagues.
          Please let me know if you need more info.

icon: https://upload.wikimedia.org/wikipedia/commons/2/28/Logo_TU_Freiberg.svg

import: https://raw.githubusercontent.com/liaScript/mermaid_template/master/README.md

-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://LiaScript.github.io/course/?https://raw.githubusercontent.com/TUBAF-IUZ-LiaScript/crosslab/main/CL_progress_report_2023_02.md)

# Progress Report 2

    {{0-1}}
> **Author:** Dr. Mark Jacob, IUZ/Languages, TU Bergakademie Freiberg
>
> **Date:** February 22, 2024
>
> **Project:** CrossLab
> This report will provide a brief overview of the **CrossLab consortium project** (hereafter referred to as the **project**).
>
>> **Subproject:** Integration of Remote Labs into English for Specific Purposes Language Courses for students of STEM (science, technology, engineering and mathematics) at institutions of Higher Education (hereafter referred to as the **subproject**). The updated status of the subproject will be reviewed, covering details on work completed, work in progress and work remaining.

   {{1}}
```mermaid @mermaid
flowchart TB
    CL((CrossLab)):::yellow
    classDef orange fill:#d80,stroke:#000,stroke-width:2px
    classDef green fill:#5c0,stroke:#000,stroke-width:2px
    classDef blue fill:#6ce,stroke:#000,stroke-width:2px
	classDef yellow fill:#ff0,stroke:#000,stroke-width:2px
	CL-->A(Teaching)
	CL-->B(Technology)
	CL-->C(Organisation)
    A:::blue-->|Consortium project|D(1.Using remote labs for inquiry-based learning<br>2.Understanding remote labs as complementary<br>3.Training and Educating)
    B:::orange-->|Consortium project|E(1.Using established software solutions<br>2.Enabling LMS integration<br>3.Enhancing reliability)
	C:::green-->|Consortium project|F(1.Providing a platform for remote labs<br>2.Expanding the range on offer<br>3.Networking internationally)
	D:::blue
    E:::orange
	F:::green
    D-->|IUZ subproject|G:::blue
    E-->|IUZ subproject|H:::orange
    F-->|IUZ subproject|I:::green
    G(1.Microcontroller and LED strip project<br>2.Professional skills for computer scientists<br>3.Invitation to D2C2 Werkstatt- und Laborpause)
    H(1.Edrys and C#<br>2.LiaScript in OPAL<br>3.Remote and semi-remote solutions)
    I(1.remote-labs.org<br>2.LED strip -> LED cube<br>3.IUGB Cote d'Ivoire)
    P:::yellow
    P(Perpetuating<br>remote labs)
    G-->P
    H-->P
    I-->P
```

## **Overview**

    {{0-1}}
> **Project Facts and Figures**
>
> -   start date of project: August 1, 2021
> -   end date of project: July 31, 2024
> -   extension of project: December 31, 2025
> -   Universties involved:
>
>  - TU Bergakademie Freiberg (Lead partner)
>  - TU Ilmenau
>  - TU Dortmund
>  - Nordakademie
>
> -   Funded by Stiftung Innovation in der Hochschullehre (ca. €5 million)
>
>> **Subproject Facts and Figures**
>>
>> -   start date of subproject: February 15, 2022
>> -   end date of subproject: July 31, 2024
>> -   extension of subproject: December 31, 2025
>> -   Departments involved (TUBAF unless otherwise stated):
>>
>>  - IUZ/ Languages (Lead partner)
>>  - Department of Computer Science
>>  - Department of Chemistry
>>  - Department of Didactics, TU Dortmund
>>
>> -   Funded by Stiftung Innovation in der Hochschullehre (0.5 *Wissenschaftlicher Mitarbeiter* Research Associate)


    {{1-2}}
> **Project Purpose**
>
> CrossLab, funded by the Foundation for Innovation in Teaching in Higher Education,  is a German consortium project that aims to build a network of remote laboratories which are accessible for students from universities in Germany and potentially worldwide. With this, possibilities are opened up for students to experience a wider range of facilities than are available at their own institutions.
>
> The CrossLab project aims to define the **technical**, **didactic** and **organizational** solutions for open digital laboratory objects, which can be combined as required in a learning environment for student-centered teaching and learning.
>
>> **Subproject Purpose**
>>
>> The aim of English language courses at TU Bergakademie Freiberg are to extend the effectiveness of a student's knowledge and use of the English language from general contexts covered during the 8 to 10 years typically spent learning English at school to those specific to academia and to the subject area of the degree course being taken. With this in mind, the approach of the language courses in Freiberg is one of subject-sensitive language teaching.
>>
>> The purpose of the subproject is to maximize the subject-sensitivity of the language teaching by integrating remote labs into the language laboratory, that is, into the English language courses for students of STEM subjects at institutions of Higher Education.

    {{2-3}}
> **Project Scope**
>
> There are four German partner universities involved in the project, each already having developed a number of remote laboratories in the fields such as engineering, chemistry, physics and computer science. The project aims to bring the operation of these remote labs onto a single platform and to develop didactic standards for their use in university courses. New remote laboratory facilities are being developed within the partner universities and eventually these resources will be available to students at other universities in Germany and across the globe.
>
>> **Subproject Scope**
>>
>> The scale of the subproject is rather small in that only one English language instructor is involved and therefore the materials and methods developed will be implemented initially in only three groups of first-year (second semester) students in the course *Introduction to English for Specific Purposes*:
>>
>> - Group 1, Robotics (ROB) and Geoinformatics/Geophysics (BGIP)
>> - Group 2, Mathematics (Mm), Business Mathematics (BWM) and Computer Science (BAI)
>> - Group 3, Chemistry (BCH and Ch)
>>
>> Implementation of the materials and methods will require 3 sessions of the summer semester. In addition to the planned implementations, the subproject will also network with external partners to assist in making the CrossLab infrastructure available to students in other countries, in particular countries in Africa.

    {{3-4}}
> **Project Activities**
>
> Within the project, there are a number of working groups focussing on the technical aspects of building up a platform for the remote laboratories as well as a didactics group, which deals with the integration of the remote laboratories into university teaching. Additionally, competitions have taken place at the four partner universities, in which teaching staff can win funding to develop their own remote laboratories. For more information see the project website https://cross-lab.org/.
>
>> **Subproject Activities**
>>
>> Within the subproject, a student assistant has been hired to develop the software and hardware necessary for creating a remote lab that can be used as a test case for implementing remote labs in English lessons. For more information on this, please refer to the section on work completed.

## **Subproject status**

    {{0-1}}
>> **Work Completed**
>>
>> Year 1
>>
>> Year 2

    {{1-2}}
>> **Work in Progress**

    {{2-3}}
>> **Work Remaining**

    {{3-4}}
>> **Plan for extension**




