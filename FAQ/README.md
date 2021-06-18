## Github @ UNCG Frequently Asked Questions (FAQs)

#### FAQ #1: I already have a Github Organization that I set up myself outside of UNCG. Can I migrate it into Github @ UNCG so I can take advantage of UNCG Authentication and other awesome benefits?
 - ANSWER: Github does not provide a method to migrate/import a whole organization, however you can migrate the individual repositories one by one. For example, adding a new "remote" to your existing repository, and pushing to github instead of the old repo location. Just make sure you're aware of For example:

``` $ cd $HOME/my-repo-directory
$ git fetch && git pull 
$ git remote rename origin old-repo-location-name
$ git remote add origin https://github.com/my-uncg-org/my-awesome-new-uncg-git-repo-url.git
$ git push origin master
$ git remote rm old-repo-location-name
```

#### FAQ #2: Can Github @ UNCG Admins, or Organization Admins see everyone's code?
 - ANSWER: No. Github Admins and Org Owners do **NOT** have blanket/comprehensive access to every repository. In order for a Github Admin to access/view a repository, the admin must be given explicit permission within that Organization or repository (either directly or via team membership).

#### FAQ #3: A repository owner left UNCG and now we can't get into the repo. Can someone help?
 - ANSWER: If all the owners/permitted people are unavailable, the repository or organization is considered orphaned. Github Admins or Org Owners cannot forcibly gain access through any direct or backdoor process. For this reason, it is important for Org and Repo owners to ensure that they always have at least 2 permitted people with the correct level of access, so orphaned resources don't occur. Users can consider using [Synced Teams](Teams) to alleviate some of the risk, by providing an external method of managing access to certain resources.
