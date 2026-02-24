# Mentors Onboarding

Most steps depend on the status of the mentor in Airtable ‘Mentors’ table, so they are activated when this status changes.

## [**Step 1: When a Form of Interest is Sent**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/mentors/mentors-onboarding/#step-1-when-a-form-of-interest-is-sent)

1. The mentor fills up the form.  
2. ‘Status’ column needs to be **empty** at this point.  
3. Airtable automation [“Mentors 1 – Application Received”](https://airtable.com/appIzQKfwTn5dyPVp/wfl61ZWmsgMcEMbKO) sends the following email:

> Hi\!  
> Thank you for submitting your application to become a mentor in the WordPress Credits Program. We truly appreciate your willingness to contribute your time and expertise to support our students.  
> Please note that it may take several weeks before we are able to review all applications. Once the selection process is complete, we will contact you to let you know whether you have been chosen as a mentor.  
> We are grateful for your patience and interest in being part of this program.  
> Best regards,  
> The WordPress Credits Program Team

## [**Step 2: Vetting**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/mentors/mentors-onboarding/#step-2-vetting)

1. We will vet the mentors applications following [these requirements](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/mentors/mentors-requirements/) and introduce in the Status:  
   * Vetted Positive  
   * Declined  
   * Needs Second Opinion  
   * Needs More Information

## [**Step 3: Onboarding to ‘Vetted Positive’**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/mentors/mentors-onboarding/#step-3-onboarding-to-vetted-positive)

### [**Step 3.1: Invitation to the course (course is closed to the public, access only with invitation link)**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/mentors/mentors-onboarding/#step-3-1-invitation-to-the-course-course-is-closed-to-the-public-access-only-with-invitation-link)

1. When the status changes to ‘Vetted Positive’, the automation [“Mentors 2 – Course”](https://airtable.com/appIzQKfwTn5dyPVp/wfllwUJ5eCs0E4bSK) sends [this email](https://docs.google.com/document/d/1wuWyAAn1qNIUcOuX3eH1SDaNW4nSt9ja071NpmI6yQo/edit?tab=t.jmr6hou6hy9t) to them.

### [**Step 3.2: Course completed – Welcome/Info email**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/mentors/mentors-onboarding/#step-3-2-course-completed-welcome-info-email)

1. When they complete the course, the mentor writes back to education@wordpressfoundation.org to let us know.  
2. We:  
   * Change Status column to ‘Active’.  
   * Create a **filtered view** of the **Student Report** table for **that mentor \+ Status is ‘In Sensei’** with a password protected link.  
   * Create a 1 time link for the password with https://1ty.me.  
   * We add both urls (personal Student Report table and 1ty) to the Mentors table columns ‘Student Report personal table’ and ‘Password for Student Report personal table’  
3. The automation [“Mentors 3 – Welcome”](https://airtable.com/appIzQKfwTn5dyPVp/wfli8FE6SQw08Vdio) gets triggered with all that and sends t[his welcome email (second tab)](https://docs.google.com/document/d/1wuWyAAn1qNIUcOuX3eH1SDaNW4nSt9ja071NpmI6yQo/edit?tab=t.jmr6hou6hy9t) to them.  
4. We invite them to the \#WP-Credits private Slack channel.  
5. We give them access to the sponsors coupon spreadsheet (see link in the \#WP-Credits private Slack channel Canvas).  
6. We give them Editor access to the [Mentor resource folder.](https://drive.google.com/drive/folders/10N1G77WD9ca3zMc612XoPjEjDtZgDYfa?usp=share_link)  
7. Make sure to mark their email in Helpscout as close when finished.

## [**Step 4: Communication to ‘Declined’**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/mentors/mentors-onboarding/#step-4-communication-to-declined)

1. When the status changes to ‘Declined’, the automation [“Mentors 4 – Decline”](https://airtable.com/appIzQKfwTn5dyPVp/wfl5SCmxcQ480wcpP) is triggered and this email is sent automatically:

> Dear \[Full Name\],  
> Thank you sincerely for expressing your interest in supporting and educating students through the WordPress Credits program. We truly appreciate your enthusiasm and your commitment to fostering contributions within the WordPress community.  
> While we would have been delighted to welcome you to the team, after reviewing your application, we found that the information available in your WordPress.org profile was not sufficient to confirm your eligibility to serve as a mentor at this time. We genuinely value the time and effort you invested, and we encourage you to stay involved with the WordPress Credits initiative by contributing in other ways, such as joining discussions in the [WordPress Credits Slack channel](https://wordpress.slack.com/archives/C0959D2M3T8) or helping out with specific tasks in our [GitHub repository](https://github.com/WordPress/WPCredits-Tracker).  
> If you would like to appeal this decision or share additional details about your background, experience, and reasons why you’d be a great fit as a mentor, please reply to this email and provide more context about your involvement with WordPress and any mentoring or teaching experience you may have.  
> We truly appreciate your willingness to contribute to this initiative and would be happy to review your application again once more information is available.  
> Thank you once again for your time, interest, and support.  
> Best regards,  
> The WordPress Credits Program Team

## [**Step 5: Communication to ‘Needs More Information’**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/mentors/mentors-onboarding/#step-5-communication-to-needs-more-information)

When the status changes to ‘Needs More Information’, the automation [“Mentors 5 – Need more info”](https://airtable.com/appIzQKfwTn5dyPVp/wflWv3v4W3kaNCCI1) is triggered sending a email to request more info.
