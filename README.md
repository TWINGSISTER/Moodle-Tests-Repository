# Moodle Tests Repository
In this repo you will find a collection of activities for Moodle. 

These tests can be used with Moodle installing in your Moodle site the plugin for a modified qtype for Geogebra.

This plugin is contained in  the zip that can be downloaded from 
[here](https://github.com/TWINGSISTER/moodle-qtype_geogebra/archive/refs/heads/twingsisterdev.zip).

In this repository there are files in different formats.

The files in the mbz format can be restored within any Moodle 4.0 site.

The files with the .ggb extension can be used in any Geogebra question either downloading the .ggb file locally and 
dragging it into the quiz or linking the file from GitHub using the URL of the corresponding ggb file in the GitHub pages.

For instance use the URL  e.g. https://twingsister.github.io/Moodle-Tests-Repository/Geogebra/Valin/1_Multilingual/1_Reperage_plan_693x530-FLEN-FR-IT.ggb to use the ggb in the repository file at "/Geogebra/Valin/1_Multilingual/1_Reperage_plan_693x530-FLEN-FR-IT.ggb"  

#Create a .ggb for a quiz
To adapt a GGB activity to this scheme there are some scripts that can help. You can find them in [this repository](https://github.com/TWINGSISTER/GeogebraMultilanguageTranslator). In this repo you can find [three services](https://twingsister.github.io/GeogebraMultilanguageTranslator) that will help to convert your .ggb in an activity similar to those listed here.
#Create a GGB based quiz in Moodle
To create a quiz in Moodle out of a .ggb file in the Geogebra>Valin>series-one>Translations (for instance from https://twingsister.github.io/Moodle-Tests-Repository/Geogebra/Valin/series-one/Translations/Calcul_distance_milieu_T5_719x464REV_Type3-one-FL.ggb) first restore [this mbz](https://twingsister.github.io/Moodle-Tests-Repository/MoodleiQuiz/backup-moodle2-course-14-tobechanger-20230302-1647-nu-nf.mbz) 

This MBZ simply adds a quiz named TENSIXPLUSFOURQUIZ that must be renamed to WHATYOULIKE. Also rename the question bank cathergory "Default for TENSIXPLUSFOURQUIZ" to "Default for WHATYOULIKE"

This new quiz act as a wrapper around the .ggb with most of what need to be set is already in place. You have to add  the URL of the .ggb as explained before and click the button to reload it. Second check that the Seed is set if needed. Third delete all the questions from the quiz and add them again taking a fresh copy from the question bank. 