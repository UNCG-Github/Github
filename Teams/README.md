# GITHUB TEAMS

## OVERVIEW

[Before going any further, please read Github's documentation about "teams"](https://docs.github.com/en/organizations/organizing-members-into-teams/about-teams).

Organization owners can set up teams that are managed directly inside of Github, or optionally the team can be kept in sync with a UNCG Azure AD group. 

Administrators have already set up the [sync process](https://docs.github.com/en/organizations/managing-saml-single-sign-on-for-your-organization/managing-team-synchronization-for-your-organization), meaning for existing groups it's just a simple process of selecting it from a drop-down menu inside your Team Settings. When people are added/removed via the sync process, automated emails are sent. Examples are included in this folder for reference.

## CONNECTING TO AN EXISTING UNCG AZURE AD GROUP

Information about setting up a team to be synchronized is [provided by Github here](https://docs.github.com/en/organizations/organizing-members-into-teams/synchronizing-a-team-with-an-identity-provider-group).

## DON'T HAVE A UNCG AZURE AD GROUP YET?

 - Groups can be used to sync members into other services like Google Groups, Canvas Orgs etc, so the recommendation is to create a group for the distinct population you need to manage, and then you can use it with various services.
 - Contact ITS Identity Management through [6-TECH](http://6tech.uncg.edu) to get your group(s) set up. 
 - After set up (usually within 24 hours) the group(s) will appear in Github for you to select as a source for your team [per the instructions](https://docs.github.com/en/organizations/organizing-members-into-teams/synchronizing-a-team-with-an-identity-provider-group).

## ADDITIONAL INFORMATION / BEST PRACTICES

- Ensure users are using their primary iSpartan account email address for their github account, not an alias. A Github account that is using a UNCG alias as its email address may not be synchronized correctly. This is due to UNCG Azure looking for the primary username as the correct attribute to sync, and not the alias@uncg.edu format.

- You should always set up synchronized teams before you add/invite members to your organization. This way, the member will be added to all appropriate teams very quickly after they accept the invite. On occasion, Github admins have noticed a need to remove and then re-invite existing organization members, in order for them to get synchronized (added) for the first time.

