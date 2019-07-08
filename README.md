
# lonshines planning software

![lonshines Logo](https://github.com/lonshines/schedule/blob/master/images/logo.png)

Schedule employees at your company

## Instructions

In the following small tutorial we will sign in as a demo administrator of a fictive company called Umbrella Corporation. We will subsequently
create a new task for an employee at Umbrella Corporation by masquerading his account. Finally by logging in as the employee (in a different browser)
we will review and approve the task belonging to the employee.

### Sign in as admin:

Sign in as the admin of Umbrella Corporation at the [login](http://www.lonshines.com/users/sign_in) page.

    $ Email: admin@umbrellacorp.com
    $ Password: admin_at_umbrellacorp

### Instructions to create a task for an employee

Masquerade an employee and create a new task for the employee by following this [link](http://www.lonshines.com/users/masquerade/2).

You are now masquerading USER 2. You can interact with the user account with the same privileges as the account owner with the exception of the calendar tab (calendar tab is not available for employees). Next go to the [calendar tab (only available for the administrator)](http://www.lonshines.com/calendar) while masquerading user 2.

Click and drag inside the calendar to create a new task for the employee. In the appearing overlay form "New Schedule" choose a color and a title. For testing
purpose create a task in the past. Use the arrows above the calendar to go back one day and create a task there.

## Instructions for an employee     

    $ OPEN IN A SECOND BROWSER (Firefox, Chrome, Safari, Opera, ..)

### Sign in as an employee:

Sign in as Brad Hilfiger at the [login](http://www.lonshines.com/users/sign_in) page.

    $ Email: b.hilfiger@umbrellacorp.com
    $ Password: employee_at_umbrellacorp

### Instructions to review tasks as an employee

Review the tasks in the [waiting for approval](http://www.lonshines.com/waitingforapproval) tab.

### Instructions to approve tasks as an employee

Press the blue "Approve all" Button above the calendar list view.

#### ALL YOUR TASKS SCHEDULED BY THE ADMINISTRATOR OF THE UMBRELLA CORPORATION ARE NOW BEING MARKED AS ONGOING OR FINISHED

***

### Approved and upcoming tab: Instructions

#### See your approved tasks at the [approved](http://www.lonshines.com/approved) tab

#### Review your upcoming tasks at the [upcoming](http://www.lonshines.com/upcoming) tab 

#### Color code for upcoming tasks (customizable)
**Red**: Approve this change
**Yellow**: Approve this change, title, start, end
**Green**: No change possible anymore, title, start, end

## etc.etc.etc. Use on your own will and determination. Create new users [here](http://www.lonshines.com/users/sign_up). 
No worries, emails to register users are not sending. 

### Create more employees and manage all of them

You find the masquerade "Login As User" Link for every user on the [masquerade  overview](http://www.lonshines.com/admin/users) page. You have to be logged in as an admin. You will often come back to this dashboard or save the appropriate links to each employee's account as bookmarks.

## ATTENTION: THIS DEMO APP AUTOMATICALLY DELETES THE DATABASE EVERY 10 MINUTES

Lonshines itself is hosted on heroku on a free dyno that goes to sleep. It can take some time to spin up the dyno. If you experience performance issues, it is likely because of an idling dyno.

## Customization or things on the roadmap, handled by requests

- Possibility as a planner to send the tasks data by email.

- Bill all your employees for a special accommodation and event demi-année.
How do you store my credit card? 
By default there is Stripe as a payment provider to securely store your card in a fully PCI compliant, SSL, and AES-256 bit encrypted server.
Read more here: https://jumpstartrails.com/jumpstart/docs/billing

- Create announcements -free

- Configuration to connect with Omniauth providers so users can register or sign in with their social accounts

- Overview page of all employees & tasks (needs Fullcalendar.io premium license)

- Statistics for each employee

- Create new teams with team specific tasks, where only the team lead has to approve all team related tasks

- Send SMS / Push text messages for scheduling tasks and changes

For requests to host longshines planning software on your Domain, your Heroku Subdomain or your Intranet
use the form below.

[Work request](https://docs.google.com/forms/d/e/1FAIpQLSdj1m2npsjclaitdLtWj1pUdYIW_wba3oO6kpY7mNeFL2qPYQ/viewform)

> If you want to build upon [Jumpstartpro](https://jumpstartrails.com) in the planning/scheduling space, feel free to share your prototype on [Github](https://github.com/lonshines/schedule). We are hiring.