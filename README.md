This is a template for a Hackers at Cambridge workshop repository.
To get started making a workshop, clone this repository to `workshop-[[workshopId]]` (e.g. `workshop-intro-to-rust`).

The 'workshopId' is just a short identifier that represents your workshop. (e.g. `intro-to-rust`)

After filling in the necessary information in this repository, and adding this workshop to the [workshops index](https://github.com/hackersatcambridge/workshops), it will be parsed by our website and shown on the workshops page at:
[https://hackersatcambridge.com/workshops](https://hackersatcambridge.com/workshops)

Tick off the following steps as you go along (they don't have a strict order):

- [ ] Ensure that all contributors have write access to the clone of the workshop repository and that it is hosted in the [Hackers at Cambridge GitHub organisation](https://github.com/hackersatcambridge). 
- [ ] Fill in [metadata.yaml](/.hac_workshop/metadata.yaml)
- [ ] Add an appropriate license that matches what is in [metadata.yaml](/.hac_workshop/metadata.yaml): [Example](https://github.com/hackersatcambridge/workshop-intro-to-git/blob/master/LICENSE)
- [ ] Fill in [description.md](/.hac_workshop/description.md)
- [ ] Fill in [prerequisites.md](/.hac_workshop/prerequisites.md)
- [ ] Fill in [presenter_guide.md](/.hac_workshop/presenter_guide.md) or delete it if it isn't needed
- [ ] Fill in [setup_instructions.md](/.hac_workshop/setup_instructions.md)
- [ ] Fill in [troubleshooting.md](/.hac_workshop/troubleshooting.md) or delete it if it isn't needed
- [ ] Add promotional images in [promo_images](/.hac_workshop/promo_images) (the HaC design team can produce these for you)
- [ ] Fill in [notes.md](/.hac_workshop/notes/notes.md)
- [ ] Go to https://hackersatcambridge.com/workshops/validate/[[workshopId]] and ensure that validation passes. Fix any errors that occur
- [ ] _Once validation has passed_, make a PR to add this repo to the [workshops index](https://github.com/hackersatcambridge/workshops)
- [ ] Once the above PR has been merged, delete this file up to the following divider and put your workshopId in the template below to link to the website page of this workshop

*NOTE:* Anything you wish the attendees to be able to download should go in the top level directory of this repository

---

This is a Hackers at Cambridge workshop. This repository holds all the content to the workshop but the best way to view the content is on our website. Go to:

hackersatcambridge.com/workshops/[[workshopId]]
