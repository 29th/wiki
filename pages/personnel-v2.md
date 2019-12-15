---
title: Personnel v2
permalink: /Personnel_v2
layout: page
author: JHill
date: 2015-01-23T20:19:28Z
category: 
---
# Events

## Absent for a drill

What was previously called “posting an absence” is now called “posting a
leave of absence” or “LOA.” Being absent without a leave of absence
posted is now called “absent without leave” or “AWOL.” Members with
three or more AWOLs within thirty days are subject to discharge.

1.  Click the event on the calendar
2.  Click Post LOA within 24 hours of the event

## Long-term absence

What was previously called “taking an LOA” is now called “taking an
extended leave of absence” or “ELOA.” These have not been implemented in
the new system yet. In the meantime:

1.  The member posts their Extended LOA request as a new thread in the
    Adjutant Corps forum
2.  Upon return, the member must reply to the thread to end the ELOA

## Creating Drills

Until drill/event creation is automated,

1.  Go to [admin/events](http://api.29th.org/admin/events) and create a
    record for each event
    1.  Fill in Date/Time, Unit, Type (Basic Combat Training), Mandatory
        (true)

## Identifying AWOL Members

Members with 3 or more AWOLs (absent without leave) are subject to
discharge

1.  Go to the unit’s page and click AWOLs
2.  Review the Adjutant Corps Extended LOAs to check if any members are
    on ELOA

# Members

## Promoting

1.  Post promotion thread on forum
2.  Go to [admin/promotions](http://api.29th.org/admin/promotions) and
    add a record
    1.  Fill in Member, Date, Old Rank, New Rank, Forum (Vanilla), Topic
        ID (of the post you made)
3.  Post the promotion details in the forums

## Giving an Award

1.  Post award thread on forum
2.  Go to [admin/awardings](http://api.29th.org/admin/awardings) and add
    a record
    1.  Fill in Member, Date, Award, Forum (Vanilla), Topic ID (of the
        post you made)
3.  Post the award details in the forums

## Transferring

1.  Go to the member’s profile and click the Admin Tab then click Assign
    1.  Select the unit they’re transferring from in Transfer From
    2.  Platoon HQ can transfer someone within their platoon. Between
        platoons requires Company HQ. Between companies requires
        Battalion HQ.
2.  Post the transfer details in the forums

## Discharging

1.  Post discharge thread on forum
2.  Go to the member’s profile and click Discharge, then fill out the
    form
3.  Verify they have lost all access
    1.  In member’s profile, Active Class should no longer say Combat
    2.  In member’s forum profile, Roles should only include Public
        Member
4.  Post the discharge details in the forums

## Issuing a Demerit

1.  Post the demerit thread on forum and lock the thread
2.  Go to [admin/demerits](http://api.29th.org/admin/demerits) and add a
    record
    1.  Fill in Member, Author, Date, Reason, Forum (Vanilla), Topic ID
        (of the post you made)

# Staff Offices

## New Assignment

1.  Go to the member’s profile and click Assign
    1.  Leave Transfer From empty if it’s a new assignment

## End Assignment

1.  Go to the member’s service record and click the Edit button on the
    assignment
    1.  Put today’s date as the End Date

# Weapon Passes

## Identifying Recruiters

1.  Identify recruiters by reviewing each accepted enlistment

## Adding Passes

1.  Add the pass to the passes list on the forums
2.  Notify the member via PM about the pass

# Finance

## Managing Records

1.  Go to [admin/finances](http://api.29th.org/admin/finances) and add a
    record

# Lighthouse

## Enlistments

1.  Recruit goes to 29th.org, clicks Enlist, and follows the
    instructions
    1.  Recruit creates an account on the forums
    2.  While logged in, recruit fills out the enlistment form
    3.  Recruit bookmarks the page they’re taken to (the enlistment)
2.  Enlistment liaisons monitor enlistments page for new Pending
    enlistments
    1.  Communicate with the recruit via the Comments section below the
        enlistment
3.  Enlistment liaisons process the enlistment by clicking Process
    Enlistment
    1.  Select the Training Platoon as the Unit
    2.  Set the Status of the enlistment
    3.  Select the Recruiter
4.  If a recruit is accepted, enlistment liaison can change the
    recruit’s name by clicking Modify Profile
5.  Enlistment liaison provides instructions for recruit in the Comments
    section
6.  Recruit checks the enlistment the next day and follows the
    instructions provided in the comments

## Training Platoons

### Creating

1.  Lighthouse Clerk goes to
    [admin/units](http://api.29th.org/admin/units) and creates a new TP
    unit
    1.  Copy the Path of another training platoon and follow its format
    2.  Ensure Class is set to Training and Active is true
2.  Lighthouse Clerk goes to
    [admin/events](http://api.29th.org/admin/events) and creates events
    for each day of BCT
    1.  Fill in Date/Time, Unit, Type (Basic Combat Training), Mandatory
        (true)

### Reminder Emails

1.  PM them and hope they haven’t turned off email notifications

### Posting AARs

1.  Members of Lighthouse Corps have access to post AARs for BCT events

### Modifying Steam IDs

1.  Members of Lighthouse Corps have access to Modify Profile for each
    cadet, where they can fill in the Steam ID (aka ROID)

### Graduating

1.  Battalion HQ posts graduation details in the forums
2.  Battalion HQ clicks Assign in each graduating cadet’s profile
    1.  Fill in the Unit, Position, set Start Date to the graduation
        date, leave End Date blank, and set Transfer From to the
        training platoon they’re graduating
3.  Battalion HQ goes to
    [admin/promotions](http://api.29th.org/admin/promotions) and adds a
    record for each graduating cadet
    1.  Fill in Member, Date, Old Rank (Rec.), New Rank (Pvt.), Forum,
        Topic ID
4.  Battalion HQ goes to
    [admin/awardings](http://api.29th.org/admin/awardings) and adds
    awards for each graduating cadet
    1.  Fill in Member, Date, Award, Forum, Topic ID
5.  Battalion HQ sets the Training Platoon unit to inactive on
    [admin/units](http://api.29th.org/admin/units)

