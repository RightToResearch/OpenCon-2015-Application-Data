#OpenCon 2015 Application Open Data 

The purpose of this document is to accompany the public release of data collected from OpenCon 2015 applications. 
Download & Technical Information

The data can be downloaded in CSV format from GitHub here: https://github.com/RightToResearch/OpenCon-2015-Application-Data

The file uses UTF8 encoding, comma as field delimiter, quotation marks as text delimiter, and no byte order mark.

#License and Requests

This data is released to the public for free and open use under a CC0 1.0 license. 

We have a couple of requests for anyone who uses the data. First, we’d love it if you would let us know what you are doing with it, and share back anything you develop with the OpenCon community (#opencon / @open_con ). Second, it would also be great if you would include a link to the OpenCon 2015 website (www.opencon2015.org) wherever the data is used. You are not obligated to do any of this, but we’d appreciate it!

#Data Fields

<table cellpadding="0" cellspacing="0" class="c9">

<tbody>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">Unique ID</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">This is a unique ID assigned to each applicant. Numbers were assigned using a random number generator.</span>

</td>

</tr>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">Timestamp</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span>This was the timestamp recorded by google forms. Timestamps are in EDT (Eastern U.S. Daylight Time). Note that the application process officially began at 1:00pm EDT June 1 ended at 6:00am EDT on June 23\.</span> <span>Some applications have timestamps later than this date, and this is due to a variety of reasons including exceptions granted for technical difficulties, error corrections (which required re-submitting the form), and applications sent in via email and later entered manually into the form.</span> <sup>[[a]](#cmnt1)</sup>

</td>

</tr>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">Gender</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">Mandatory. Choose one from list or fill-in other. Options provided: Male, Female, Other (fill in).</span>

</td>

</tr>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">Country of Nationality</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">Mandatory. Choose one option from list.</span>

</td>

</tr>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">Country of Residence</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">Mandatory. Choose one option from list.</span>

</td>

</tr>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">What is your primary occupation?</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">Mandatory. Choose one from list or fill-in other. Options provided: Undergraduate student; Masters/professional student; PhD candidate; Faculty/teacher; Researcher (non-faculty); Librarian; Publisher; Professional advocate; Civil servant / government employee; Journalist; Doctor / medical professional; Lawyer; Other (fill in).</span>

</td>

</tr>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">Select the option below that best describes your field of study or expertise</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">Mandatory. Choose one option from list.</span>

</td>

</tr>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">What is your primary area of interest within OpenCon’s program areas?</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">Mandatory. Choose one option from list. Note: for the first approximately 24 hours the options were listed in this order: Open Access, Open Education, Open Data. After that point, we set the form to randomize the order, and noticed an immediate shift in the distribution of responses.</span>

</td>

</tr>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">Are you currently engaged in activities to advance Open Access, Open Education, and/or Open Data?</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">Mandatory. Choose one option from list.</span>

</td>

</tr>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">Are you planning to participate in any of the following events this year?</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">Optional. Choose all that apply from list. Multiple selections separated by semi-colon.</span>

</td>

</tr>

<tr class="c4">

<td class="c12" colspan="1" rowspan="1">

<span class="c11">Do you have any of the following skills or interests?</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">Mandatory. Choose all that apply from list or fill-in other. Multiple selections separated by semi-colon. Options provided: Coding; Website Management / Design; Graphic Design; Video Editing; Community / Grassroots Organizing; Social Media Campaigns; Fundraising; Communications and Media; Blogging; Advocacy and Policy; Event Logistics; Volunteer Management; Research about OpenCon's Issue Areas; Other (fill-in).</span>

</td>

</tr>

</tbody>

</table>

#Data Collection & Cleaning

This data consists of information collected from people who applied to attend OpenCon 2015. In the application form, questions that would be released as Open Data were marked with a caret (^) and applicants were asked to acknowledge before submitting the form that they understood that their responses to these questions would be released as such. The questions we released were selected to avoid any potentially sensitive personal information, and to minimize the chances that any individual applicant can be positively identified.

Applications were formally collected during a 22 day period beginning on June 1, 2015 at 13:00 EDT and ending on June 23 at 06:00 EDT. Some applications have timestamps later than this date, and this is due to a variety of reasons including exceptions granted for technical difficulties, error corrections (which required re-submitting the form), and applications sent in via email and later entered manually into the form. 

Applications were collected using a Google Form embedded at http://www.opencon2015.org/attend, and the shortened bit.ly link http://bit.ly/AppsAreOpen was promoted through social media. 

The primary work we did to clean the data focused on identifying and eliminating duplicates. We removed all duplicate applications that had matching e-mail addresses and first and last names. We also identified a handful of other duplicates that used different e-mail addresses but were otherwise identical. In cases where duplicate applications contained any different information, we kept the information from the version with the most recent timestamp. 

We made a few minor adjustments in the country field for cases where the entry was obviously an error (for example, electing a country listed alphabetically above or below the one indicated elsewhere in the application). We also removed one potentially offensive comment (which did not contain an answer to the question) from the Gender field and replaced it with “Other.”

#About OpenCon

OpenCon 2015 is the student and early career academic professional conference on Open Access, Open Education, and Open Data and will be held on November 14-16, 2015 in Brussels, Belgium. It is organized by the Right to Research Coalition, SPARC (The Scholarly Publishing and Academic Resources Coalition), and an Organizing Committee of students and early career researchers from around the world. The meeting will convene students and early career academic professionals from around the world and serve as a powerful catalyst for projects led by the next generation to advance OpenCon's three focus areas—Open Access, Open Education, and Open Data.

A unique aspect of OpenCon is that attendance at the conference is by application only, and the majority of participants who apply are awarded travel scholarships to attend. This model creates a unique conference environment where the most dedicated and impactful advocates can attend, regardless of where in the world they live or their access to travel funding. The purpose of the application process is to conduct these selections fairly. This year we were overwhelmed by the quantity and quality of applications received, and we hope that by sharing this data, we can better understand the OpenCon community and the state of student and early career participation in the Open Access, Open Education, and Open Data movements. 

#Questions

For inquires about the OpenCon 2015 Application data, please contact Nicole Allen at nicole@sparc.arl.org. 
