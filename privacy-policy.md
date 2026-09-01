# Privacy Policy — Basha Bazar

**Last updated:** 2 September, 2026

Basha Bazar ("the app", "we") helps people find rental houses ("to-lets") on foot in
Bangladesh. It records the route you walk, lets you pin to-lets you find, and lets you
share what you find with other users.

This policy explains exactly what the app collects, why, where it is stored, who can
see it, and how to delete it.

**Contact:** tasmirolislam@gmail.com
**Developer:** Tajmirul Islam

---

## 1. Data we collect

### Account information

When you sign in with Google we receive and store:

| Data | Why |
|---|---|
| Email address | Identifies your account |
| Name | Shown as the contributor name on to-lets you share publicly |
| Google account identifier | Links your data to your account |

There is no other way to use the app — an account is required, and we do not support
anonymous use.

### Location

| Data | When | Visible to |
|---|---|---|
| Precise location, in the background | Only between you pressing **Start Walk** and **Stop Walk** | Only you |
| Precise location, in the foreground | While the map is open, to show your position | Not stored |
| Location of a to-let | When you pin one | Everyone, if you mark the to-let public |

**Background location.** The app records your walking route so you can see which
streets you have already covered. This happens **only while a walk is active** — never
at other times. An ongoing notification is shown while recording. Recorded routes
("trails") are **private to you**: no other user can see them.

You can use the app without granting background location; you simply will not get
route recording.

### To-let information you enter

When you pin a to-let you may enter rent, contact phone number, number of rooms,
washrooms, balconies, floor, sunlight, gas type, free-text details, and photos.

You choose whether each contribution is **public** (visible to all users) or
**private** (visible only to you).

### Photos

Photos you attach are uploaded and stored. You may also photograph a "To Let" sign so
the app can read the phone number from it — see *Automated phone-number scanning*
below.

### Device storage

The app keeps a local database on your device holding pending changes that have not yet
been uploaded, so it works offline. This is removed when you uninstall the app.

---

## 2. Phone numbers and other people's information

To-let listings usually contain **a landlord's or caretaker's phone number**, which is
information about a person who is not a user of this app.

By entering such a number and marking the contribution public, you are publishing
someone else's contact details to other users. Only enter contact information that is
already publicly displayed — for example, written on a "To Let" sign visible from the
street — and do not enter it if you have been asked not to share it.

If you are the owner of a phone number published in the app and want it removed,
contact us at tasmirolislam@gmail.com and we will remove it.

---

## 3. Automated phone-number scanning

If you use the photo-scan feature, the photo is sent to **Google's Gemini API**
(`gemini-3.1-flash-lite`) to extract the phone number from the image. Google processes
the image on our behalf under their API terms.

We store the scanned image, the extracted result, and usage counts, so we can measure
and improve accuracy. These records are **private to your account** and are not shown
to other users.

---

## 4. Who can see your data

| Data | Who can see it |
|---|---|
| Your email and Google account id | Only you and us |
| Your name | Other users, on to-lets you make public |
| Your recorded walking routes | **Only you** |
| Public to-let contributions and their photos | All users, and anyone using the app's public data |
| Private to-let contributions | Only you |
| Your scan history and scanned images | Only you and us |

### An important limitation about photos

Photos are stored in a **publicly readable** storage bucket. File paths are long random
identifiers that cannot be guessed, and the app never shows a private to-let's photos to
another user — but **anyone who obtains the direct URL of a photo can open it**, even if
the to-let is marked private.

Do not attach photos to a private to-let that you would not be willing to have seen if
the link were shared. We intend to close this gap in a future release.

---

## 5. Where your data is stored

Data is stored with **Supabase**, our backend provider, on servers in the
**Tokyo, Japan region (`ap-northeast-1`)**. If you use the app from Bangladesh or
elsewhere, your data is transferred to and stored in Japan.

Sub-processors:

| Provider | Purpose | Data involved |
|---|---|---|
| Supabase | Database, file storage, authentication | All data described above |
| Google (Sign-In) | Authentication | Email, name, account id |
| Google (Maps) | Map display | Map requests from your device |
| Google (Gemini API) | Phone-number scanning | Photos you choose to scan |

We do not use advertising networks or third-party analytics, and we do not sell your
data or share it for advertising.

---

## 6. Retention

- Data stays until you delete it or delete your account.
- Deleting a to-let contribution removes it, its photos, and its scan records.
- **Deleting a to-let *place* you created also removes contributions other users added
  to that place**, because contributions are attached to the place.
- Local device data is removed when you uninstall the app.

---

## 7. Deleting your data

**In the app:** open **Profile → Delete account**. This permanently deletes your
account, your to-lets and contributions, your photos, your recorded routes, and your
scan history. It cannot be undone.

**By request:** email tasmirolislam@gmail.com, or use the form at
https://tajmirul.github.io/basha-bazar-legal/delete-account. We will confirm your identity and delete your data.

To delete individual items instead, delete the contribution or trail in the app.

---

## 8. Your choices

- **Location permission** — you may deny it, or grant foreground-only. Route recording
  needs the "Allow all the time" setting; the rest of the app works without it.
- **Photo and camera permission** — only requested when you attach or scan a photo.
- **Notifications** — used only for the ongoing notification shown while a walk is
  recording.
- **Public or private** — set per contribution, and changeable afterwards.

You can revoke any permission at any time in Android or iOS settings.

---

## 9. Security

Access is controlled per user at the database level, so one user cannot read or modify
another user's private data. Traffic between the app and our backend is encrypted with
HTTPS. Note the photo-URL limitation described in section 4.

No system is perfectly secure, and we cannot guarantee absolute security.

---

## 10. Children

The app is not intended for children. You must be 18 or older to use it. We do not
knowingly collect data from children. If you believe a child has provided us data,
contact tasmirolislam@gmail.com.

---

## 11. Changes

We may update this policy. Material changes will be announced in the app or on the
store listing, and the "Last updated" date above will change.
