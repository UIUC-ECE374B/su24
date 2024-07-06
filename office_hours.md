---
layout: default
title: Course Schedules
---
{% if site.archived == true %}
Obviously this course isn't active and there aren't any discussion sections or office hours. But I left a bunch of sample data in the repo to show how the backend works when you need to display a weekly schedule (in this case OHs). It was tricky to get working at the time but I built everything so that you only need to set the time(s) in the people.yml file and everything is beautifully displayed on the schedule table. Super helpful since staff needs to change OH times frequently throughout the semester and all you need to do on your end is to change a few values in the .yml file instead of futzing with a bunch of HTML.   
{% endif %}


#### Lectures

<table id="customers">
  <tr>
    <th> Section </th>
    <th> Time </th>
    <th> Who </th>
    <th> Location </th>
  </tr>
  <tr>
    <td> BL1 </td>
    <td> MTWR at 10:00AM - 11:20AM | F at 12:30PM - 01:30 PM </td>
    <td> Kani </td>
    <td> 2015 ECEB </td>
  </tr>
</table>
&nbsp;

<!-- #### Discussion Sections
<table id="customers">
   <tr>
    <th> Section </th>
    <th> Wednesdays and Fridays at </th>
    <th> Who </th>
    <th> Location </th>
  </tr>
  <tr>
    <td> BYA </td>
    <td> 09:00AM - 09:50AM </td>
    <td> Jack Chen, Yueyi Shen </td>
    <td> 2017 ECEB </td>
  </tr>
  <tr>
    <td> BYB </td>
    <td> 10:00AM - 10:50AM </td>
    <td> Haoyuan You </td>
    <td> 0216 Siebel </td>
  </tr>
  <tr>
    <td> BYC </td>
    <td> 11:00AM - 11:50AM </td>
    <td> Sindhu Vydana </td>
    <td> 4070 ECEB </td>
  </tr>
  <tr>
    <td> BYD </td>
    <td> 12:00PM - 12:50PM </td>
    <td> Sandhya Perumenki </td>
    <td> 4070 ECEB </td>
  </tr>
  <tr>
    <td> BYE </td>
    <td> 01:00PM - 01:50PM </td>
    <td> Weiyang Wang, Sumedh Vemuganti </td>
    <td> 4070 ECEB </td>
  </tr>
  <tr>
    <td> BYF </td>
    <td> 02:00PM - 02:50PM </td>
    <td> Sung Woo Jeon </td>
    <td> 4070 ECEB </td>
  </tr> 
</table>
&nbsp; -->

#### Office hours
Office hours will be conducted by the instructor(s), TAs and CAs. Office hours are not a place to check if your homework solutions are correct (the CAs do not even have access to the homework solutions). They're for learning concepts and working through a problem under the guidance of someone that understands the material. Office hours are meant to help you master the course concepts and assist you in working through any assignments when you are stuck.

Because we have a mix of online and in-person students, most OHs will be held on Zoom (though Kani's and Vishesh's will have an in-person component as well). The Zoom links are as follows: 

<table id="customers">
  <tr>
    <th> Who </th>
    <th> Zoom Link </th>
  </tr>
  <tr>
    <td> Kani </td>
    <td> <a href="https://illinois.zoom.us/j/5828330103?pwd=UkJLNjBpWXFnSytWTHJsVXU4dU1idz09"> Zoom Room </a> </td>
  </tr>
  <tr>
    <td> Sumedh </td>
    <td> <a href="https://illinois.zoom.us/j/3890061261?pwd=R3l3R3Y3SjZmODJxRUpSdUkyaTFUUT09"> Zoom Room </a> </td>
  </tr>
  <tr>
    <td> Vishesh </td>
    <td> <a href="https://illinois.zoom.us/j/7012718197?pwd=OXlvZkdqSlFnVGtlMFVjMjVDTXQrQT09"> Zoom Room </a> </td>
  </tr>
  <tr>
    <td> Siddhant </td>
    <td> <a href="https://illinois.zoom.us/j/5172262578?pwd=VE9sTUpVY1M2NmdndXUvWkVFN3Fhdz09"> Zoom Room </a> </td>
  </tr>
  <tr>
    <td> Rubin </td>
    <td> <a href=""> Zoom Room (TBD) </a> </td>
  </tr>
</table>

Here are the office hour times:

{% include OHs_table.html %}


