# Fuerza Latina Fort Collins Colorado Website

[![Netlify Status](https://api.netlify.com/api/v1/badges/5a05781c-e452-4664-8407-83473d8f8b0a/deploy-status)](https://app.netlify.com/sites/fuerza-latina/deploys)

This is the repo for https://fuerzalatinafoco.com. Fuerza Latina is an organization of immigrants and allies dedicated to educating, informing, organizing, and promoting change to facilitate an improved quality of life for immigrants in our community.

This site functions off the following technologies:
 [Jekyll](https://jekyllrb.com/)
 [netlify-cms](https://www.netlifycms.org/).
 [netlify](https://app.netlify.com/) (team page: https://app.netlify.com/sites/fuerza-latina/overview)

Using these technologies, we can obtain the following:
 - static site generation (no backend servers)
 - absolutely free hosting (some restrictions apply)
 - in page editing via the admin page, so non-technical users can contribute to webpage

## How to run Website // CMS locally for development purposes
 - Install ruby/jekyll (https://jekyllrb.com/docs/installation/)
 - Obtain access to repo, contact info@fccan.org
 - `git clone https://github.com/pbjtime/fuerza-latina.git`
 - `cd fuerza-latina`
 - `bundle exec jekyll serve --host 0.0.0.0`
 - You can now access the site: http://0.0.0.0:4000 (replace 0.0.0.0 with the local-link if hosting locally http://127.0.0.1:4000 or public address of your computer.)

**Optional:** In another terminal (to run the cms locally):
 - `cd fuerza-latina`
 - `PORT=8076 npx netlify-cms-proxy-server`