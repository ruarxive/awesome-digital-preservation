# Awesome Digital Preservation

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Curated list of digital preservation tools, standards, and organizations, with
a strong focus on web archiving.

Last updated: 2026-01-20

## Scope & Inclusion Criteria

- Includes tools, standards, registries, and organizations that directly
  support capture, preservation storage, fixity, replay, access, and analysis
  of digital materials (web, social, files, AV).
- Prioritizes actively maintained, documented, and widely used resources.
- Lists preservation-specific standards/specs and registries commonly used in
  workflows.
- Out of scope: generic backup/sync utilities, short-lived scrapers without
  archival outputs, and unrelated analytics tools.

## Table of contents

- [Scope & Inclusion Criteria](#scope--inclusion-criteria)
- [How to Use This List](#how-to-use-this-list)
- [Web Archiving](#web-archiving)
  - [Crawlers & Capture](#crawlers--capture)
  - [Replay & Access](#replay--access)
  - [Analysis & Data Processing](#analysis--data-processing)
  - [Capture Operators & Services](#capture-operators--services)
- [Social Networks](#social-networks)
  - [Twitter](#twitter)
  - [Instagram](#instagram)
  - [Universal](#universal)
- [Other Digital Objects](#other-digital-objects)
  - [Online Storage](#online-storage)
  - [Messengers & Chats](#messengers--chats)
  - [Specific CMS](#specific-cms)
  - [Public Data API](#public-data-api)
- [Preservation Frameworks & Platforms](#preservation-frameworks--platforms)
- [Preservation Storage & Replication](#preservation-storage--replication)
- [File Format Identification & Validation](#file-format-identification--validation)
- [Fixity & Packaging](#fixity--packaging)
- [Emulation & Virtualization](#emulation--virtualization)
- [Audio-Visual & Media Preservation](#audio-visual--media-preservation)
- [Digital Forensics & Ingest](#digital-forensics--ingest)
- [Metadata Standards & Tools](#metadata-standards--tools)
- [Preservation Planning, Risk & Policy](#preservation-planning-risk--policy)
  - [Policy & Audit](#policy--audit)
- [Training, Education & Best Practices](#training-education--best-practices)
- [Conferences, Events & Communities](#conferences-events--communities)
- [Standards and Specifications](#standards-and-specifications)
- [Organizations](#organizations)
- [Knowledge Bases](#knowledge-bases)
- [Major Digital Archives](#major-digital-archives)
- [Related Lists](#related-lists)
- [Maintenance](#maintenance)
- [How to Contribute](#how-to-contribute)

## How to Use This List

If you are new to digital preservation, start with preservation frameworks to
see end-to-end systems, then explore specific tool categories (web archiving,
metadata, fixity, or forensics) based on your needs.

## Web Archiving

Tools and services for capturing, replaying, and analyzing web content.

### Crawlers & Capture
* **[Wget](https://www.gnu.org/software/wget/)** - Classic downloader often used for basic crawls.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[WPull](https://github.com/ArchiveTeam/wpull)** - Wget-compatible web downloader and crawler.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[Conifer](https://github.com/Rhizome-Conifer/conifer)** - Browser-based capture and replay for web pages.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Cloud
* **[grab-site](https://github.com/ArchiveTeam/grab-site)** - Web crawler with WARC output and crawl dashboards.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Docker
* **[Heritrix3](https://github.com/internetarchive/heritrix3)** - Internet Archive's extensible, archival-quality crawler.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux / macOS
* **[WAIL](https://github.com/machawk1/wail)** - One-click user-initiated web preservation toolkit.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** macOS / Windows
* **[Browsertrix Crawler](https://github.com/webrecorder/browsertrix-crawler)** - High-fidelity browser-based crawler in a Docker container.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Docker
* **[Brozzler](https://github.com/internetarchive/brozzler)** - Chrome-based high-fidelity web crawler with WARC output.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux / Docker

### Replay & Access
* **[ArchiveWeb.page](https://github.com/webrecorder/archiveweb.page)** - Browser extension for high-fidelity web archiving.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** Browser
* **[ReplayWeb.page](https://github.com/webrecorder/replayweb.page)** - Serverless web archive replay in the browser.
  - **Type:** Library
  - **Open Source:** Yes
  - **Platform:** Browser
* **[pywb](https://github.com/webrecorder/pywb)** - Python toolkit for recording and replaying WARC archives.
  - **Type:** Library
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[webrecorder-player](https://github.com/webrecorder/webrecorder-player)** - Desktop app for offline web archive replay.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[ipwb](https://github.com/oduwsdl/ipwb)** - Distributed web archive replay system built on IPFS.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux / Docker
* **[Webrecorder](https://webrecorder.net/)** - Interactive capture and replay service for web archives.
  - **Type:** Service
  - **Open Source:** No
  - **Platform:** Cloud / Browser

### Analysis & Data Processing
* **[Archives Unleashed Toolkit (AUT)](https://github.com/archivesunleashed/aut/)** - Toolkit for analyzing web archives.
  - **Type:** Library
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[AUT Notebooks](https://github.com/archivesunleashed/notebooks)** - Example notebooks for working with AUT outputs.
  - **Type:** Library
  - **Open Source:** Yes
  - **Platform:** Browser
* **[warcio](https://github.com/webrecorder/warcio)** - Streaming library for fast WARC/ARC IO.
  - **Type:** Library
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[Metawarc](https://github.com/datacoon/metawarc)** - Extracts metadata from WARC files.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS
* **[WarcDB](https://github.com/Florents-Tselai/WarcDB)** - Stores crawl data in SQLite databases.
  - **Type:** Library
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[ArchiveSpark](https://github.com/helgeho/ArchiveSpark)** - Spark framework for processing web archives.
  - **Type:** Library
  - **Open Source:** Yes
  - **Platform:** Linux / Docker
* **[CDX Toolkit](https://github.com/cocrawler/cdx_toolkit)** - Tools for working with CDX indices.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

### Capture Operators & Services
* **[ArchiveBox](https://github.com/ArchiveBox/ArchiveBox)** - Self-hosted web archiving for URLs, feeds, and bookmarks.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Docker
* **[Wayback](https://github.com/wabarc/wayback)** - Toolkit for archiving webpages to multiple targets.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[Archivenow](https://github.com/oduwsdl/archivenow)** - Command-line tool to push resources into web archives.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[iagitup](https://github.com/gdamdam/iagitup)** - Archives GitHub repositories to the Internet Archive.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[Archive-It](https://archive-it.org/)** - Subscription web archiving service from the Internet Archive.
  - **Type:** Service
  - **Open Source:** No
  - **Platform:** Cloud

## Social Networks

Tools for collecting content from social platforms.

### Twitter
* **[twarc](https://github.com/DocNow/twarc)** - Command-line tool and Python library for archiving Twitter JSON.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

### Instagram
* **[instaloader](https://github.com/instaloader/instaloader)** - Downloads Instagram media and metadata.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

### Universal
* **[sfm-ui](https://github.com/gwu-libraries/sfm-ui)** - Social Feed Manager user interface application.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS
* **[Media Downloader](https://github.com/awesome-yasin/Media-Downloader)** - Multi-platform media downloader for social sites.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

## Other Digital Objects

Tools for archiving content beyond traditional web pages.

### Online Storage
* **[ydiskarc](https://github.com/ruarxive/ydiskarc)** - Backs up public Yandex Disk resources.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[filegetter](https://github.com/ruarxive/filegetter)** - Collects files from public data sources using URL patterns.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

### Messengers & Chats
* **[tgarc](https://github.com/ruarxive/tgarc)** - Archives Telegram JSON.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

### Specific CMS
* **[wparc](https://github.com/ruarxive/wparc)** - Archives WordPress API data and files.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[spcrawler](https://github.com/ruarxive/spcrawler)** - Backs up SharePoint public installations via API.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

### Public Data API
* **[apibackuper](https://github.com/ruarxive/apibackuper)** - Backs up API calls with a Python library and CLI.
  - **Type:** Library
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

## Preservation Frameworks & Platforms

End-to-end systems for ingest, storage, and access.

* **[Archivematica](https://www.archivematica.org/)** - OAIS-aligned preservation workflow system.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux / Docker
* **[DSpace](https://dspace.lyrasis.org/)** - Repository platform for research outputs and collections.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux / Docker
* **[Fedora](https://fedorarepository.org/)** - Modular repository platform for digital assets.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux
* **[Islandora](https://islandora.ca/)** - Fedora-based repository framework for cultural heritage.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux
* **[Preservica](https://preservica.com/)** - Commercial digital preservation platform.
  - **Type:** Service
  - **Open Source:** No
  - **Platform:** Cloud
* **[DuraCloud](https://www.duracloud.org/)** - Hosted preservation storage and access platform.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Cloud

## Preservation Storage & Replication

Systems focused on preservation storage, replication, and integrity.

* **[LOCKSS](https://www.lockss.org/)** - Distributed preservation network for replicated content.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux / Cloud
* **[iRODS](https://irods.org/)** - Data grid for preservation storage, policy, and replication.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux / Cloud
* **[Archivematica Storage Service](https://www.archivematica.org/en/docs/storage-service-0.18/)** - Storage management component for Archivematica.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux / Docker

## File Format Identification & Validation

Tools for identifying and validating file formats.

* **[DROID](https://www.nationalarchives.gov.uk/information-management/manage-information/preserving-digital-records/droid/)** - File format identification tool from The National Archives (UK).
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[JHOVE](http://jhove.openpreservation.org/)** - Validates and characterizes digital objects.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[FITS](https://projects.iq.harvard.edu/fits)** - File Information Tool Set for format identification.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[MediaConch](https://mediaarea.net/MediaConch)** - Media format validation and policy checking.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[PRONOM](https://www.nationalarchives.gov.uk/PRONOM/Default.aspx)** - Format registry and signatures.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Browser
* **[Siegfried](https://github.com/richardlehane/siegfried)** - Signature-based file format identification tool.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[FIDO](https://github.com/openpreserve/fido)** - Format identification tool using PRONOM signatures.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

## Fixity & Packaging

Tools and standards for checksums and packaging.

* **[BagIt](https://datatracker.ietf.org/doc/html/rfc8493)** - Packaging format for transferring digital content.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[Bagger](https://github.com/LibraryOfCongress/bagger)** - GUI tool for creating BagIt packages.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[Fixity](https://github.com/avpreserve/fixity)** - Fixity checking and monitoring tool.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** Windows / macOS
* **[bagit-python](https://github.com/LibraryOfCongress/bagit-python)** - Python library for creating and validating BagIt packages.
  - **Type:** Library
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

## Emulation & Virtualization

Tools for preserving software environments and legacy systems.

* **[EaaSI](https://eaasi.gitlab.io/)** - Emulation-as-a-Service Infrastructure.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux / Cloud
* **[QEMU](https://www.qemu.org/)** - Open-source machine emulator and virtualizer.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[DOSBox](https://www.dosbox.com/)** - Emulator for running legacy DOS software.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

## Audio-Visual & Media Preservation

Tools for preserving and analyzing audiovisual materials.

* **[FFmpeg](https://ffmpeg.org/)** - Command-line toolkit for audio and video processing.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[MediaInfo](https://mediaarea.net/MediaInfo)** - Displays technical metadata for media files.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[ExifTool](https://exiftool.org/)** - Reads and writes metadata for media and image files.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[BWF MetaEdit](https://bwfmetaedit.sourceforge.net/)** - Edits and validates Broadcast Wave Format metadata.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[QCTools](https://mediaarea.net/QCTools)** - Quality control and analysis for audiovisual preservation.
  - **Type:** GUI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

## Digital Forensics & Ingest

Tools for capture and forensic workflows before preservation ingest.

* **[BitCurator](https://bitcurator.net/)** - Digital forensics environment for archivists.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Linux
* **[The Sleuth Kit](https://www.sleuthkit.org/)** - File system and disk analysis tools.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[Brunnhilde](https://github.com/timothyryanwalsh/brunnhilde)** - Digital preservation reporting on file collections.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows
* **[Bulk Extractor](https://github.com/simsong/bulk_extractor)** - Extracts features from disk images for analysis.
  - **Type:** CLI
  - **Open Source:** Yes
  - **Platform:** Linux / macOS / Windows

## Metadata Standards & Tools

Metadata schemas and tools commonly used in preservation workflows.

* **[PREMIS](https://www.loc.gov/standards/premis/)** - Preservation metadata standard.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[METS](https://www.loc.gov/standards/mets/)** - Metadata Encoding and Transmission Standard.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[Dublin Core](https://www.dublincore.org/)** - Core metadata vocabulary.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[MODS](https://www.loc.gov/standards/mods/)** - Metadata Object Description Schema.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[EAD](https://www.loc.gov/ead/)** - Encoded Archival Description.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A

## Preservation Planning, Risk & Policy

Frameworks and guidance for policy, maturity, and planning.

* **[NDSA Levels of Preservation](https://ndsa.org/levels-of-digital-preservation/)** - Practical preservation levels framework.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[DPC RAM](https://www.dpconline.org/digipres/maturity-models/dpc-ram)** - Rapid assessment maturity model.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[DRAMBORA](http://www.repositoryaudit.eu/)** - Digital repository audit methodology.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A

### Policy & Audit
* **[TRAC](https://public.ccsds.org/Pubs/652x0m1.pdf)** - Trustworthy Repositories Audit & Certification criteria.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[ISO 16363](https://www.iso.org/standard/56510.html)** - Audit and certification for trustworthy digital repositories.
  - **Type:** Standard
  - **Open Source:** No
  - **Platform:** N/A
* **[CoreTrustSeal](https://www.coretrustseal.org/)** - Certification for trustworthy data repositories.
  - **Type:** Service
  - **Open Source:** No
  - **Platform:** Browser

## Training, Education & Best Practices

Learning resources for practitioners and teams.

* **[DPC Training](https://www.dpconline.org/digipres/train-your-staff)** - Digital preservation training resources.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Browser
* **[Digital Preservation Handbook](https://www.dpconline.org/handbook)** - Practical guidance from the DPC.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Browser

## Conferences, Events & Communities

Groups and events that share preservation knowledge.

* **[iPRES](https://ipres2025.jp/)** - International digital preservation conference series.
  - **Type:** Service
  - **Open Source:** No
  - **Platform:** Browser
* **[NDSA](https://ndsa.org/)** - National Digital Stewardship Alliance community.
  - **Type:** Service
  - **Open Source:** No
  - **Platform:** Browser

## Standards and Specifications

Core technical standards used in web archiving.

* **[WARC Format 1.1](https://iipc.github.io/warc-specifications/specifications/warc-format/warc-1.1/)** - Web ARChive file format for bundling resources.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[CDX File Format](https://iipc.github.io/warc-specifications/specifications/cdx-format/cdx-2006/)** - Index format for WARC files.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[WARC Specifications](https://iipc.github.io/warc-specifications/)** - Collection of WARC-related specs.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A
* **[WACZ Format 1.1.1](https://specs.webrecorder.net/wacz/1.1.1/)** - Web Archive Collection Zipped media type.
  - **Type:** Standard
  - **Open Source:** Yes
  - **Platform:** N/A

## Organizations

* **[Digital Preservation Coalition](https://www.dpconline.org/)** - Not-for-profit organization supporting preservation initiatives.
  - **Type:** Service
  - **Open Source:** No
  - **Platform:** Browser
* **[International Internet Preservation Consortium](https://netpreserve.org/)** - Consortium focused on web archiving.
  - **Type:** Service
  - **Open Source:** No
  - **Platform:** Browser

## Knowledge Bases

* **[ArchiveTeam Wiki](https://wiki.archiveteam.org/)** - Community knowledge base for web archiving and tools.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Browser

## Major Digital Archives

* **[Internet Archive](https://archive.org/)** - Large public web and digital archive.
  - **Type:** Service
  - **Open Source:** No
  - **Platform:** Browser
* **[Common Crawl](https://commoncrawl.org/)** - Open web crawl datasets and index.
  - **Type:** Service
  - **Open Source:** No
  - **Platform:** Browser

## Related Lists

* **[Awesome Web Archiving](https://github.com/iipc/awesome-web-archiving)** - Awesome list focused on web archiving.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Browser
* **[Awesome Data Takeout](https://github.com/ivbeg/awesome-data-takeout)** - Tools for exporting personal data.
  - **Type:** Service
  - **Open Source:** Yes
  - **Platform:** Browser

## Maintenance

Please check links and descriptions at least quarterly. When adding new entries,
prefer stable URLs and clearly note if a tool is archived or unmaintained.

## How to Contribute

Contributions are welcome. To add a new resource:

1. Confirm it is directly related to digital preservation.
2. Add it to the most appropriate section (or propose a new one).
3. Use this format:

   ```markdown
   * **[Tool Name](URL)** - One sentence on what it does and who it is for.
     - **Type:** CLI / GUI / Service / Library
     - **Open Source:** Yes/No (license if known)
     - **Platform:** Linux / macOS / Windows / Browser / Docker
   ```

4. Open a pull request with a short rationale for inclusion.