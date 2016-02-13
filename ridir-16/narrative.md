---
output: word_document
bibliography: ridir-16.bib
csl: pnas.csl
---

# Making the Hidden Visible

## PROJECT SUMMARY (1 p)

The widespread capacity to share and exchange data over the internet has transformed scholarship, but technical problems with incompatible formats, applications, and specialized proprietary environments hinder the free exchange of data.
Video recordings rely on myriad established industry format and codec standards such than almost any video can be easily converted for any use, but the various annotation metadata that researchers laboriously generate in the process of their research largely remain locked in incompatible, often proprietary formats.
This project proposes to extend the success that the NSF- and NICHD-supported Databrary (databrary.org) digital library has had with increasing video sharing to promote sharing, accessibilty, and reusability of video coding data as well.
This will make it easier for behavioral scientists who annotate or code video data to exchange, share, convert, access, and reuse their coding data, in order to increase the value and discoverability of the associated shared videos.

Video constitutes a primary means of recording behavior in home, lab, classroom and museum settings for researchers in the developmental sciences and in other fields from anthropology to linguistics, ethology to human-computer interaction (@derry_conducting_2010, @goldman_video_2014, @alibali_embodiment_2012, @masats_rethinking_2011, @pasqualino_filming_2007, @qualitative_data_repo, @cmdbase_ethology_video_archive, @chaquet_survey_2013, @rautaray_vision_2012).
Video powerfully captures behavior unfolding in real time and depicts how behavior changes across development, and researchers already spend many hours using specialized tools to meticulously code the subset of these behaviors relevant to their research.
Video data collected for one purpose can be readily reused for other purposes beyond those envisioned by the original researchers, and in doing so these new analyses can leverage the original coding data, but only if they are shared and readable.
With the creation of Databrary, the number of researchers actively sharing video and reusing shared video has grown, and we now aim to similarly increase the range and value of coding data as well.

This project proposes to enhance Databrary so that:
1. Transcripts, annotations, and codes researchers apply to video using specialized, but incompatible, software tools can be uploaded, imported, visualized, searched, and downloaded from Databrary.
2. Researchers can browse codes produced by others, share coding files across geographically distant locations, and build upon codes contributed by others while Databrary keeps track of file changes, thereby promoting transparency and reproducibility in research.
3. Information about annotations and codes contained in coding manuals or other files can be uploaded, imported, indexed, visualized, searched, and downloaded from Databrary.
4. Researchers can search for specific segments of video based on codes, tags, or keywords.

**Intellectual Merit.** This project will enhance the Databrary digital library, a "user-friendly large-scale next-generation data resource" that already serves a growing community of several hundred developmental and learning scientists.
The enhancements will add significant value to Databrary's extensive existing library of reusable video data by integrating a previously inaccessible and invaluable set of expertly coded and micro-detailed annotations describing and enriching those videos.
The new sources of data will be made accessible in a variety of formats for reuse, allowing researchers to work in the tools with which they are most familiar and are best suited to their research questions and analyses.
Interoperability among codes will enable new multidisciplinary research questions to be asked based on existing, already collected and shared video data.
By incorporating annotations and code definitions, the enhancements will enable Databrary users to more readily seek, find, and reuse shared video data.

**Broader Impacts.**
The proposed enhancements will make datasets shared on Databrary, many of them previously funded by NSF and NIH, more findable, accessible, interoperable, and reusable [@_fair_2014].
The project will have impacts across the social, behavioral, biological, and educational sciences that involve video data collection.
The enhancements will make it substantially easier for scientists at institutions with limited resources for research to participate in scientific discourse about human behavior by building on the expensive-to-collect data gathered by others.
The project will make data sharing more appealing to scientists, and this should increase the number of researchers who share, the diversity of the data sets they share, the quality of data shared, and the pace of data sharing.
This will improve transparency and boost reproducibility.
Since some dataset metadata and possibly entire datasets will be available for public viewing, we will raise the profile of video-based research and bolster interest in and support for the behavioral sciences among the public at large.

(*Broader impacts: http://www.nsf.gov/pubs/2007/nsf07046/nsf07046.jsp*)

## PROJECT DESCRIPTION

<!--Video exists and people code it to analyze behavior-->
Video constitutes a primary means of recording behavior in home, lab, classroom and museum settings for researchers in the developmental and learning sciences and in other fields from anthropology to linguistics, ethology to human-computer interaction <!--look for Derry, S., Pea, R. and other similar citations to include here-->.
Video powerfully captures how behavior unfolds in real time and depicts how it changes in different contexts and across development.
Even without extensive metadata, video data collected for one purpose can be readily reused for other purposes beyond those envisioned by the original researchers
However, many researchers spend hours meticulously coding the subset of these behaviors relevant to their research.
Coded data files may contain information about who was involved or spoke, what happened or was said, when, where, and for how long.
New analyses can build upon the codes, but only if these are shared and stored in ways not specific to a particular investigator.
With the creation of Databrary, the number of researchers committed to sharing and reusing video has grown.
We now aim to expand the kind and depth of analyses they can conduct by enabling Databrary to store and share coding data files that are linked to shared videos.

### Challenge
<!--What tools are used and what the process is like-->
Most researchers who code video use paper and pencil, spreadsheets, or tools specialized for entering speech transcriptions or applying annotations or codes to selected points or segments in time.
The specialized tools most commonly used by developmental researchers [@gilmore_video_2016] -- CLAN [@CLAN_2016], Datavyu [@datavyu_2016], ELAN [@ELAN_2016], Mangold Interact [@_mangold_2016], Noldus Observer XT [@_noldus_2016], and Transana [@_transana_2016] -- enable analysts to move backwards and forwards through digital videos at varied speeds.
Analysts easily apply annotations time-locked to the video segments.
The codes form the basis of subsequent quantitative and qualitative analyses.
To ensure reliable, reproducible, and robust results, most researchers augment their annotations with rich, textual descriptions of the behaviors of interest, codified in separate coding manual files saved in word processing or spreadsheet formats [@gilmore_video_2016].
Taken together, the coding data files and manuals contain invaluable, expensive-to-acquire, human-validated, text-based information about the contents of raw video recordings.

<!--Incompatibilities of existing coding tools and problems of moving data around-->
With a few notable exceptions, the tools store data in incompatible, proprietary, and non-interoperable formats.
Import and export among them can be difficult to impossible.
Researchers may need to hire technical experts simply to collaborate with a colleague who uses an incompatible tool.
Those without access to technical expertise or a compatible tool may simply abandon an attempt to reuse shared data.
Few efficient and secure means exist for sharing videos with linked coding files; those that do exist support only a restricted set of file formats.

#### Opportunity

The videos linked to coding files and manuals generated by researchers constitute a substantial resource for new discovery with significant potential to catalyze novel research.
This potential lies unrealized until the materials are made readily available in interoperable formats.
Databrary has demonstrated that researchers will embrace the practice of sharing video data if barriers are reduced and appropriate incentives exist.
We believe this will extend to coding data files and manuals, as well.
We must, therefore, make it easy for users to share and exchange these files on a convenient functional platform.
This involves allowing users to upload and download the files in whatever format best suits their purposes.
The hard-won information contained within the files can then be made fully accessible and available to researchers for a myriad of uses, and its potential for reuse by others fully realized.

Accordingly, we propose to expand Databrary's capabilities to import and export transcripts, annotations and codes about videos that are already collected and coded by researchers, but not easily or readily shared.
We propose to make codes and code definitions currently stored in incompatible file formats interoperable with one another.
Where coding files contain metadata useful for search, we will import the information and add it to Databrary's search functionality.

These enhancements will accelerate the pace of video data sharing and reuse in the developmental and learning sciences, a field where there is a well-identified community of hundreds of researchers who use video as a primary means of data collection.
Our efforts will leverage and increase the value of NSF's prior investments in Databrary and create opportunities for new research in other areas of behavioral sciences that use video or audio recordings as raw data.
Ultimately, the project will enable new, cross-disciplinary, multi-level, and integrative research on human behavior that is currently prohibitively expensive, if not impossible.

### Project Aims

The project is organized around four aims.

#### Aim 1: Enable codes and annotations from targeted video coding tools to be imported to and exported from the Databrary video library.

Databrary currently supports uploading, storing, and sharing coding files but cannot extract their contents or link them to videos.
Working closely with a technical advisory committee (TAC) representing the leading academic and commercial video coding software tools (see Appendix A) commonly used by the majority of developmental researchers, we will expand Databrary's understanding of and ability to work with these files.
Databrary will develop ways for users to exchange between these formats and link them with the original video source.

Import functionality will bring the codes into the Databrary system and make the codes available for visualization and search within a dataset and across the library.
Databrary will also build the capacity to export imported codes back into their native formats wherever possible, as well as to more user-consumable formats (e.g., CSV).
The features will reduce barriers to sharing coded videos across labs that use different coding tools and allow users to build upon codes generated by others.

#### Aim 2:  Expand and extend Databrary's system for visualizing user-defined video codes.

Many researchers apply layers of codes derived from multiple coding passes through the same videos, following established best-practices in video data coding [@best_practices].
Databrary's existing "timeline" interface for depicting tagged video segments will be modified to allow users to display, filter, and download the codes or passes that have been applied to shared video sessions.
This will require Databrary to store and represent information from multiple coding passes within the same coding file and codes from multiple coding files.
Databrary will also be modified to track and report version changes in coding spreadsheets and coding passes.
This will make it substantially easier for Databrary users to share coding efforts on the same shared videos across geographically separate labs and will maximize the transparency and reproducibility of codes applied to video segments.

#### Aim 3:  Design and implement ways for Databrary to upload, import, index, visualize, make available for search, and export the information about specific behavioral codes contained in coding manuals or coding file templates.

Databrary currently allows users to upload and share coding manuals in word processing, spreadsheet, and text based file formats, but information in the files cannot be easily accessed or searched.
We will develop ways for users to enter and share coding manuals with Databrary, creating electronic equivalents that capture code definitions and make them searchable.
We will also develop ways to extract code definitions from those coding tools whose files store them.
This will help the search engine return more relevant and useful information to users, and it will provide better, more human-readable information for visualizing the codes while previewing recordings.

#### Aim 4:  Design and implement a user interface and database structure that empowers authorized Databrary users to search for specific segments of video based on codes, tags, or keywords linked to those segments.

Databrary currently allows users to search across collections of videos for selected terms.
The information contained in the coding files will be indexed by Databrary's search engine as described in Aim 1.
We will design, implement, test, and refine back-end technologies and user interfaces that return within-video search results in ways that make it easy for users to click on and preview video segments the search engine finds.
The interface will allow users to select and download selected segments for future reanalysis using the desktop video coding tools that are part of a user's current workflow.
These features will make it easy for Databrary users to discover, preview, copy, and reanalyze video datasets that meet the specific requirements of their research question while keeping careful track of data sources and provenance.

### Background and Rationale

Open data sharing has become a scientific imperative across disciplines.
It is common practice in many areas of biomedical [@kaye_data_2009], physical [@young_crowd_2010], biological [@reichman_challenges_2011] and earth sciences [@kleiner2011data], and it is an emerging priority in neuroscience [@poldrack_making_2014, @poline_data_2012].
Despite notable efforts to make data sharing a norm in the behavioral sciences [@_aera_2011, @nosek_scientific_2012] most research on human learning and development remains shrouded in a culture of isolation [@adolph_toward_2012, @gilmore_big_2016].
Researchers share interpretations of distilled, not raw data, almost exclusively through publications and presentations.
The path from raw data to findings to conclusions can rarely be traced or validated by others, nor can other researchers easily pose new questions that build on the same raw materials.

<!--Coding manuals-->
The codes form the basis of quantitative and qualitative analyses that researchers report in journal articles, talks, and presentations.
To ensure reliable, reproducible, and robust results, most researchers produce a coding manual to define how the behaviors of interest should be coded.
These coding manuals vary in the degree of detail and depth used to describe or illustrate the behaviors of interest, and may be kept as separate documents or integrated in the coding tool.
Taken together, the codes and manuals contain invaluable, expensive-to-acquire, human-validated, text-based information about the contents of raw video recordings.

#### The growth and potential of video as data

Hundreds of researchers who study learning and development collect video recordings in home, laboratory, classroom, and museum contexts.
The applicants recently conducted an electronic survey of members of the email lists of the International Congress for Infant Studies (ICIS), the Cognitive Development Society (CDS), and lists of users of the Datavyu and Databrary software tools [@gilmore_video_2016].
Of the 259 respondents, 100 reported collecting more than 5 hours of video per week [@gilmore_video_2016].
The scale of some large collaborative projects is even larger.
The Measures of Effective Teaching Project [@met_project], funded by the Gates Foundation, generated more than 1,000 videos from K-12 classrooms, covering core subjects such as mathematics and language arts from multiple camera angles.
The data, constituting tens of terabytes of storage, are hosted at the University of Michigan [@met_data_icspr] and streamed to registered viewers across the country.
The NSF-funded HomeBank project [@homebank], affiliated with the TalkBank/CHILDES archive [@talkbank_site], is collecting and sharing hundreds of hours of naturalistic audio recordings of children's speech, some of which will be accompanied by video [@talkbank_video_exemplar].
The Autism and Beyond Project at Duke University [@autism_beyond] has deployed an iPhone application that will collect video images of children's facial expressions in order to evaluate the feasibility of using computer vision techniques to screen children in their homes for developmental disorders and risk of mental illness.
These examples illustrate how the widespread availability of low-cost, high resolution cameras has made video a large and rapidly growing source of information about human behavior.

#### Video enables behavioral science research, but poses special challenges

Video documents the richness and complexity of human behavior -- the interactions between people and their environment -- unlike any other form of measurement.
Video records what people say and what they do.
It captures when, where, and how they look, gesture, move, and communicate, and how their looking, gesturing, moving, and communicating correspond to what others are doing.
Because of these characteristics, video -- and before that, film -- has a long history in the study of learning and development [@goldman_video_2014, @curtis_tangible_2011].
Because video closely mimics the visual and audio experiences of live human observers, recordings collected by one person for a particular purpose may be readily understood by another person and reused for a different purpose.
Capitalizing on the unique potential of large-scale video data collections, however, requires overcoming a set of challenges associated with sharing video data.

**Videos contain personally identifiable information; this poses problems for the protection of participant privacy**.
Although policies exist for sharing de-identified text-based data, video contains easily identifiable information: faces, voices, spoken names, interiors of homes and classrooms, and so on.
Removing identifiable information from video severely diminishes its value for reuse and puts additional burdens on researchers.
So, video sharing requires policies that protect the privacy of research participants while preserving the integrity of raw video for reuse by others (see pp. X-X).

**Large file sizes and diverse formats present technical challenges**.
Video files are large (one hour of HD video can consume 10 GB of storage) and come in varied formats (from cell phones to high-speed video).
Many studies require multiple camera views to capture desired behaviors from different angles.
The cameras and other data streams must be synchronized for detailed analysis.
Thus, sharing videos requires substantial storage capacity and significant computational resources for transcoding videos into common formats that can be preserved over the long term and for synchronizing multiple streams.

**Video sharing poses practical challenges of data management**.
Researchers report lacking time to find, label, clean, organize, and copy their files into formats that can be used and understood by others [@ascoli_ups_2006], and most lack training or expertise in standard practices of data curation.
Study designs vary widely, and no two labs manage data in the same way.
Idiosyncratic terminology, record-keeping, and data management practices are the norm.
Few researchers reliably document workflows or data provenance.
Although video requires minimal metadata to be useful, video files must be electronically linked to what relevant metadata exist including information about whether participants have given permission to share.
When researchers do share, standard practice involves organizing data after a project is finished, perhaps when a paper goes to press.
This "preparing for sharing" after the fact presents a difficult and unrewarding chore for investigators.
It makes curating and ingesting datasets challenging for repositories, as well [@gordon_researcher-library_2015].

**Technical and practical challenges involved in extracting behavioral patterns from videos present barriers**.
Videos contain rich and diverse information that requires time consuming work by human observers to extract.
Researchers make use of videos by watching them and, using paper and pencil or more automated computerized coding software, translating observations into ideas and numbers.
In principle, human-applied codes and annotations could make the contents of videos searchable by others.

However, most coding files consist of letter or numeric codes coupled to time stamps or a time interval.
These minimal codes simplify the laborious task of manually coding video by allowing users to press single buttons on a computer keyboard to record specific behavioral events.
For example, "M" may mean a baby is in motion in one study but "Mother is speaking" in another.
Single character codes make for efficient coding, but lack transparency and make search and reuse difficult.
To resolve this ambiguity for themselves and their collaborators, researchers regularly generate richer, narrative or even image or video-segment-based definitions of codes in separate coding manuals.
Some coding tools store code definitions in specialized fields.
The software coding tools many researchers use to put annotations in a digital form employ incompatible data formats, and coding manuals or code definition files are rarely shared with other researchers outside the original team.
Moreover, researchers focus on different questions from varied theoretical perspectives and lack consensus on conceptual ontologies.

So, in practice, most coded video data are not easily shared.
Nor do automated video coding tools provide a workable solution.
Not only do machine learning and computer vision tools require a human-generated ground truth for training and validation, but the tools are not yet capable of efficiently replacing the judgments of trained human coders across the diversity of tasks studied by behavioral scientists.

#### The Databrary digital library overcomes many of these barriers

Mindful of these challenges but motivated by the scientific promise of video data sharing, PIs established databrary.org, the first-of-its-kind library for storing and sharing video data and associated metadata.
Databrary was created with support from NSF (BCS-1238599) and NICHD (U01-HD-076595) and has garnered additional funding from the Society for Research in Child Development.
From the beginning, Databrary sought to create a secure home for research videos in the developmental and learning sciences in order to foster widespread data reuse and enhance transparency.
We targeted the developmental and learning sciences community because the PIs are developmentalists, and this community regularly collects and analyze video.
But, we designed Databrary so the system could be adapted for and used by other researchers in the behavioral sciences.
The code is fully open source [@databrary_github].

Databrary began public operation in the spring of 2014.
The library has since grown to encompass 262 authorized investigators [@databrary_investigators] and 143 affiliate investigators from 163 institutions [@databrary_institutions] around the world.
These investigators have contributed more than 3,600 hours of video or audio recordings, representing some 3,400 participants ranging in age from 6 weeks to middle age.
The system stores 162 volumes or datasets, of which 55 are currently shared with the community of authorized researchers or with the public.

Databrary permits users to upload, store, organize, and share data with collaborators, the full community of authorized Databrary users, or the public, depending on the level of sharing permission granted by participants.
Users may also search for, browse, view, and download videos stored on the site.
Users may view specific characteristics of videos such participant ages or recording context (home, lab, or school) for recoding and reanalysis.
Databrary empowers users to stream in the browser or download videos or video highlights -- clips that may be shown for educational or research purposes like lectures or talks.
Thus, Databrary supports data sharing, data reuse, and pre/non-research uses of shared videos and associated materials.
The system does so while solving some of the thorniest problems associated with sharing video.

##### Databrary's policies enable the sharing of identifiable data

Policies for sharing identifiable data in ways that securely preserve participant privacy are essential for sharing research video.
Databrary does not attempt to de-identify videos.
Instead, Databrary maximizes the potential for video reuse by keeping recordings in their original unaltered form.
To make unaltered raw videos available to others for reuse, Databrary has developed a two-pronged access model that (a) restricts access to researchers who register and are granted formal authorization by their institutions [@databrary_agreement], and (b) enables access to identifiable data only with the explicit permission of the participants, an extension of the principle of informed consent.
Databrary has created template language [@databrary_release] for seeking participants' permission to share data that researchers may adapt for their own use.
These policies are spelled out fully in an online user guide [@databrary_policies].

Unique among data repositories, the Databrary Access Agreement authorizes both data use and contribution.
However, users agree to store on Databrary only materials for which they have ethics board or IRB approval.
Data may be stored on Databrary for the contributing researcher's use regardless of whether the records are shared with others or not.
When a researcher chooses to share, Databrary makes the data available to the community of authorized researchers.

The framework, with minimal modification, has been agreed to by more than 160 institutions in North and South America, Europe, Asia, and Australia, and the number grows daily [@databrary_institutions].

##### Databrary's technology overcomes technical barriers to video data sharing

To address the problem of diverse video formats, Databrary automatically transcodes each recording using NYU's high performance computing services into a common format suitable for web-based streaming (currently H.264+AAC in MP4 for video).
The system maintains a copy in the original format for long-term preservation.
To address file storage limitations, Databrary does not currently place limits on the number or size of files that can be uploaded.
Databrary's current assets total 17TB and are stored on NYU's central IT storage which provides one off-site mirror and regular long-term tape backups.

##### Databrary's design overcomes practical barriers to sharing

Databrary has developed a novel active-curation framework that reduces the burden of post hoc data sharing [@gordon_researcher-library_2015].
The system empowers researchers to upload and organize data as it is collected.
Immediate uploading reduces the workload on investigators, minimizes the risk of data loss and corruption, and accelerates the speed with which materials become available.
Databrary employs familiar, easy-to-use spreadsheet and timeline-based interfaces that allow users to upload videos, add metadata about tasks, settings, and participants, link related files, and assign appropriate permission levels for sharing.
To encourage immediate uploading, Databrary provides a complete set of controls so that researchers can restrict access to their own labs or to other users of their choosing.
Datasets can be shared with the broader research community at a later point when data collection and ancillary materials are complete, whenever the contributor is comfortable sharing, or when journals or funders require it.

With this active-curation framework, the cost in time and labor to researchers is equivalent to current lab practices of storing a copy of the video on a hard drive and entering the associated metadata into a spreadsheet.
Moreover, with this method, Databrary acts as the researcher's personal lab file server and cloud storage, enabling web-based sharing among members of the protocol and ensuring secure off-site backup.

#### Remaining gaps this project will fill

Despite these advances over the past three years, the Databrary team recognizes that there are barriers to widespread data sharing that we have not yet been able to address systematically.
Our survey [@gilmore_video_2016] indicated that most developmental and learning scientists who collect video use a specialized tool to code it (Datavyu, CHAT, ELAN, Mangold Interact, Noldus Observer XT, or Transana).
Almost all researchers augment information stored in the coding tools with text or image-based information about specific codes, stored in coding manuals.
The tools vary in their strengths, weaknesses, cost, customizability, and optimal use cases, but with few exceptions remain largely unable to talk to one another.
So, we think it is critical to enhance Databrary so that the information contained in coding files and coding manuals can be uploaded and stored on Databrary.
These enhancements will result in the following outcomes:

- Enabling Databrary to import, store, and share coding files from the leading video coding tools used by researchers in the developmental and learning sciences.
- Enabling search within videos based on these codes.
- Increasing interoperability among video coding tools.
- Making it easier for labs that use multiple coding tools to move and export data between them for analysis.
- Making it easier for researchers who use incompatible video coding tools to collaborate and build upon one another's findings.
- Capturing currently "hidden-to-outsiders" code definitions and related metadata vital for understanding and building upon a shared project's analyses.
- Encouraging standardization of documentation practices and documentation formats for coding definitions, and as a result making it possible for codes used by one research group to be compared with or built upon by other groups.
- Creating infrastructure that embodies recognized best-practices in video coding [@best-practices] and data management.
- Reducing the barrier posed by incompatible video formats by exploiting Databrary's existing infrastructure for transcoding.
- Filling gaps in current research workflows and reducing barriers that make sharing and reuse of video data harder than it needs to be.
- Enhancing the reproducibility and transparency of video-based analyses of human behavior.
- Automating version control for coding files, making it easier to track data provenance.
- Making it substantially easier for geographically dispersed researchers to share the burden of coding video and to collaborate on projects.
- Laying the groundwork for future enhancements that involve the integration of other temporally dense data streams, such as eye tracking, physiological measurements, kinematics.
- Positioning Databrary to take advantage of rapid developments in computer vision that focus on the automated or semi-automated tagging of static images or video segments.
- Making Databrary more useful and attractive to an even wider range of researchers across the behavioral sciences.
- Leveraging the existing investments that NSF and NICHD have made in creating Databrary.

In turn, the project will enable new, integrative, multidisciplinary research that is at present difficult, time consuming, and prohibitively expensive to conduct.
It may soon be possible for researchers who are interested in, for example, children's laughter, to search across the library for examples of children laughing.
From the returned videos, the researcher may select only those with coded language transcripts or which show the children's face so that facial expressions can be coded.
Based on summary, participant- and dataset-level metadata stored in Databrary, the researcher can evaluate the geographic (region of origin) and demographic (race, ethnicity, languages spoken, sex/gender) characteristics of the sample to ensure that it suits her needs.
She notes that the sample includes many children from bilingual homes, and she makes a note to talk with the cultural anthropologist colleague she has been wanting to collaborate with.
The researcher can compare code definitions from the set of shared coding manuals to determine whether she agrees with other researchers' definitions of what constitutes child laughter.
In browsing the videos found in the search, the researcher discovers that one dataset includes codes related to children's gestures.
The researcher hadn't considered coding motor behavior, but since a detailed coding manual was shared, she decides to select those materials, as well.
Satisfied that the search has yielded useful data for her project, the researcher downloads the relevant videos, coding files in the format of her choice, coding manuals, and other materials.
The researcher begins annotating the downloaded videos using her own coding scheme and, since it is easy to do, the researcher shares the resulting coding files and code definitions back to Databrary.
The new set of codes and definitions are linked to the previously shared videos so that other researchers can validate or build upon the findings.

We describe how this scenario can be realized in the Implementation Plan.

### Implementation Plan

The implementation plan consists of four main projects aligned with the specific aims.
The sections below describe the main phases in general terms, with specific technical details provided in the [Technical Plan](technical-plan.md) addendum.
See Figure X in that addendum for a project timeline.

#### Project 1: Code import, representation/visualization, and export

Project 1 focuses on importing coding files from the leading software coding tools used by developmental scientists, representing and visualizing codes within Databrary, and exporting coding files in their native formats.
Despite significant variation across coding tool platforms, at one level, all of the codes we intend to import are usually simple data structures.
Each code consists of a start time, an optional end time, and an associated set of alphanumeric characters or data structures.
Coding files consist of one or more arrays of these codes, organized into separate, possibly hierarchical or nested "passes".
Databrary's existing data model includes an internal representation that allows users to apply simple text-based tags to temporal segments of specific videos.
We will extend this foundation in building the coding file import capabilities that are part of Project 2.

##### Project 1.1: Import and export Datavyu coding files.

We will start by making Databrary capable of importing spreadsheets generated by Datavyu (datavyu.org), the free, Java-based, open-source video coding tool maintained by Databrary and Project PI, Adolph.
Some 6 volumes on Databrary representing 230 video sessions contain spreadsheets coded in Datavyu.
Internal download data, support forum comments, and our survey of the video-using developmental science community suggest that there are hundreds of laboratories using Datavyu [@gilmore_video_2016].
The Datavyu file format is well-known to the Databrary team, so making Databrary capable of reading Datavyu spreadsheet files will be a test case, demonstrating the feasibility of other projects (2.2 - 2.6) focused on other data formats.
Because Datavyu uses a known format, we will also add to Databrary the capability of exporting codes in the Datavyu format.
At present, a user who exports from Databrary videos with linked Datavyu files must re-link the video files to the coding spreadsheet after downloading.
By developing capabilities within Databrary to read and write information to Datavyu files, we will eliminate this time-consuming step.
Co-I Simon will have available for consultation the current part-time Datavyu developer, Jesse Lingeman.

##### Project 1.2: Import ELAN coding files.

ELAN [@ELAN_2016] is a free video and audio annotation tool developed by researchers at the Max Planck Institute for Psycholinguistics in the Netherlands.
It is widely used in the psycholinguistics community and among respondents to our recent survey [@gilmore_video_2016].
It has special features for language researchers who use it to study language features from phonetics to pragmatics.
Han Sloetjes, one of the lead developerers on ELAN, has agreed to serve on the TAC and assist the project team to overcome hurdles involved in importing and exporting ELAN files (Appendix A).
ELAN is built in Java, like Datavyu, and the ELAN team has already consulted with the Databrary and Datavyu staff on challenges both tools face in importing and playing diverse video formats.
Import/export tools currently exist for converting ELAN files to and from the CHAT format used in CHILDES, TalkBank, and HomeBank (see Project 1.3 below).
ELAN coding data includes significantly more structure than Datavyu, including hierarchical and linked coding passes (called tiers), but we expect the basic coding information from ELAN files to be extractable, and simple versions to be exportable.
Project staff will build on these existing relationships in developing ELAN import/export features for Databrary.

##### Project 1.3: Import and export CHAT files.

TalkBank [@talkbank_site] is a collection of language-related databases that include transcripts, audio, and video data from children and adults.
Many of TalkBank's audio or video files are linked to text-based transcripts in the CHAT format [@CHAT_files_2015], developed for the Child Language Data Exchange System (CHILDES) Project.
CHAT files can be used with the Computerized Language ANalysis (CLAN) [@CLAN_2016] suite of software tools, a recognized standard in the language community.
TalkBank's founder and coordinator, Dr. Brian MacWhinney, serves on the Databrary advisory board and has agreed to serve on the TAC for the current proposal.
Professor MacWhinney will work with the project staff and PIs to allow CHAT-format transcripts linked with video or audio recordings to be imported into Databrary.
CHAT files are well-structured; the file specification is open and known; and Databrary staff have already done some preliminary work with CHAT-format transcripts.
However, CHAT files are unique in that transcription data is not directly linked to specific temporal codes, but instead specific points in the transcription text can be associated with points in the video or audio timestream.
For this reason, this format may have unique restrictions on which files can be imported and exported.

Support for CHAT-formatted transcripts is essential for interoperability with the NSF-funded HomeBank data archive project that focuses on collecting a large corpus of natural speech using the LENA [@LENA_foundation] recording device, linked with CHAT-formatted transcripts.
Databrary serves as a consultant on the HomeBank project, and works closely with its PIs, Dr. Anne Warlaumont (UC Merced), Dr. Mark VanDam (Washington State University), and Dr. Brian MacWhinney.
The leadership of both projects has determined that interoperability is an important priority for both projects given the considerable overlap in our research communities.
LENA files are stored in a fairly well documented XML format that our HomeBank colleagues have already gained working familiarity with.
Databrary staff will build on our colleagues' expertise and contacts in developing features for Databrary.

##### Project 1.4: Import and export files from Transana

Transana (http://www.transana.org/) is an open source software package that is used by researchers in the educational, learning, and developmental sciences to analyze digital video and audio.
Earlier phases of the project received support from both NSF and the TalkBank project at Carnegie Mellon.
Transana's lead developer, Dr. David Woods, has agreed to serve on the project's technical advisory committee (see Appendix A).
Transana already enables the full export of project codes and related metadata into an open XML format.
Transana also offers multi-user versions for lab groups who want to share and collaborate on coding audio or video files and a fee-for-service cloud storage feature.
Transana's capabilities extend well beyond video coding, but these facts give the project team confidence that some form of restricted Transana file import and export features can be added to Databrary.

##### Project 1.5: Import and export Mangold Interact files

Mangold Interact ([@mangold_interact] is a commercial video annotation tool used by more than 20% of respondents in our recent survey [@gilmore_video_2016].
Alongside its video collection, coding, and analysis software Mangold develops, sells, and supports integrated hardware and software laboratories for video and audio-based behavioral analyses.
Pascal Mangold, founder of Mangold International, has agreed to serve on the project's technical advisory committee (Appendix A).
Mangold Interact has several features the project team hopes to exploit in developing the import and export functionality for Databrary.
The software has a user-scripting function that enables coding files to be exported in a variety of formats for subsequent data analysis.
It stores study/project-level information separately from session-specific data, and allows users to create coding templates that contain structured representations of some of the information users now store in separate coding manuals.
Project staff will work with Mr. Mangold and his experts first to enable uploading and downloading of Mangold Interact files.
We will then strive to develop tools that import and export these coding files in their native format, or, in the worst case import files that have been exported by the Mangold software into an open, text-based (CSV or XML) format.

Beyond the project team's desire to serve this important segment of the developmental and learning sciences research community, Databrary staff believe that import/export functionality for Mangold Interact is important for another reason.
One of the largest (n=344 participants, 1,344 sessions) and most diverse video datasets currently stored and shared on Databrary comes from an NSF-funded longitudinal study led by Catherine Tamis-LeMonda [@Tamis-LeMonda_data].
Professor Tamis-LeMonda has available Mangold Interact format coding files, but has not yet shared these with Databrary.
Successful implementation of Mangold Interact import functionality may make it eventually possible to store and share these coded spreadsheets with Databrary alongside the already-shared videos, thus augmenting the current value of the shared data.
Unfortunately, some intermediate data from coding these videos that would allow the codes to be linked with the videos on Databrary has been lost, so this process may require significant effort and will require the project team to assess cost and feasibility prior to starting work.

##### Project 1.6: Import Noldus Observer XT files

Noldus Observer XT [@noldus_observer_XT] is a commercial software package produced by Noldus Information Technology that is specialized for the collection, coding, and analysis of audio, video, eye tracking and physiological data streams.
Noldus, like Mangold, develops, sells, and supports complete integrated hardware and software packages for multi-measure behavioral analyses.
Niek Wilmink, Product Portfolio Manager at Noldus, has agreed to serve on the project's technical advisory committee (see Appendix A).

Noldus Observer XT files are in a proprietary format, but the software has the capability of exporting codes and short code definitions stored in coding template files into a spreadsheet (Microsoft Excel) format.
Project staff will work with Mr. Wilmink and the Noldus team to build support within Databrary for uploading and downloading coding templates and files.
With support from our Noldus partners, project staff will investigate the possibility of functionality that allows Databrary to import Noldus files from their native formats into the Databrary back-end.
In the worst case, Databrary will build functionality to import files that are exported by the Noldus software into an open or easy-to-read format, like the Excel spreadsheet format used by the coding template export function.

#### Project 2: Timeline interface for viewing/selecting coding passes

Project 2 focuses on improvements to Databrary that make it easier for users to visualize what codes have been applied to shared video, to upload new coding passes to their own videos, and to do so with mechanisms in place that provide version control over coding files and coding manuals/definitions.
Once the user has identified a particular session of interest, we need to enable visualization of existing coding passes uploaded with this session.
Databrary needs to allow basic visualization and manipulation of these passes, so that users can preview the codes, select a subset of passes for download, and potentially upload newer versions of the coding passes.

##### Project 2.1 User interface for displaying data about code sources

Databrary has already implemented a timeline interface (*FIGURE*) that allows users to visualize temporal relationships among multiple phases of a data collection or data streams such as multiple camera views.
Project staff will augment this interface to allow users to visualize the different types of codes that have been applied to a particular video segment.
In addition, the interface will allow users to select or deselect specific codes so only those codes of interest are displayed.

The same iterative UI/UX design approach adopted in other parts of the project (4.3, 1.x, 3.1, 3.3) will be employed here.

##### Project 2.2 Back-end modifications to track changes to uploaded coding files

We aim to make Databrary the home for ongoing video coding projects to reduce the burdens of uploading and curating data for sharing after a project is complete.
Databrary already tracks when new or modified files are uploaded and by whom.
Staff will modify Databrary's existing back-end auditing/event-reporting features and will enhance existing ways of displaying version information to users.

A particular challenge this raises is how to track codes applied by Databrary users as part of a study that reuses or repurposes data collected and shared by another investigator.
We are in the early phases of designing back-end and UI/UX components that enable Databrary users to create their own studies from shared videos, but those details are not yet fully worked out.
So, at a minimum, we will provide and display version control information about coding files if those files were uploaded and shared by a researcher with write privileges on a dataset, in other words, the original data owner, their lab, and other collaborators.

#### Project 3: Importing rich, text-based code definitions

This project involves enhancing the capacity of Databrary so that the rich, text-based descriptions of behavioral codes, formalized in coding manuals often (but not always) stored separately from coding files, can be imported into Databrary.
The text in the manuals will be indexed by the Databrary search engine, and thus become searchable metadata.

Sixty-three percent of developmental researchers who responded to our survey [@gilmore_video_2016] report they "always" create detailed coding manuals that define behavioral codes associated with a particular study's set of analyses.
Respondents most often report creating these manuals using word processing or spreadsheet software.
Consequently, we know that coding manual information about videos is available; we just need ways to capture it systematically.

##### Project 3.1 Make existing Databrary functionality for storing coding manuals more salient to users

Databrary currently allows users to upload word processing, spreadsheet, PDF and other materials.
Relatively few researchers use this capability now to upload coding manuals.
So, the project team will explore design and styling changes to the site that make coding manuals visually distinctive when they are uploaded.
The team will also explore changes to the site's documentation, especially in the study design and active/self-curation portions, so that users are encouraged to upload coding manuals early on in the research process.

##### Project 3.2: Design back-end representation of coding manual information

While textual coding manuals are useful, unless the information contained therein can be associated with specific coding data, they cannot be used to enhance searching within videos.
Accordingly, project staff must enhance Databrary's back-end data model and front-end interface to allow new coding manuals to be entered directly on the web.
Project staff will need to modify the data model to allow the additional text available in the coding manuals to be associated with specific codes *across* a video and *across* an entire dataset.
These links are crucial because most *coding files* contain single alphanumeric characters.
Thus, in one context 'm' might mean 'mother is speaking' and in another 'm' might mean 'participant is manipulating an object'.
Only by linking richer, text-based descriptions to the specific codes can the search engine return meaningful results to a user who enters 'mother speaking' into a search box.
In this way, if users enter their coding manuals online directly on Databrary, rather than uploading them as separate files, we can further enhance video search.
This project, like Projects 1.1-6 builds on the Apache solr-based search engine already implemented in Databrary.

##### Project 3.3: Design user interfaces for uploading and visualizing coding manual information.

The target coding tools vary in the extent to which they capture and store code definitions.
Datavyu does not store code definition information at all.
CHAT-formatted files employ a structured set of well-defined keywords that describe the content of speech transcripts and other metadata such as the speaker, context, etc., and user-defined codes are usually tagged as comments.
Transana, Mangold Interact, and Noldus Observer XT allow code definition information to be stored within the coding files or in linked files, but there are often size limits on the amount of text that may be inserted into the code description or definition fields.
As a result, researchers who use these tools regularly augment the information about specific codes or coding schemes in external word processing or spreadsheet documents.

For tools that store code-specific definitions in the coding files, the project team will build upon the import functions developed as part of Project 1.
Developing an interface for users to enter code-specific information stored in coding manuals poses a somewhat bigger challenge.
The team has already begun to collect coding manuals from volunteers who responded to our community survey.
We will also consider the viability and utility of creating and encouraging the use of template coding manuals, as we have done for Data Management Plans (https://databrary.org/access/policies/dmp-template.html) and for Video Data Sharing Releases (https://databrary.org/access/policies/release-template.html).

Once code-specific information has been entered into Databrary, we will need to make available interfaces that allow users to view and edit the information.
One interface will need to allow users to view and edit the code definitions in a document-like form similar to a coding manual.
It will be easier to provide users ways to edit information stored in coding manuals than to enable users to edit code definition fields that are part of the data package associated with specific coding files in tools like Transana, Noldus Observer XT, and Mangold.
So, the extent to which users can edit or export information normally contained in these coding files or code templates will depend on the extent to which we are able to read from and write to native (or importable) file formats.

A second type of interface will be needed that allows users who are viewing a particular video in a specific session to view what codes have been applied to what segments of video.
Project 2 describes how we intend to tackle the problem of displaying the *sources* of the codes (coding file type, contributor, etc.).
This interface will likely build upon Databrary's existing video segment tagging feature, but it will have to include the ability to toggle on or off the visibility of individual code definitions, or the visibility of a separate "code definition" panel.
Consistent with other UI components of Databrary and this proposal, we will proceed iteratively in developing and validating these designs, guided by input from the Databrary advisory board, our technical advisory committee, and user feedback.

#### Project 4: Search interface and functionality.

Project 4 will focus on designing, implementing, and verifying the user interface that returns within and across video search results in powerful, flexible, and informative ways.
Project 4 will also focus on building the back-end capacity for Databrary's existing Apache solr-based search engine (see <technical-plan.md>) to return results from within video segments based on the information contained in imported coding files and coding manuals.
Finally, the project will develop both the back-end and user interface components that allow users to use the videos they have found through search.

##### Project 4.1: Design search interface

The PIs and project staff will gather requirements for the search interface.
A functional specification document with wireframes will be developed and circulated for feedback.
Once finalized, the developers will implement the approved design.
The project team will seek input from the TAC (Appendix A) and from the Databrary Advisory Board in designing and implementing the search interface.

##### Project 4.2: Adapt Databrary's search functionality.

Databrary's existing search architecture is based on Apache solr targeting entire datasets as documents.
The system has existing capabilities that enable users to add text based comments or tags to video segments selected by hand using a web-browser.
Thus, Databrary already has the capacity to represent selected segments of video and to link video segments to text-based codes.
Staff will adapt the existing comment/tag functionality to permit tags from imported coding spreadsheets to be added to the text available to the search engine.
This will require extensive modifications to Databrary's back-end data model and search infrastructure to allow returning video segment results.
As described in the technical plan, Co-I and Databrary Systems Architect, Dr. Dylan Simon, has extensive experience developing and deploying databases of the sort required to implement these features.
Simon also has available to him the resources of NYU's Digital Libraries staff through the contributions of Co-I Millman.

##### Project 4.3: Develop mechanisms for extracting and delivering tagged segments of video.

Once the search engine is able to seek specific text linked to particular video segments, the team will need to develop mechanisms for extracting and delivering the tagged segments in the interface designed as part of Project 1.1.
There are several technical challenges to overcome.
Databrary does not store or represent videos as sequences of frames or time segments.
So, if a user searches for the term "infant speech" and the system returns 100 segments with that tag, Databrary will need to determine what information to return to the user -- a small image (thumbnail) of the first frame of the entire video, a thumbnail image of the first frame of the found segment, or something else.
For the interface to return a thumbnail image, Databrary will need to take information about the video and compute the frame or frames that should be returned.
Similarly, if the user interface allows the user to click on thumbnail images and preview video segments or use mouse movements to scrub through the video segments forward and backward in time, the Databrary system may need to compute and re-encode these frames in cases that the entire video cannot be delivered to the user.
Solving these problems in ways that make the interface responsive to users will be critical for making the search capability useful.
Databrary's current timeline and highlights interfaces support video streaming, but the proposed new features will require extensive new work.

### Coordination and Management Plan

#### Leadership and governance

The project will be overseen by the PIs, Gilmore and Adolph, with guidance from the Co-Is, Millman and Simon.
Simon also serves as Technical Director (see <technical-plan.md>).
Gilmore and Adolph currently meet via phone or video conference several times each week to discuss Databrary project-related business matters with the Co-Is and with project staff.
Adolph and Gilmore collaborate on most decisions and regularly seek input from the Co-Is, but as overall Project Director, Adolph has the final say.
The project will be managed by Lisa Steiger, including coordinating and scheduling development tasks, managing developers and other staff, integrating feedback from users and other external reviewers, and coordinating outreach, support, and documentation efforts.
Steiger currently manages the Databrary project as a whole, coordinating staff meetings and other internal decision processes, and reporting progress and getting feedback from the PIs.
These practices will continue under the proposed project.

In addition, the Databrary project as a whole has input from an advisory board.
The board (see Appendix X) consists of experts internal to PSU and NYU and external advisers who bring expertise in data sharing and developmental science.
The Databrary advisory board meets annually to hear project updates and provide guidance about policy and technical matters.

Because of the unique nature of this proposal, we have assembled a technical advisory committee consisting of representatives from the leading video data coding software tools used by the developmental and learning sciences research communities (See Appendix X - <ridr-16-technical-advisory-comm-members.md>).
These advisors have agreed to provide technical assistance to the project staff via email, phone, or video conference for up to 1 hour per month.
The advisors have also agreed to participate in a half-day webinar meeting held annually in each of the three years of the proposed project period.

#### Evaluation and Assessment

We will evaluate progress on the project in several ways.
The PIs will report on progress meeting each of the specific projects, relative to the goals outlined in the timetable (See <technical-plan.md>) in the required annual project report.
Among other metrics, we will report the number of Databrary users who are sharing coding spreadsheets and coding manuals, by coding tool used.
We will also develop measures of data reuse based on download statistics.
The team will send out surveys to Databrary users once a year to solicit feedback about system operations, focusing on new features, and asking users the extent to which the new features change their willingness to share data, the ease of doing so, and the attractiveness of reusing others' data.
With the cooperation of our technical advisory team members, we will explore the possibility of surveying the community of video coding tool users to ask similar questions.
The results of those surveys will be summarized in the annual NSF report and discussed at the annual Databrary advisory board meetings.

#### Future Directions

### Summary

There are multiple barriers that limit the adoption of video data sharing in the developmental and learning sciences.
In only its first few years of operation, Databrary has overcome many of them, but several remain.
The current proposal will enhance the Databrary digital library, making it possible for contributors to upload, store, and share the results of human-generated annotations of video segments along with text-based definitions of the annotation codes.
These data and metadata will make it possible for users to search for specific codes or keywords across videos within a dataset and across videos across the entire library.
No longer will the choice of video coding tool prevent researchers from sharing the burden of coding with their collaborators, nor will differences in tool file formats prevent the insights one lab draws from being shared with the entire community.

#### Intellectual Merit

This project will enhance the Databrary digital library, a "user-friendly large-scale next-generation data resource" that serves a growing community of several hundred developmental and learning scientists across the globe.
The enhancements will add significant value to Databrary's extensive existing library of reusable video data by integrating a previously inaccessible and invaluable set of expertly coded and micro-detailed annotations describing and enriching those videos.
The new sources of data will be made accessible in a variety of formats for reuse by other researchers, allowing researchers to work in the tools with which they are most familiar and are best suited to their research questions and analyses.
Interoperability among codes will enable new multidisciplinary research questions to be asked based on existing, already collected and shared video data.
Finally, by incorporating annotations and code definitions, the enhancements will enable Databrary users to more readily seek, find, and reuse shared video data.

#### Broader Impacts

The proposed enhancements will make datasets shared on Databrary, many of them previously funded by NSF and NIH, more findable, accessible, interoperable, and reusable.
Video and audio recordings are used by researchers in fields across the social and behavioral sciences, so the infrastructure enhancements will have impacts beyond the developmental science community.
The proposed enhancements will make it substantially easier for scientists at institutions with limited resources for research or their students to participate in scientific discourse about human behavior by building on the expensive-to-collect data gathered by others.
The project will make data sharing more appealing, and this should increase the number of researchers who share, the diversity of the data sets they share, the quality of data shared, and the pace of data sharing.
This will improve transparency and boost reproducibility.
Since some dataset metadata and possibly entire datasets will be available for public viewing, we will raise the profile of video-based research and bolster interest in and support for the behavioral sciences among the public at large.