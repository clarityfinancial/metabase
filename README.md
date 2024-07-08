# Upgrade Metabase

- Take note of the current Metabase version.
- Trigger a DB backup in Render to ensure that you'll be able to roll back if you need to.
- Update our Dockerfile to the version you want to upgrade to.  
- Commit and merge your pinned version Dockerfile update.
- Trigger a deployment on Render.  This will install the version you pinned in our Dockerfile.
