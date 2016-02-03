---
title: Media in Wistia
layout: post
category: Account
description: From changing the title, to embedding it on your website or blog, learn all the functionality for uploaded media here.
post_intro: <p> From changing the title, to embedding it on your website or blog, learn all the functionality for uploaded media here.</p>
footer: 'for_beginners'

---

{% post_image hashed_id: 'abc9da23d7fa5920bd70ada7a8f1b9a729b26175', class: 'center' %}

## Upload Video

Before you can do anything awesome with your videos, you have to upload them!

Check out the [uploading documentation]({{ '/upload-video' | post_url }}) for
more info on uploading.

## Update Video Title

The title of the Media is how you will find it in your Account.  By default,
the title is the name of the media you uploaded, but can be updated anytime
(doesn't have to be set before uploading). Changing the title of the video won't
affect embed codes or links, either.

{% post_image hashed_id: '96baa9af41a004daabe3376ccb28e5e0790f925f', class: 'center' %}

To edit the title, hover over it with your mouse, and click the
Edit button. Edit the title text, and press the Save button at the bottom of the form.

## Video Description

Adding or editing your video description is done in the same way that you edit the title.
Hover your mouse over the Media title and click the Edit button. Add a description
in the second field of the form and click the Save button to submit your changes.

{% post_image hashed_id: 'ee71741ced9ef389792fb9a0489d922959ae790d', class: 'center' %}

The video description can help set context to your video or link viewers to your homepage or another video.
The description will also be passed through to services
like Facebook ([see more on social sharing]({{ '/social-sharing' | post_url }})).

You can type plain text into the description field or you can use markdown to style the text and put
images or links into your description. Clicking the link "Formatting with Markdown"
will open a guide explaining more about markdown.

{{ "Embedding elements via HTML in video descriptions is currently not recommended and can cause issues with the page displaying." | note }}

## Change the Thumbnail

Changing the thumbnail of your video is covered in detail in the [Customize documentation]({{ '/customizing-your-video' | post_url }}).

## Moving and Copying Media

Moving and copying media is a normal part of the organizational workflow for
your videos.

*Copying* is good for creating multiple instances of a video with different
customizations, or for zero-ing out stats for a certain video (i.e. you make a
copy and then re-embed).

*Moving* is good for keeping your account tidy. You might set up a project
called "Active Videos" and another called "Archive". Moving an old video to the
"Archive" project means you can reference the stats for that video later, but
it doesn't clutter up the "Active Videos" project. Or maybe we're just
persnickety when it comes to organization. :)

{% post_image hashed_id: 'cf7972e5b6055eb26078644ea9a99a40a79d1df2', class: 'center' %}

Select *Move & Copy* from the <span class="action_menu">Project Actions</span>
menu. This will open up the *Move & Copy panel*.

{{ "You must be an admin on the project to view and open the *Move & Copy panel*." | note }}

{% post_image hashed_id: '2c91018f45702bfc159e5659f5815398d8ffbcc7', class: 'center' %}

You can drag & drop the media you wish to move in either direction (left to
right, or right to left). Hold the `Shift` key to select multiple media.

To Copy, hold the `Ctrl` (Windows) or `⌘` (Apple) key while you arrange media.

Watch the video to see Move & Copy in action.

{% wistia_embed hashed_id: 50uxm03679 %}

### Moving Videos Between Accounts

If you are an Account Owner or Manager on multiple accounts, the *Move & Copy panel* will allow
you to move media to other accounts. For videos with stats, however, the stats
will not transfer between accounts.

**If you move a video between accounts accidentally**, and need the stats back,
moving the video to its original account and project will automatically
restore the stats. Phew.

## Embed Video

The ins-and-outs of embedding your video is the subject of our
[embedding documentation]({{ '/embedding' | post_url }}).

## Downloading Media

There are two ways to download media within your Wistia account.

The most common way is found within the <span class="action_menu">Video Actions</span>
menu on a media's page.
If you open the menu you will see an option to download the video file. You are
able to choose to download either the original media file that was uploaded or
one of the video's derivatives we created when we encoded your video.

Or you could go to a project's page and open the <span class="action_menu">Project Actions</span>
menu.
Here you will see an option to Export All Media. Clicking this will allow you
to export all of the original media files within the project as a .zip file.
There is a 4GB limit on the size of the .zip file.

### Who can download?

Account Owners and Managers by default are the only users with access to the
Video Actions menu and therefore the download option.

By default, contacts invited into Wistia are not permitted to download your
media files, but they can be granted this permission. A contact's ability to
download files is controlled via permissions at the project level.

There is more on giving download permissions in the [private sharing]({{ '/private-sharing' | post_url}})
documentation.

You can also allow any viewers to download your video via a Social Bar button.
[More on that here.]({{'/customizing-your-video#social_bar' | post_url}})

## Deleting Media

{{ "Deleted medias can't be restored, so make sure you absolutely want
to delete your media before proceeding." | alert }}

To delete a media, select *Delete* from under the
<span class="action_menu">Video Actions</span> menu.

{% post_image hashed_id: '383e7f81a6f47a29e2a5a53b21e6a0834d9b1429', class: 'center' %}

Or, if you're in a Project, just click that cute lil' *X* to the right of your
media.

{% post_image hashed_id: '4d17ba7d5090fab4e84881b713894aa402e3350f', class: 'center' %}

## Timecoded Comments

Timecoded comments allow the user to link a comment on a video to a particular
time in the video.  The timecode is captured and stored with the comment such
that when another user views the comment, they can click on the time code, the
video will skip directly to the point in the video where the comment was made.

{% post_image hashed_id: 'f26b3184c9e982fd383a4f6498d760d7431a7109', class: 'center' %}

### How to make a timecoded comment

To make a timecoded comment, pause the video at the time to which you wish the
comment to be linked.  Then, simply check the box below the text field
which says *Link comment to current time in video*.

Once the box is checked and the comment has been written, click the
<span class="faux_button">Post comment</span> and your comment will be saved.

{% post_image hashed_id: 'e3f557e99d74f221e806d97772e257b359dab2fa', class: 'center' %}

### Delete Comment

To delete comments, hover over the comment you'd like to delete, and click
the Delete button to remove the comment permanently.

{% post_image hashed_id: 'f169174d471ec77cae3451c44872421ade294efb', class: 'center' %}

### Disable Comments

Comments can be disabled for each video. The [Customize documentation]({{ '/customizing-your-video#turn_off_comments' | post_url }})
covers this in further detail.
