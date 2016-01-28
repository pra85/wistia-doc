---
title: Sharing Video Privately
layout: post
category: embed and share
description: Wistia makes it easy to privately share your videos with people right within the Wistia app. Invite people to your account via email, and track how they watch in a secure environment.
post_intro: <p>Your Wistia account isn't crawled by search engines, but you might not always want to embed your videos in order to share them. That's where Wistia's Private Sharing functionality comes in. Wistia allows you to invite users to your account, lets you assign permissions to each viewer (or groups of viewers), and monitor their viewing activity.</p><p>Private sharing is right for you if you want to:</p><ul><li>Review and approve content before it goes live</li><li>Share instructional videos with your team</li><li>Create internal content that contains sensitive information</li><li>Charge your customers to view content in a secure environment</li>
footer: 'for_beginners'
---

{% wistia_embed hashed_id: rz17xouyzk %}

## What is Private Sharing?

Private Sharing in Wistia allows you to add users to your individual projects and
give them specific accesses and controls around to your videos. Wistia videos in
your account aren't crawled by search engines, so until you share your videos
(via direct URLs, or embedded on your website) they will remain private.

You will only need to use Private Sharing if you want to further
restrict access to your videos, invite users to add or update content in your
projects, or share and monitor internal content.

If you're confident that Private Sharing is right for you, let's get started!

## Invite Contacts

{% post_image hashed_id: 'b7f77d7e188bc953dfd491ae12d9476ee44f5c2c', class: 'center' %}

Your first move in Private Sharing (after you've
[uploaded]({{ '/upload' | post_url }}) and
[customized]({{ '/customizing-your-video' | post_url }}) your video of course)
is to invite contacts to your project. You can do this on the
[Users](https://my.wistia.com/contacts) page in your account, or on individual
project. Let's first walk through adding contacts to a project.

[Managers]({{ '/permissions#managerlevel_permissions | post_url }}) in your
Wistia account can invite new contacts to view private content using the
*Sharing & Privacy* feature.

From the Project page, select *Sharing & Privacy* from under the blue
**Project Action** dropdown menu. You can also click on the padlock icon next
to the title of the project.

<!---
Screencast of both
--->

In the box where it says "Enter email addresses to add users," do just that!
Type in the email addresses for contacts you'd like to share the project
privately with. You can also customize the text of the message by clicking
"Add a personal message."

{% post_image hashed_id: '82a0ef0b697b5f311d80bb9ef7fe07ca73437358', class: 'center' %}


## Privately Share Video By Link

{% post_image hashed_id: 'c0abef6318491516e0ec8044efacfa1869cb609a', class: 'right', width: 320 %}

This is the best sharing method to use if you want to:

* Send out a single link from your own email account to a group of people to allow
  them to view your video.
* Track how people watch your video, but are less concerned about associating
  viewing with a viewer's email address.

Once you have uploaded your videos to your project, from within the project
hover over the *Project Actions* menu and choose the *Sharing and Privacy*
option.

When the sharing window appears, the privacy of that project will be
displayed at the top (see image below). To create a link that can be sent out
and viewed anonymously, switch the account over to **unlocked** and then
**save**.  

Once the project has been set to *unlocked*, copy the link displayed. You can
share this link in an email or put it on a webpage, and when users click on the
link, they will be taken directly into the project.

{% post_image hashed_id: '84b91f68a2d3a09bd4635648e3598bef81efb871', class: 'center' %}

To disable access to your project through the link, set the sharing level to
*locked*.

## Managing Permissions

{% post_image hashed_id: 'b7f77d7e188bc953dfd491ae12d9476ee44f5c2c', class: 'center' %}

Wistia accounts include permissions and access controls for Managers, to set
who can view media and what they can view.  To manage permissions for contacts
on a Project, click the *Sharing and Privacy* option under Project Actions.

The share screen shows which users currently have access to the Project, and what permissions they have.  From here, Managers can add permissions like:

*  **Admin**, which gives the user Manager-Level permissions for that
   particular Project.
*  **Upload**, which allows the viewer to upload new content.
*  **Download**, which allows the viewer to download content.
*  **Share**, which means the viewer can share the Project with new viewers.
*  **Stats**, which gives the viewer the ability to view stats for videos in the Project.

{% post_image hashed_id: 'f3bab334f91573315cba67b509d0274d194f5f6e', class: 'center' %}

### Removing Access

Removing viewer access can also be done by clicking the small **X** icon at the
end of each viewer row. Make sure to **save** your changes.

## Private Viewer Analytics

Now that you have invited some viewers in to view your private content, it's
time to see if they actually watched!  This is especially helpful for reviews
and approvals and training or educational content.

{% post_image hashed_id: 'b6aebd416657befa27efa259249ab2b32d158649', class: 'center' %}

To view the individual user statistics for people you've invited into Wistia,
select the *Private User Sessions* option under the *Account* tab at the top of any page
in your Wistia account.

You will see a list of all user sessions for the users that have logged into
your Wistia account.  To see exactly what each user did in each session, click
*View Details* next to the session.

{% post_image hashed_id: '3d2c0eff0d4a023770f80abea853267bf3828204', class: 'center' %}

A complete audit trail will be shown with all of the actions the user took
while they were logged in to your Wistia account.  This includes amount of time
spent on various pages as well as video heatmaps for the videos that they
viewed.

{% post_image hashed_id: '65022f264a05a073e9a1de4196481e099a112184', class: 'center' %}

## How Wistia Appears For Your Viewers

When you invite new viewers into your account to privately view video, they
will only have access to parts of the account that have been shared with them
or they have been giving access to. For a quick review on sending
invitations, see the [Invite Viewers]({{ '/private-sharing#invite_viewers' | post_url }}) section above.

Let's walk through an example of how this will look from your viewer's perspective.


### The Invitation Email

{% post_image hashed_id: 'a2892adc2c8a546416f8853efd0eaed65c76112e', class: 'float_right', width: 500 %}

After clicking the *Add User* button, your viewer will receive an email at the
address you have designated.  This email will include an invitation to view the
project you are sharing, along with a link for their access.

{{ 'This activation link is specifically designed for their email, and is only good for one use (the email cannot be forwarded).' | note }}



### The Credential Creation Screen

{% post_image hashed_id: 'b24e225a3f0567bd80589ab5ee563c05fcbedcd7', class: 'float_right', width: 500 %}

After clicking the activation link, viewers who have never interacted with the
Wistia system will land on a page where they can create Wistia credentials.  


### The Viewer's Perspective

When your viewer logs in, they will have access to the specific Project you have shared with
them, but they will only see the functionality you have enabled for them.

By default, they will not be able to access any information specific to the
account, and they will not be able to access any other Projects in the
account.

{% post_image hashed_id: '845a72ca08edbf2cf5d2055b13d02e22e5ab1f8d', class: 'center' %}

*A sample project actions menu for an invited user with Upload and Share permissions*

Some example scenarios:

* Users who have been given *Admin* permissions for the project will be able
  to see every option under Project Actions, and will also be able to see all
  other shared users on the project via the "Sharing and Privacy" screen.
* Users with the *Stats* permission will see the Stats option under
  Project Actions.
* Users with *Upload* permissions will see the Upload option under Project
  Actions.

Users who have been given the *Share* permission (but not the *Admin*
permission) will see a slightly different Sharing screen. They will be able to
add email addresses into the "Share with" box, and will only be able to give
out the permissions that they currently have for that Project. They can also
customize the email message that is sent out as well. Here is what that Sharing
screen looks like:

{% post_image hashed_id: '3f02151ecc91df28777bc63ac177d8dc66223439', class: 'center' %}

## Private Sharing FAQ

### Why don't I set a password for my viewers?

The best way for unwanted viewers to view secure content is through the original email. Sending a group email that contains the login and password needed to access secure content can be grabbed easily: from a stolen laptop, from a hacked email account, even read right off the screen at a coffee shop. With Wistia, your invited viewers receive an email with a one-time use activation code, and then create their own password.
