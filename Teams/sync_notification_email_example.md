# Sync Notification Email Example

When someone is syncronized into a team via the automated process, an automated email is sent to the person.

```
FROM: noreply@github.com

TO: {email of person who was synced}

SUBJECT: github-team-synchronization[bot] added you to the **{team name}**

BODY:
You’ve been added to the {team name} for the {organization name}.  {team name} has {x} members and gives access to {x} repositories.

View {team name}: {Link to Github Team}

Read more about team permissions here: https://docs.github.com/articles/what-are-the-different-access-permissions

```
