# daliworkshop.github.io

The DALI current webpage.

This repository contains the current DALI conference page. Once the year has past it can be archived to dali20XX and modified to form the next year's page.


## Archiving Last Year's Page

Each year the main web page needs to be archived to store as a previous year's conference. To do this, the first thing you need to do is duplicate this repository. 

1. Create the new repo in github by going to <https://github.com/organizations/dalimeeting/repositories/new>, use the name coding `daliXXXX` where `XXXX` is the year of the archived conference. 

2. In the conference description field, place the dates and locatin of the workshop, e.g. "3rd-5th April, Lanzarote, Canary Islands"

3. Do *not* create an initial README for the conference. 

4. Create the Repo.

5. Go to a suitable directory on your machine and type:

```
git clone --bare https://github.com/dalimeeting/dalimeeting.github.io.git
mv dalimeeting.github.io.git daliXXXX
cd daliXXXX
git branch -m gh-pages
git push --mirror https://github.com/dalimeeting/daliXXXX.git
```
6. Edit the `_config.yml` file in the new repo to set `baseurl` to `daliXXXX` and set `permalink` to  `"/:title.html"`.

7. Delete CNAME from the repo.

8. Commit the changes and push the repo.

9. Check that the archived page appears online at http://dalimeeting.org/daliXXXX/

10. Update the original main repository at [https://github.com/dalimeeting/dalimeeting.github.io](https://github.com/dalimeeting/dalimeeting.github.io) for the current conference.
This will be used to host the current DALI.

11. Add the team `daliXXXX` to the admin rights for the repo `daliXXXX`

12. Create a new admin team for this year's page, `daliYYYY`, where `YYYY=XXXX+1` and assign it to admin `dalimeeting.github.io` 

## More information

* See
  a list of repositories of past web sites [here](https://github.com/dalimeeting/).

* This link gives [Github help about project
pages](https://help.github.com/articles/user-organization-and-project-pages/)
(at the bottom), if we put the Jekyll files in **gh-pages** branch, the repository
will be served under http://dalimeeting.github.io/dali20xx. Note that the main
repository uses master branch, not gh-pages.

* When archiving to dali20xx, it is necessary to modify the ``baseurl``
  entry of ``_config.yml`` from ``baseurl: ""`` to ``baseurl: "/dali20xx"``
so that internal links in the web site are generated correctly.  

* ``baseurl:
""`` is used only in the current DALI site because its files are at the root
of dalimeeting.github.io.


