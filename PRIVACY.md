# Work: Privacy Policy

Effective 17 November 2026.

## The short version

Work is a mail, calendar, notes and to-do app made for E Ink devices. It has no accounts with us, no ads, no analytics and no crash reports, and it doesn't use Google services. Everything it keeps stays on your phone. It connects only to the mail and calendar providers you add yourself.

## Who is responsible

Work is made by Tintako, Croatia, app@tintako.com. Tintako has no server for Work and receives none of your data.

## What the app stores, and where

Only on your phone, in the app's private storage:

- the addresses and server settings of the accounts you add;
- passwords, encrypted with a key kept in the Android Keystore;
- the mail list and folders from the last refresh;
- the text of the newest messages, as many per account as you set in Mail settings (50 at first; you can turn this off), without attachments;
- messages waiting in the Outbox until they are sent or you delete them;
- downloaded events and events you create on the phone;
- notes and to-do lists;
- addresses you write to and receive mail from, for suggestions while typing;
- your settings, including your signature.

The app is left out of phone backups, so none of this is copied to a cloud. Remove an account to delete its mail, events and password from the phone; notes stay. Uninstalling the app or clearing its data deletes everything, notes included, for good.

## Permissions, and what each is for

- **Internet:** to connect to your mail and calendar providers, only while you use the app.
- **Camera:** only while you scan a calendar link from a QR code; asked the first time you open the scanner. Images are never saved or sent.
- **Contacts:** only to read e-mail addresses when you open the contact list and the phone has no contact picker of its own; asked the first time. Contacts are never changed or copied.

## What leaves, and only when you ask

- When you sign in, refresh or send, Work connects to your provider's mail (IMAP and SMTP) and calendar (CalDAV) servers with the details you entered.
- When you add or refresh a calendar by link, Work downloads that calendar file.
- Mail is shown as text and remote images are never loaded, so senders can't tell whether you opened a message.
- Nothing runs in the background: when the app leaves the screen, all network work stops.

## Who else receives anything

Only the services you add yourself. Each sees your IP address and handles your data under its own privacy policy:

| Service | When | What it receives |
|---|---|---|
| iCloud (`imap.mail.me.com`, `smtp.mail.me.com`, `caldav.icloud.com`) | if you add an iCloud account | your sign-in, the mail you send, the events you change |
| Zoho (`imap`, `smtp` and `calendar` at `zoho.com` or `zoho.eu`) | if you add a Zoho account | as above |
| Gmail (`imap.gmail.com`, `smtp.gmail.com`) | if you add a Gmail account | your sign-in and the mail you send |
| Any IMAP/SMTP server you enter | if you add another mail account | as above |
| The address of a calendar link you add | when you add or refresh it | only the request for the calendar file |

Help pages (Apple, Zoho and Google pages for app passwords and calendar links) and the tip jar (Ko-fi) are shown only as QR codes to open on another device; the app never opens or contacts them itself.

## Legal basis (EU/EEA and UK)

Tintako does not process your personal data, because it receives none. Everything Work does with your data happens on your own phone, at your request, to give you the service you asked for. Your mail and calendar providers process your data as controllers under their own terms.

## Your rights

You decide what is on the phone: you can delete any account, message, event, note or list at any time, or remove the app. Tintako holds none of your data, so there is nothing to hand over or delete. You can complain to your national data protection authority (in Croatia, AZOP).

## Children

Work is suitable for everyone and collects no data from anyone, children included.

## Changes

This policy may change with a new version of the app. The version in the app (Settings → About → Privacy) and this page always say the same.
