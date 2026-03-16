<img width="1415" height="347" alt="Screenshot 2026-03-16 at 15 01 39" src="https://github.com/user-attachments/assets/aa5f5283-4a37-4f6c-b125-7dc7407d40cf" />

# Cloud MR

This is the GitHub repository for **Cloud MR**, an open-source platform for comprehensive MRI experiment simulation. Cloud MR uses a modular software architecture that allows users to assemble custom simulation pipelines by combining different modules for specific research or educational applications. 

→ Visit the [project page](https://cmr.cloudmrhub.com/) for more information

## Repositories

The code for each web application is organized in three repositories:

`<app name>`-webgui: the user interface (frontend)

`<app name>`-tools: computational methods, which can be used independently from the web GUI

`<app name>`-app: routines for cloud execution, orchestration, and scaling

Methods used by multiple applications have dedicated repositories:

[Cloudmr-tools](https://github.com/cloudmrhub/cloudmr-tools): Python library for magnetic resonance image reconstruction

[Cloudmr-ux](https://github.com/cloudmrhub/cloudmr-ux): UI library for frontend components

## License

Cloud MR is released under the **MIT License**.

## Disclaimer


Cloud MR is intended for research purposes. The code is continuously developed and may contain bugs. We strongly encourage the users to provide feedback and report bugs and potential errors.
