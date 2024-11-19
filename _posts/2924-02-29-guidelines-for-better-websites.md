---
title: "Guidelines for better websites"
date: 2023-08-19 12:10:00 -0400
categories: homunculogy
authors: ismaelc
status: draft
---

## HTML

- Add the **charset utf8** to every webpage with the <meta> element.
- Always add a **favicon** to the website that must be useful to identify it from any other website.
- Add a **<title>** tag to every webpage. The text inside it must be specific to each webpage and, if it's about a generated webpage, like a profile or a content uploaded by a user, the text must be related to the content, and not to the category of the generated webpage.
- Add a **description** meta information based on each webpage. If that webpage is a generated webpage, the description must be related to the generated content, in order to vary between each generated webpage of the same kind.
- Add the **canonical link element** in every webpage.
- Add the **<script>** elements at the end of <body>, after every other element inside it.
- All **urls must be canonicalized**, that means that there can't be special characters in the url and whitespaces are always replaced by dashes. Accents are eliminated.
- **Force https** inside the website, by redirecting http connections to be always https connections instead. Force the appearance of www in the url by doing redirects too, because then the url is always the same, it doesn't has variants that confuse the visit.

## UI

The **contrast** is the difference in color between two color. A **high contrast** means that two colors are very different and then are easy to distinguish between them.

- All the different UI element must have a **high contrast** with the background in which they are placed, in order to be easily seen. They can't have a similar color to the background, because in that case they aren't seen easily.
- All icons should be well-known, if there's a known icon for some purpose it must be used instead of a new one which is unkown by the visits.

## Account data

- **National identity number** data, which is optional, and if it's used, it allows to always recover the account with the national identify card, by sending a picture of it to the administrators of the wesite.
- **Email** adresses. There has to be choose if the website will allow only one email address per account, or any number of them per account. If the email address is only one, that email address is the one used for sign in. If there's more than one email address per account, each email address can be configured to be allowed to be used for sign in purposes or not. If they aren't used for sign in purposes, they are only useful for messages.

## Forms

### Validation messages

The **validation messages** are the message that appear to inform about any specific rule of the form that must be followed by the user in order for the form to be send.

### Custom form fields

- **Date picker**, which allows to select a date easier than entering it like a text.
-- **Time picker**, which allows to select a time value easier than entering it like a text.
- **National identity number** field. It's a text field that also formats the value entered with the dots, dashes, and any other symbol pertaining to the national identity number requested to be entered.
- **Color picker**, which allows to select a color with an interactiva interface.

## Sign in

- Use the **email** field, and not the username field, as the field to identify the account to do sign in. The other field that can be used, in replacement of the email, is the national identity number. Also, it's possible to allow both options, and to have then a sign in form where the first field allows at the same time an email value or a national identity number value.
- Add the **remember me** checkbox in all sign in forms.

## Account creation

- The **email** field is mandatory, because otherwise there's no possibility of verifying the account and of sending any important information to the user about the website.
- After sending the first form, there must appear a button allowing to open the email account. That button should link to the website of the email service, beign it Outlook, Gmail, or another.
- The **login** field, also called sometimes **username**, must be replace by the email field, which is better. The reason behind this is that this field is harder to remember than the email, and so it's the email the field that should be used, alongside with the password, to sign in.

### Validation rules - email

- Only allow **outlook** and **gmail** email addresses, disallow all others. This criteria is to allow only services that have high surveillance and are then more trustable. All email services that provide email accounts that can be easily hacked must be forbidden, otherwise it{s possible to create fake accounts in the website in big numbers by each hacking attack.

### Validation rules - national identity number

- Allow to optionally add the national identity number during the account creation. It's forbidden to change that national identity number through settings, that number is instead permanent for each account of the website. Also, usually, it's not possible to have more than one account with the same national identity number, unless in the website it's allowed the same real person to have more than one account in the same website.

## Account settings

- Any form that allows to change settings of the account must required the password of the account to be sent, that prevents hacking attacks.
- The form to **change password** must be independent to all other forms that allow to change any setting of the account, and **must** require to enter the previous password.
- The form to **delete the account** must be independent to all other forms and **must** require the password. Also, it's better if it's required to confirm the deletion of the account via a link sent to the email account, in order to prevent hacking attacks.
- Add a webpage of the **history of sign ins**, which must list the browser used, the operating system, and any other important characteristic of the computer, in order to provide the user with enough information to identify if a person has hacked his account.

## Mandatory webpages

- **About us:** It informs about the authors of the website and the purpose of it.
- **History:** If that information doesn't appears inside the webpage about us, this webpage must inform the history of the website.
- **Contact:** This webpage allows to email the authors about anything related to the website.
