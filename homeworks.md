---
layout: default
title: Homeworks
---

<table id="customers">
  <tr>
    <th> # </th>
    <th>Topic</th>
    <th>|Problems|</th>
    <th>Assigned</th>
    <th>Due</th>
    <th>Questions</th>
    <th>Solutions</th>
  </tr>
  {% for iteml in site.data.homework %}  
    {% assign item = iteml[1] %}
    <tr>
        <td>{{ item.num }}</td>
        <td> {{ item.topic }} </td>
        <td> {{ item.num-problems }} </td>
        <td> {{ item.assigned-date | date: "%b %d" }} </td>
        <td> {{ item.due-date | date: "%b %d" }} </td>
        <td> 
            {% if item.questions-link %}
            <a href="{{ site.base }}{{ item.questions-link }}"
                style="text-decoration: none">
                <img class="homework-icon"
                    alt="Homework {{ item.num }} Questions"
                    title="Homework {{ item.num }} Questions"
                    src="{{ site.base }}/img/icons/lab_questions.png" />
            </a>
            {% endif %}
        </td>
        <td> 
            {% if item.solutions-link %}
            <a href="{{ site.base }}{{ item.solutions-link }}"
                style="text-decoration: none">
                <img class="homework-icon"
                    alt="Homework {{ item.num }} Questions"
                    title="Homework {{ item.num }} Questions"
                    src="{{ site.base }}/img/icons/lab_solutions.png" />
            </a>
            {% endif %}
        </td>
    </tr>        


  {% endfor %}

</table>

&nbsp;

Couple things to note about homeworks:
- Homeworks are to be completed **individually**. Yes, this is a change from previous semesters but we have [good reason](/resources/No-group-assignments.html) to believe that the group homeworks hamper learning instead of facilitate it. 
- Because this is a summer course, homeworks will be due the Tuesday the week after the material is covered. I usually like to give more lead time but the summer session is short and intense. Regardless, you have lecture recordings, so you can start homewokrs if you anticipate a scheduling issue. Each HW assignment corresponds to a particular lecture. I recommend doing each problem the evening after the corresponding lecture to ensure that the material is fresh and you can complete the problem quickly.  
- It's a bad idea to skip homeworks. Homeworks and labs are where we get inspiration for exam problems. 
- You can find a sample HW LaTeX template [here](/materials/homeworks/hwt_B.tex).
- This half of the course will allow 2 homework problems to be dropped. 

### Homework Logistics: How to submit

- All homework solutions must be submitted electronically via Gradescope. Submit one PDF file for each numbered homework problem. Gradescope will not accept other file formats such as plain text, HTML, LaTeX source, or Microsoft Word (.doc or .docx).
- **Homeworks are due by 6 AM** of their due date. 
- You **should not** use Canvas to keep track of homeworks or any other course policies and logistics. **Canvas is a gradebook, that's all.**  
- You will be registered with Gradescope using your university email address. If you can't access Gradescope let the course staff know. 
- All homework assignments must be completed and submitted individually this semester. No group assignments. 
- As error correction, each submitted homework solution should **include the following information in large friendly letters at the top of every page/problem**. 
    - The homework number
    - The problem number
    - Name + netid
- **We will not accept late homework for any reason.** To offset this rather draconian policy, we have a very generous number of homework drops (compared to other sections/courses). Also remember you can always resubmit a problem to gradescope. There is zero reason to wait until the last minute to submit your work.  

### Homework Grading Policies: 

- **Homeworks** are graded by the entire course staff, within Gradescope. All numbered homework problems are worth the same amount. 
- Under normal circumstances, all homework should be graded within two weeks of submission. However, your graders also have significant responsibilities and may take longer to grade the homeworks. This is all to say one thing: **homeworks should not be used to check your mastery of the material.** After the due date the homework solutions are immediately posted and you can check your answers against the solutions. Every semester students email me that they got something wrong on the exam because the HW were not graded beforehand. I am sorry but I simply do not have the resources to ensure that homeworks are always returned before an exam and so, you should verify your submission against the posted solutions and ping us on Piazza or come to OHs if you don't understand a discrepancy.  
- Homework grades are **not** a proof of correctness and cannot be used to argue for correctness on an exam. 
- Partial credit is given for work that is very close to being correct. 
- **We will give zero points for long and tedious solutions** (i.e., solutions that are longer than the official solutions by a significant amount). We reserve the right of not even reading your solution if it exceedingly and unnecessarily long. If your solutions seems too long - rewrite it to be short and precise. 
- This semester I am limiting solutions text to be **300 words long max** per problem. It is incredibly important to be able to convey complex idea as concisely as possible and I think this is good practice. I highly suggest using figures(flowcharts, graphics)/equations(useful for recurrences) to cut down on the word vomit. 
>If I had more time, I would have written a shorter letter. 
><cite> - [Unknown](https://www.lb7.uscourts.gov/documents/314-cv-921.pdf) <cite>
