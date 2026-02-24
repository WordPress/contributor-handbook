# Institutions Onboarding

Most steps depend on the status of the Institution in Airtable ‘Institutions’ table, so they are activated when this status changes.

## [**Step 1: When a Form of Interest is Sent**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/institutions/institutions-onboarding/#step-1-when-a-form-of-interest-is-sent)

1. The institution fills up the form from ‘Institutions’ table.  
2. The form sends automatically an email to education@wordpressfoundation.org.  
3. Airtable automation [“Institutions 1 – Application Received”](https://airtable.com/appIzQKfwTn5dyPVp/wflD8QmeUqka2JdA4) sends an email asking the contact to book a meeting (the person of contact from the team responsible for the calendar link depends on the institution country, see Airtable ‘Countries’ and ‘Team members’ tables) or continue as discussed during the previous call (see [this template](https://secure.helpscout.net/settings/inbox/348355/saved-replies/3950163) as reference).

   ## [**Step 2: When called scheduled**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/institutions/institutions-onboarding/#step-2-when-called-scheduled)

1. Manually update To Follow Up \= Yes in the ‘Institutions’ table.

   ## [**Step 3: After the call**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/institutions/institutions-onboarding/#step-3-after-the-call)

1. Manually update ‘Status’ column in the ‘Institution’ table to:  
* Interested – ‘Agreement Sent’  
* Not interested – ‘Not moving forward’  
* Maybe later – ‘Revisit Later’

  ### [**Step 3.1: ‘Agreement Sent’ status added**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/institutions/institutions-onboarding/#step-3-1-agreement-sent-status-added)

1. Agreement document is sent to the institution.  
2. Institution is expected to review and sign the agreement.  
3. Follow up communication as needed until agreement is signed.

   ### [**Step 3.2: ‘Not moving forward’ status added**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/institutions/institutions-onboarding/#step-3-2-not-moving-forward-status-added)

1. Nothing else happens.

   ### [**Step 3.3: ‘Revisit Later’ status added**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/institutions/institutions-onboarding/#step-3-3-revisit-later-status-added)

1. The automation [“Institutions – Revisit Later – Follow up date”](https://airtable.com/appIzQKfwTn5dyPVp/wflsJQjfPDBqAgIBM) set up the ‘Days to Follow-Up’ column to 60\.  
2. A 2 months in the future date is set up automatically in the ‘Follow-Up date’ column.

   ## [**Step 4: Agreement signed**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/institutions/institutions-onboarding/#step-4-agreement-signed)

   ### [**Step 4.1: ‘Confirmed’ status added**](https://make.wordpress.org/handbook/wordpress-credits-contribution-internship-program/admin-guide/institutions/institutions-onboarding/#step-4-1-confirmed-status-added)

1. Manually update ‘Status’ column in the ‘Institution’ table to ‘Confirmed’  
2. Institution is now officially onboarded and ready to begin the program.  
3. Further communication and coordination begins as per program requirements.

