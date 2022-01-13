---
title: Syllabus
school: CU
year: "2022"
semester: spring
course_name: Security Analytics
coursenum: MSBX 5500
slack: https://securityanalyticss22.slack.com
---

<div><strong><em>Sections</em></strong></div>

{% for item in page.coursenum %}- {{ item }}
{% endfor %}

<div id='nav-bar'></div>

Instructor
: Dave Eargle  ([contact](<mailto:David.Eargle@colorado.edu>))

Class
: See [my.cu.edu](https://buffportal.colorado.edu/) for schedule

Office Hours
: See canvas

Slack
: [{{page.slack}}]({{page.slack}})


# Course Description

This class is offered within the security analytics track of the business
analytics masters at CU Boulder.

This class explores the application of data analytics to the domain of
information security. It uses python machine learning libraries to both build
and deploy models for both supervised and unsupervised modeling algorithms.
Business problem contexts include classifying the likelihood that a file or
website is malicious based on either extracted static indicators or dynamic
behavioral analysis (predictive analytics), as well as network anomaly detection
on organizational network traffic data or on user account usage (unsupervised
machine learning).

Consider this sage prediction from 2020, still relevant for us today:

<blockquote class='blockquote' markdown='1'>

The year 2020 expects to see an increase in the preventative approach of deep
learning environments, which will become outdated and dangerous. TTPs will
continue to evolve cyber threats; we’ll fight AI with AI. Drones hovering
outside office windows will discuss ML and AI to combat the threat landscape.
These AI will announce a strike over Twitter, the first monumental disruption in
2020.

Real-time data and analytics and machine learning and AI creates unpreparedness
by corporations and Big Tech companies. Managed detection engines are built on
human made logic, but keeping this up-to-date against the latest studies costs
almost three million cyber security. Perhaps the most attention raised by
increasingly employed AI-based solutions is our need to reconsider our notions
of what makes a mistake.

_-- Kelly Shortridge, VP of product strategy at Capsule8's, [bot](https://www.cyberscoop.com/2020-cyber-predictions-kelly-shortridge/)._
</blockquote>


# Prereqs

This class has the following prerequisites:
- Proficiency in (or concurrent coursework on) concepts of computer networking
  and information security management.
- Proficiency in the basics of statistics and machine learning, as
  well as in using Python to perform the same.

Students in the security analytics track of the MSBA pass both prerequistes.
MBAs _may_ take the class, but only if they demonstrate competency to me in the
two above prereqs. _This is not a "learn python ML from scratch" class._


# Learning Outcomes

**Synopsis:** Students will use security-related datasets to practice and
demonstrate comprehension of principles of _reproducible data science_ and
_deploying machine learning models_.

Use code versioning and collaboration tools
: Includes:
  * Use Git and Github responsibly
  * Write markdown
  * Submit pull requests

Use cloud computing for data science
: Includes:
  * Spin up Jupyter notebooks on cloud instances. _Fast_.

Do reproducible data science
: Includes:
  * Share your code, its results, and (maybe) your data
  * "Works on my machine": specify environments using tools like `venv`, MyBinder, and Docker

Deploy machine learning models with python
: Includes:
  * "Pickle" (serialize) models
  * Use "pipelines" for generalizable ML processes
  * Choose cutoff thresholds via optimizing F1
  * Create APIs to consume serialized models
  * Deploy models to cloud platforms, such as Heroku or AWS or GCP API ML endpoints


## Communication

Canvas for announcements, and Slack for async watercooler-type banter and help-requests.

You aren't _required_ to read and be aware of _everything_ that happens on slack
to complete assignments. If it comes up in slack that something in the
assignments is wrong, or broken, I'll make an effort to update the assignment
document webpage. Therefore, don't rely on offline, potentially out-of-date
assignment documents.

You _are_ required to be aware of all announcements I make via Canvas.


## Technology Requirements

You need python3 on a computer that you bring to class. Besides that,
you just need a stable internet connection to use cloud computing resources.


## Text Materials

You _must_ grok this book:

Foster Provost and Tom Fawcett (2013), _Data Science for Business: What You Need to Know About Data Mining and Data-Analytic Thinking_. O’Reilly Media. [Available on Amazon](https://www.amazon.com/Data-Science-Business-Data-Analytic-Thinking/dp/1449361323)

Warning -- the kindle version has crummy images. The book is not expensive.



# Assignments

## Labs

This is a labs-based class. I will typically give you at least a week to
complete each assignment. I may assign as many as one lab per week.

Labs may include submitting zip files of your code repositories,
or submitting screenshot-evidence of task completion.

## Readings

I will assign you some readings and associated open-book quizzes from Provost
and Fawcett, and from other sources.

## Final Exam

The final exam will include conceptual questions covering topics from lecture.

# Participation

Most students will earn 80% of these points. Students who are exceptional and go
above and beyond in enhancing the classroom experience may receive a higher
score.

The following list is not comprehensive, but rather an example of items considered for the class participation score:

* Attend and participate in class sessions (attendance is required!)
  * Making good efforts to complete in-class activities
* Participate on the class Slack workspace.
  * Be a community member.
  * Ask good questions
  * Answer questions
  * Use slack reactions


# Point Distribution

| Category | Weight     |
| :------------- | :------------- |
| Labs       | 65       |
| Reading Quizzes       | 5       |
| Participation       | 10       |
| Final Exam       | 20       |


# Late Work

All assignments and projects are to be submitted on time or early, so plan
accordingly. If you must miss class, please submit your assignment early. On
rare occasions, an exception may be granted, allowing the student to submit
the work late with a 20% penalty. Under no circumstances will anything be
accepted more than a week late.





{% include required-syllabus-statements-spring-2022.md %}
