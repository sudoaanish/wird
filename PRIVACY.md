# Privacy Policy for Wird

**Last updated:** May 6, 2026

This is a hackathon project built solo by Aanish Farrukh for the Quran Foundation Hackathon. Plain English ahead.

## What Wird is

Wird is a daily Quran companion web app. To function, it integrates with Quran Foundation's APIs for verse content, audio, translations, tafsir, and user features (bookmarks, notes, streaks, activity tracking).

## What data Wird touches

When you sign in to Wird, you authenticate with Quran Foundation directly via OAuth2 / OpenID Connect. Wird never sees your password. Quran Foundation issues an access token to Wird, and Wird uses that token to read and write your data on their servers on your behalf.

Data stored on Quran Foundation's servers (governed by [Quran Foundation's privacy policy](https://api-docs.quran.foundation/legal/developer-privacy/)):

* Bookmarks you save
* Reflection notes you write in the journal
* Streak and activity data
* Posts you publish to Quran Reflect

Wird also stores a small amount of data in its own database (hosted on Supabase) to support features that Quran Foundation's APIs don't cover:

* Your current theme journey and progression
* Your grace day count for the streak system
* Your app preferences (language, reciter, translation, notification time)

## What Wird does not do

* Wird does not sell your data
* Wird does not share your data with advertisers, brokers, or third parties
* Wird does not track you across other websites
* Wird does not read your reflections for any purpose other than to display them back to you
* Wird does not use your data to train any AI model
* Wird does not show ads

## Analytics

Wird uses Vercel Web Analytics, which is a privacy-friendly analytics service that does not use cookies, does not fingerprint users, and does not collect personally identifiable information. It counts page views and traffic sources at an aggregated level only.

## Cookies

Wird uses one essential cookie: a session cookie that keeps you signed in. There are no advertising or tracking cookies.

## Your rights

You can request deletion of all data Wird has stored about you by emailing the contact below. Data stored on Quran Foundation's servers is managed through your Quran Foundation account controls; Wird cannot delete that data on your behalf, but you can revoke Wird's access to your Quran Foundation account at any time, after which Wird will stop reading or writing data there.

## Contact

Aanish Farrukh — afarrukh@ithaca.edu

## Changes to this policy

If this policy changes, the "Last updated" date above will change. For a hackathon project of this scope, significant changes are unlikely.

