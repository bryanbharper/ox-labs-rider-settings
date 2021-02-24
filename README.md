# Setup

## 1. Clone Repository

```sh
git clone git@github.com:corelogic/ox-labs-jetbrains-settings.git
```

## 2. Point Rider to Local Settins Repo
In Rider, click **File > Manage IDE Settings > Settings Repository...**

In the window that pops up, click the folder icon, and select the folder of the cloned repository.

Finally, click **Overwrite Local**.

# Import New Settings

## 1. Pull New Changes
In your terminal navigate to the local settings repo, and pull. E.g.:
```
cd ~/workspace/ox-labs-jetbrains-settings
git pull -r
```

## 2. Sync Rider
In Rider, click **File > Manage IDE Settings > Sync with Settings Repository > Overwrite Local**.

# Pushing New Settings

> Before pushing new settings, make sure your settings are up to date by following the *Import New Settings* instructions.

## 1. Make Settings Change
In Rider, make the desired setting change. *When you save*, click the down arrow beside the "Save" button, and select "Solution 'data-movement' Team Shared".

## 2. Overwrite Remote
In Rider, click **File > Manage IDE Settings > Sync with Settings Repository > Overwrite Remote**.

## 4. Push to GitHub
In your terminal navigate to the local settings repo, and push. E.g.:
```
cd ~/workspace/ox-labs-jetbrains-settings
git push
```