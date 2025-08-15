website link: https://srirame5.github.io/Horizon_Esposts_Academy/


---

## **1. Public Pages (Before Login)**

These are for anyone visiting the site.

* **`index.html` (Home)** – Landing page with sections: Hero, About, Teams, Tournaments, News, Academy, Contact.
* **`about.html`** – Detailed info about the organization’s history, mission, and achievements.
* **`login.html`** – Login form for players, organizers, admins.
* **`register.html`** – Sign-up for players, team managers, or event organizers.
* **`forgot-password.html`** – Password recovery page.

---

## **2. Platform Pages (After Login)**

Once logged in, the user should see a dashboard-style interface.

* * **`dashboard.html`** – Main hub showing:

  * Linked accounts (e.g., Discord, Steam, Riot)
  * Quick links to create/join tournaments
  * Overview of active tournaments they’re in
* **`my-tournaments.html`** – Tournaments the user created or joined.
* **`create-tournament.html`** – Form to create a new tournament (game type, rules, prizes, schedule).
* **`tournament-details.html`** – Detailed view of a single tournament (teams, bracket, results).
* **`join-tournament.html`** – Search & join available tournaments.
* **`notifications.html`** – Alerts for matches, announcements, and results.
* **`profile.html`** – User’s personal info, settings, achievements.
* **`settings.html`** – Account preferences, password change, theme mode.

---

## **3. Admin Pages (Optional if you want management controls)**

* **`admin-dashboard.html`** – Overview of platform stats, user activity, tournaments.
* **`manage-users.html`** – Add, remove, or edit user accounts.
* **`manage-tournaments.html`** – Approve, edit, or delete tournaments.
* **`site-settings.html`** – Change site-wide settings (branding, rules, payment options).

---

## **4. Suggested Folder Structure**

```
/public
  index.html
  about.html
  login.html
  register.html
  forgot-password.html

/platform
  dashboard.html
  my-tournaments.html
  create-tournament.html
  tournament-details.html
  join-tournament.html
  notifications.html
  profile.html
  settings.html

/admin
  admin-dashboard.html
  manage-users.html
  manage-tournaments.html
  site-settings.html

/assets
  /css
  /js
  /images
```

---

If you want, I can also **split your current `index.html` into `index.html` + `about.html`** so you have the base ready without rewriting everything from scratch.
That way, your "before login" pages are instantly set up.


