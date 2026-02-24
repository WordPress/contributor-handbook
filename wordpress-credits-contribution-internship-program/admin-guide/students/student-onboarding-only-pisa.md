# Student Onboarding (only Pisa)

Most steps depend on the status of the student in Airtable ‘Students’ table, so they are activated when this status changes.

In all cases (EXCEPT the last 2 steps, 4th and 5th), the email has been condition to be sent only when **Pisa University** is the Student’s institution.

## [**Step 1: When a Form of Interest is Sent**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/students/student-onboarding-only-pisa/#step-1-when-a-form-of-interest-is-sent)

1. The student fills up the form and indicates **‘Pisa University’** as their institution.  
2. ‘Status’ column needs to be **empty** at this point.  
3. After submitting the form, Airtable automation [“Email – \[EN\] UniPi – Institution First Contact”](https://airtable.com/appIzQKfwTn5dyPVp/wfl1Zzavd6hSvH6Fo) sends an email asking the student to book a meeting with Isotta (see [this template](https://secure.helpscout.net/settings/inbox/348355/saved-replies/3932399) as reference) with education@wordpressfoundation.org in copy.

## [**Step 2: After the Individual Meeting with Isotta**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/students/student-onboarding-only-pisa/#step-2-after-the-individual-meeting-with-isotta)

1. Isotta applies the status **‘Interested’** in the ‘Status’ column.  
2. Airtable automation [“Email – \[IT\] UniPi – Richiesta Dati Tirocinante”](https://airtable.com/appIzQKfwTn5dyPVp/wfl0tlmLGMmgb0Zzq) gets triggered and sends the email asking for all information needed for the Agreement (see [this template](https://secure.helpscout.net/settings/inbox/348355/saved-replies/3910748) as reference) with education@wordpressfoundation.org in copy.

## [**Step 3: Agreement Signature and Process**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/students/student-onboarding-only-pisa/#step-3-agreement-signature-and-process)

1. Students provide all needed information.  
2. Isotta prepares the agreement, signs it, and sends it to the student and asks the student to sign it and to complete the signature round (tutor \+ send to the internship office).  
3. The student needs to confirm Isotta that the internship office has activated the project.  
4. **When the project has been activated on the internship portal**, the next step can be started.

## [**Step 4: Welcome Email to the Course**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/students/student-onboarding-only-pisa/#step-4-welcome-email-to-the-course)

When the student in the “Students” table match these conditions:

1. **Full Name** is not empty  
2. **Email** is not empty  
3. **Educational** Institutions is not empty  
4. **Status** is **In Sensei**  
5. **Mentor** is not empty  
* The automation [“Add students to Students Reports and Feedback”](https://airtable.com/appIzQKfwTn5dyPVp/wflXg1xFuiCSG0pXZ) creates a record for the student in ‘Students Reports’ and ‘Feedback’.  
* The automation [“Email – \[EN\] – Student Welcome Email”](https://airtable.com/appIzQKfwTn5dyPVp/wflFkVNm8tTIBZ839) sends the welcome email with the mentor and education@wordpressfoundation.org in copy. That email includes step-by-step instructions to start and their personal link to complete their Student Reports table (here are the [animated instructions on how that works with Fillout from the student point of view](https://docs.google.com/document/d/1mc1oNe-IGzzGUTPF4SjvWp_1QK6pgttGt9mRdxQ4P-8/edit?tab=t.0)).

## [**Step 5: Graduation**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/students/student-onboarding-only-pisa/#step-5-graduation)

See [Certificate & Graduation](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/students/certificate-graduation/).  
