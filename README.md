# OpenWakeWord Trainer

Application for recording sound clips from the Seeed Wio Terminal and organizing them into a dataset for training an OpenWakeWord wake word model.

This project is intended to make local wake-word dataset collection repeatable in the same environment where the wake word system will eventually be used. The Wio Terminal records audio from its intended wall-mounted location, while a mobile-friendly recording interface allows sessions to be controlled wirelessly from different positions in the house. The recording interface will collect initial metadata such as recording location and whether the clip is intended as a positive or negative example. The local server handles storage, metadata tracking, and dataset organization, with deeper review and cleanup planned through a desktop interface, direct database workflow, or separate review page.

## Planned Design

- Wio Terminal firmware for audio capture and upload
- Local Python server for recording storage, metadata tracking, and dataset organization
- Mobile-friendly recording interface for starting/stopping recordings and entering initial clip metadata
- Review/cleanup workflow using SQLite directly, a Tkinter interface, or a separate web page

## Notes

This project is currently a placeholder. It will eventually be built using prototypes from [Wio Terminal Prototypes and Labs](https://github.com/MoTWilliams/wio-terminal).
