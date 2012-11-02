This application is a mini video ingest. It offers capability to consult the video library, and to ingest additional videos using an XML file containing the metadata.
It comes prepopulated with a couple of videos.


== Installation ==

	1. Unzip performTask.zip
	2. Run perform.bat or perform.sh to launch the application

== Command line usage ==

>list
Displays all videos in the system

>add
>video_1.xml
Ingests a video, where video_1.xml needs to be in the videofiles folder (currently under /classes/).
Key words in xml file are interpreted as categories.

>report summary
Displays  summary video report.

>report type
>FRUIT_MATCH
Displays report for particular video type (available types :FRUIT_MATCH/VEGETABLE_MATCH/DRINK_MATCH)


== Improvement list ==

-Increase level of cohesion and abstraction.
-Set up maven profiles with properties files and resource filtering.
-Create specialized sub projects and api maven projects.
-Consider different database data source configuration.
-Set up jpa 2.0 and apply criteria api and entities events.
-Write some unit tests (currently only integration tests).
-Create test profiles.
-Consider dependency libraries versions upgrade an java version upgrade.
-Add “dbunit” or other library for test fixtures loading.
-Create some diagnostic logs and context appenders.
-Create custom exceptions hierarchy and better exception handling mechanism.


