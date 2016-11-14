# FP CMS Server (beta)
A self-hosted CMS server, a plugin for the [FP Static Site Generator](https://github.com/dominicfallows/FP-Static-Site-Generator) or standalone. Built with technologies that enable cross-platform use to creates many possible implementation opportunities.

## <a name="project-specification"></a>Project Specification
TBD

## Development Roadmap
Updated 2016-11-14

| Milestone | Feature Summary | Description | Estimate Delivery Date | Status |
| --------- | --------------- | ----------- | ---------------------- | ------ |
| 1.0.0-beta 	| CMS server (local)<br>+ Static Page Storage | Add a CMS server operating as a plugin for the [FP Static Site Generator](https://github.com/dominicfallows/FP-Static-Site-Generator). This will enable a site to be generated using a WYSIWYG size CMS automatically creating the static site files.<br><br> At this stage: <ol><li>The CMS server will be local, running via the build process - not intended to be running on internet/intranet infrastructure</li><li>Media Management (upload, manage and handle images, videos and other files) will be manual</li><li>Template Management (create, edit and assign layout templates) will be manual</li></ul> | TBD |
| 1.?.0-beta 	| + CMS Media Management | Upload, manage and handle media (images, videos and other files) via the CMS. | TBD |
| 1.?.0-beta 	| + DB Storage | Switch from Static Page Storage to DB Storage (to ready for Cloud Deployment/CMS on internet/intranet and CMS Authentication; amost other benefits) | TBD |
| 1.?.0-beta 	| Standalone Server | Enhance CMS Server to run standalone (not as a plugin for the [FP Static Site Generator](https://github.com/dominicfallows/FP-Static-Site-Generator)), enabling it to be the back-end/CMS for any JavaScript project.  | TBD |
| 1.0.0-RC | Testing and QA | <ul><li>Release Candidate Testing and QA ready for launch of 1.0.0 (stable)</li><li>Documentation for 1.0.0 (stable)</li></ul> | TBD |
| 1.0.0 | Launch of 1.0.0 | <ul><li>Update product website for 1.0.0 stable</li><li>Update Github stable branch</li></ul> | TBD |

Roadmap next stages TBC, but features already in the pipeline are: 

| Milestone | Feature Summary | Description |
| --------- | --------------- | ----------- |
| TBD | Cloud Deployment (static site files) | Enable deployment of production build of static site to cloud infrastructures: <ul><li>Using npm/gulp tasks of the [FP Static Site Generator](https://github.com/dominicfallows/FP-Static-Site-Generator)</li><li>via the CMS Server</li></ul> | TBD |
| TBD 	| CMS (on internet/intranet server) | Make the CMS standalone and able to run on internet/intranet infrastructure (as well as on a local server via the build process) | TBD |
| TBD 	| CMS Authentication<br> | Authentication system, to control access to the CMS | TBD |

## Licenses

This project typically uses the [MIT](LICENSE) license for code.
Some included projects license documentation and other forms of content under different licenses. See specific projects to understand the license used.
