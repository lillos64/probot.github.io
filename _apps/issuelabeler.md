---
title: Issue Labeler
description: Label issues based on title and body against list of defined labels.
slug: issuelabeler
screenshots:
- https://raw.githubusercontent.com/riyadhalnur/issuelabeler/master/assets/screenshot.png
authors:
- riyadhalnur
repository: riyadhalnur/issuelabeler
host: https://1th3h69bkc.execute-api.ap-southeast-1.amazonaws.com/production
stars: 2
updated: 2018-11-27 09:14:33 UTC
installations: 17
organizations:
- pymc-devs
- Provenance-Emu
- GameServerManagers
- aonez
- nodeschool
- chrisyue
- RMHogervorst
- denzuko
- dariok
- cms-gem-daq-project
---

A GitHub bot to label issues based on title and body against list of defined labels. Built with [probot](https://github.com/probot/probot).  

## Installation  
After installation, create `.github/labeler.yml` in the default branch to enable it:

```yml
# Number of labels to fetch (optional). Defaults to 20
numLabels: 40
# These labels will not be used even if the issue contains them
excludeLabels:
  - pinned
```  
