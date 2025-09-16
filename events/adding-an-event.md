---
description: Lets walk through the Add Event process and the Add Event form!
icon: calendar-pen
---

# Adding An Event

To get started, just go over to the `Events` page in the `Host Dashboard` and click on `Add Event` in the top right.

<div align="left"><figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 4.25.35 PM.png" alt="" width="159"><figcaption></figcaption></figure></div>

The `Add Event Form` is made up of multiple sections. Let's go over each one

### Event

<div align="left"><figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 4.25.51 PM.png" alt="" width="375"><figcaption></figcaption></figure></div>

Enter the Event Title and select an event status.&#x20;

The event title will be converted to be the root event url. If the Title is set to `Karaoke Extravaganza at Grand Ole Opry` then the KJPro.info platform will convert the url to be\
`https://kjpro.info/karaoke-event/Karaoke-Extravaganza-at-Grand-Ole-Opry`&#x20;

{% hint style="info" %}
What is the root event url?\
\
Events have a root URL and each occurrence of the events schedule can be viewed by appending the date to the end of the root url, for example: \
`https://kjpro.info/karaoke-event/Karaoke-Extravaganza-at-Grand-Ole-Opry/09-17-2025`&#x20;
{% endhint %}

### Schedule - Single Event

<figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 4.26.09 PM.png" alt=""><figcaption></figcaption></figure>

For a single event enter the `Date` of the event, the `Event Start Time` and the `Event End Time`.

The `Schedule Synopsis` is optional. This over rides the default display text of the events schedule. In the case of an single event the the default is to show the Date and Time, however this text can be replaced by whatever you enter here.

### Schedule - Weekly Event

<figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 4.26.16 PM.png" alt=""><figcaption></figcaption></figure>

For a `Weekly Event` enter the `Run From / To` dates, the `Day of Week` that the event occurs, the `Event Start Time` and the `Event End Time`.

The `Schedule Synopsis` is optional. This over rides the default display text of the events schedule. In the case of an weekly event the the default is to show `Every [Day of Week] @ [Start Time]`, however this text can be replaced by whatever you enter here. This is helpful in the case of events that are on a other than weekly schedule such as `Every 1st and 3rd Monday`

{% hint style="info" %}
Important: This does NOT change the actual event schedule, just the text that displays on event pages. To prevent dates from being included in the event schedule, you must create event modifiers for the dates you want to exclude.
{% endhint %}

### **Online Singer & Song Signup**

<figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 4.26.24 PM.png" alt=""><figcaption></figcaption></figure>

Do you use an online singer and song signup service like Song Books Online? Enter the url for the site in the `Online Song & Singer Signup URL` and the text for this link in the `Online Song and Singer Signup Directions/Label`

The text for the directions/label is a great place to put your show ID or any other information the event attendees would need. For Example: `Search and submit your songs online using show ID KaraokeKingPin`

### Location

<figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 5.04.33 PM.png" alt=""><figcaption></figcaption></figure>

The location is faster than it would appear to complete! We use the Google Places API to speed things up quite a bit. By clicking in the Google Places Search you can begin typing the name of your event venue and when you see it in the results click on it. When you click on it the KJPro.info platform will automagically populate the `Google Places ID`, `Location Name`, `Address`, `City`, `State` and `Zip`.&#x20;

<div align="left"><figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 5.07.53 PM.png" alt="" width="310"><figcaption></figcaption></figure></div>

{% hint style="info" %}
The Google Places ID is read only and can only be set using the Google Places Search function
{% endhint %}

### Event Description

<figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 4.26.58 PM.png" alt=""><figcaption></figcaption></figure>

`Event Description` allows you to enter short description for the event including any specifics for the event.&#x20;

Specials allows you to list any specials or highlights of the event or that that the venue has. Each item should be entered on a new line.&#x20;

For example:

`$6 Margaritas`\
`Buy one burger, get one free!`\
`Weekly $25 gift certificate giveaway!`&#x20;

Would produce the following on the event page:

<figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 5.13.11 PM.png" alt=""><figcaption></figcaption></figure>

### Event Flyer

<figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 4.27.06 PM.png" alt=""><figcaption></figcaption></figure>

You can select a flyer to be uploaded and displayed for your events. Select a flyer and a preview will be displayed. When the event is saved the flyer will be uploaded to the server and attached to the event.&#x20;

{% hint style="info" %}
Event flyers should be in a standard image format. .jpg is preferred.
{% endhint %}

### Terms of Service and Privacy Policy

<figure><img src="../.gitbook/assets/Screenshot 2025-09-16 at 4.27.16 PM.png" alt=""><figcaption></figcaption></figure>

You must agree to the [Terms of Service](https://kjpro.info/terms-of-service) and [Privacy Policy ](https://kjpro.info/privacy-policy)every time you create or edit an event. Please take the time to review them both and ensure you agree before adding or editing any event!

### Save Event

Woo Hoo, you made it this far! Now you just need to save your event! Click the `Add Event` to get your event listed (assuming the status is set to active)!
