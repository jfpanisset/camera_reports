# VES Camera Reports

## Background

A key ingredient to creating high quality visual effects is the ability to recreate a digital
replica of the environment in which the scene was captured. Accurate knowledge of the camera
information and key measurements of the set are critical to aiding this process. The Visual
Effect Camera Reports are the key record for most of this information.

Despite the fact that most studios agree on the fundamental data that needs to be captured on set,
there has yet to be any consensus on a standard camera report format to record this information. 
We've set out to fix that.

## Goals

The primary goals for developing the VES camera report are:

* Provide a known standard set of fields and a well specified format for exporting (or importing) the data.
* Make it as easy as possible for a facility to ingest camera reports and their associated data even though they may have been created by another company or production.

The secondary goals are:

* Provide baseline camera reports that productions can adopt which output the standard set of fields correctly. This will serve as a useful tool for some productions, while providing an example application for others to improve on in the future.
* Provide versions of camera reports for film and digital shoots, as well as stereo shoots. Multiple cameras are supported.

## Interchange Format Introduction

The file format is a csv file, that combines slates and takes into a single row per take,
repeating the slate information for each row. The take fields will be prefixed by "tk" to make
them easy to identify. The first line will include the file fields. For more details see:
[Camera Report Interchange Format](https://docs.google.com/document/d/17CVfBa2a1m2lyve5NFIovfTFC76GF5DE8qdPD1Fd4UI/pub).

(https://docs.google.com/spreadsheet/pub?key=0AnE1uazTlVCGdDAtUkRwQlB4bWwxM0pKWGJneFZINmc&single=true&gid=2&output=html&range=A1%3ABG14")

## How to be involved

Whether you are a studio, vfx vendor or data wrangler we welcome your input. Please review the camera report specification and give us feedback.

Even if you have no input at this time, please join the [ves-tech-camera-reports](https://groups.google.com/forum/#!forum/ves-tech-camera-reports) google group.

## Downloads

The camera reports are available to download as a filemaker database. This is intended as a
baseline. We encourage 3rd party vendors to produce custom solutions that support this format as
a standard for interchange.

We plan to list additional 3rd party applications that support this interchange format. 3rd party
support might allow integration directly with ingest, the digital cameras and script supervising
systems, or simply a better interface than filemaker can provide.

| File          | Version       | Size  |
| ------------- |--------------:| ------:|
| [Camera Report Database for Filemaker 12 and newer](https://camerareports.org/filemaker_12/ves_camera_reports.fmp12?raw=true) | version 2.1   | 2.9 MB |
| [Camera Report Database for Filemaker 11](https://camerareports.org/filemaker_11/ves_camera_reports.fp7?raw=true) | version 1.1   |   7 MB |
| [Self-contained Filemaker camera-report macOS application](https://camerareports.org/standalone/VES_CameraReport_Standalone.dmg?raw=true) |               |  59 MB |
| Free iOS [Filemaker 17 to go](https://itunes.apple.com/us/app/filemaker-go-17/id1274628191?mt=8) app | |
| [Blank camera report pdf](https://camerareports.org/assets/camera-report-print-1.0-blank.pdf) for a paper backup. | |

## 3rd Party Integration

3rd party tools supporting the interchange format:

* [Setellite](https://setellite.nl/)
* [Custom Shotgun entity type to hold VES Camera Report schema](https://gist.github.com/reformstudios/993286b82f5e70b43013a3cd5f223c45)

## Links

* [Complete Camera Report Proposal](https://camerareports.org/assets/VESCameraReportProposal.html)
* [Developer Guide](https://docs.google.com/document/d/1ZmPxV6TMdPYdJ2ixfQ9V2TtvRVMxLIpn1JrUAGpDTxI/pub) if you want to adapt the VES database, or if you want to adapt your own filemaker database to export the VES exchange format.
* [Change Log](https://docs.google.com/document/d/1_A8FBCWZtw2zkUlUi7f02W1UDLgDdBA7u_B1r3ZwsOc/pub) for the specification and camera reports
* [License](https://camerareports.org/LICENSE.txt)
* Samples and Screen shots
    * Laptop entry screen: ![Laptop entry screen](https://camerareports.org/images/camera-report-full-1.0-beta.png)
    * Sample PDF output: ![Sample PDF output:](https://camerareports.org/images/camera-report-print-1.0-beta.png)
    * iPad screenshot ![Pad screenshot 1](https://camerareports.org/images/ipad-1.png)
    * iPad screenshot![iPad screenshot 2](https://camerareports.org/images/ipad-2.png)

## VES Technology Committee

This is been developed by Sam Richards as a project of the VES Technology Committee, with
assistance from numerous visual effects artists and data-wranglers. The original Filemaker
database used as a starting point for this project was graciously contributed by Rhythm and Hues.

For more details about the VES and the VES technology committee, please see the [VES Home Page](http://www.visualeffectssociety.com/).








