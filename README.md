# Executable Environment for OSF Project [he8mu](https://osf.io/he8mu/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Status of our Science

**Project Description:**
> The scientific quality of social and personality psychology has been debated at great length in recent years. Despite research on the prevalence of questionable research practices (QRPs) and the replicability of particular findings, the impact of the current discussion on research practices is unknown. The current studies examine whether and how practices have changed, if at all, over the last 10 years. In Study 1, we surveyed 1,166 social and personality psychologists about how the current debate has affected their perceptions of their own and the field’s research practices. In Study 2, we coded the research practices and critical test statistics from social and personality psychology articles published in 2003-2004 and 2013-2014. Together, these studies suggest that (1) perceptions of the current state of the field are more pessimistic than optimistic; (2) the discussion has increased researchers’ intentions to avoid QRPs and adopt proposed best practices, (3) the estimated replicability of research published in 2003-2004 may not be as bad as many feared, and (4) research published in 2013-2014 shows some improvement over research published in 2003-2004, a result that suggests the field is evolving in a positive direction.

**Original OSF Page:** [https://osf.io/he8mu/](https://osf.io/he8mu/)

---

**Important Note:** The contents of the `he8mu_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_he8mu/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_he8mu/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `he8mu_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-he8mu:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-he8mu
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.
