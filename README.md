# Dutchento agenda
This repository is meant to maintain the Dutchento agenda in a [YAML](https://en.wikipedia.org/wiki/YAML) file called `agenda.yaml` so that this could be used in other places.

## Adding your event
If you have an event, feel free to add a Pull Request to this repository to add your event to the `agenda.yaml` file. You can add a PR by cloning this repository. But likewise, you can simply edit the online file in your browser and commit a GitHub Pull Request on the fly.

Each entry has the following format:
```yaml
YYYY-MM-DD-EVENT-ID
  - date: YYYY-MM-DD
  - title: Your event name
  - location: Somewhere
```
Each entry should start with a key `YYYY-MM-DD-EVENT-ID` (`year` + `month` + `day` + unique name to identify this event).

Once a Pull Request is submitted, it will be reviewed by the Dutchento team and accepted as soon as possible.

## Current resources
Currently the following sites are used to scan for meetups regularly:

- https://www.dutchento.org/category/events/
- https://www.meetup.com/Magento-User-Group-Amsterdam/
- https://www.meetup.com/Magento-User-Group-Noord-Brabant/
- https://www.meetup.com/Rotterdam-Magento-Meetup/
- https://www.meetup.com/Magento-User-Group-Gelderland/
