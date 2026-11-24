---
title: ytdark privacy policy
permalink: /ytdark/privacy-policy/
---

# ytdark — Privacy Policy

- **Effective date:** November 24, 2026
- **Developer:** Christ Is King Software
- **Contact:** christiskingsoftware@gmail.com

## Summary

ytdark is a private tool used by a single operator to manage YouTube channels that the operator owns. It has no public users, no website login and no server of its own. It runs on the operator's computer.

## Data accessed

When the operator signs in with Google, ytdark asks for permission to manage the operator's own YouTube channel (the `youtube.upload` and `youtube.force-ssl` scopes). Through the YouTube Data API it reads and writes only that channel's data: channel settings, videos and their metadata, thumbnails, captions and playlists.

## Data stored

- An OAuth refresh token for the operator's channel, kept in a password-protected secrets manager (Bitwarden Secrets Manager).
- Local working files about the operator's own videos on the operator's computer.

## Sharing

ytdark does not sell, share, transfer or disclose Google user data to anyone. It sends data only to Google's YouTube API, on the operator's behalf. It does not use Google user data for advertising or to train machine-learning models.

ytdark's use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Retention and deletion

The token and local files stay until the operator deletes them. Access can be revoked at any time at https://myaccount.google.com/permissions, which makes the stored token unusable.

## Children

ytdark is not directed at children and collects no data from anyone other than its operator.

## Changes

If this policy changes, this page and its effective date will be updated.

## Contact

Questions: christiskingsoftware@gmail.com
