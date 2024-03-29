# Moodle Tests Repository
In this project you will find a collection of activities for Moodle. Some of them use Geogebra. They are distributed in the MoodleQuiz folder and sub-folders. They are distributed as a backup of a Moodle course i.e. as a .mbz file. The normal way of using this is to restore this course in your Moodle site as a separate course and then import activities into your course. The plugin import to a section that is archived [here](https://web.archive.org/web/20231002132300/https://moodle.org/plugins/download.php/21708/local_importtosection_moodle39_2020061403.zip) is especially useful to control these imports. See [here](https://web.archive.org/web/20231002132946/https://moodle.org/plugins/local_importtosection) for details.

The tests    developed with Geogebra must be used installing in your Moodle site the plugin for a modified qtype for Geogebra.

This plugin is contained in  the zip that can be downloaded from 
[here](https://github.com/TWINGSISTER/moodle-qtype_geogebra/archive/refs/heads/twingsisterdev.zip).

In this repository there are files in different formats.

As explained above, the files in the mbz format can be restored within any Moodle 4.0 site. 
The files with the .ggb extension can be used in any Geogebra question either downloading the .ggb file locally and 
dragging it into the Geogebra quiz or linking the file from GitHub using the URL of the corresponding ggb file in the GitHub pages.
Again, to find an example of tis process, the best option is to  download an .ubz file and see how the quiz in the course were implemented.

# Referencing a .ggb
For instance, use the URL  e.g. https://twingsister.github.io/Moodle-Tests-Repository/Geogebra/Valin/1_Multilingual/1_Reperage_plan_693x530-FLEN-FR-IT.ggb to use the ggb in the repository file at "/Geogebra/Valin/1_Multilingual/1_Reperage_plan_693x530-FLEN-FR-IT.ggb"  
The repository has a copy on Bitbucket so you can use this URL, too,
https://bitbucket.org/twingsister/moodle-tests-repository/raw/master/Geogebra/Valin/snap-one/Translations/Equation_de_droite_T_906x680-one-FLEN-FR-IT.ggb

# Create a .ggb for a quiz
To adapt a GGB activity to this scheme there are some scripts that can help. You can find them in [this repository](https://github.com/TWINGSISTER/GeogebraMultilanguageTranslator). In this repo you can find [three services](https://twingsister.github.io/GeogebraMultilanguageTranslator) that will help to convert your .ggb in an activity similar to those listed here.
# Create a GGB based quiz in Moodle
To create a quiz in Moodle out of a .ggb file in the Geogebra>Valin>series-one>Translations (for instance from https://twingsister.github.io/Moodle-Tests-Repository/Geogebra/Valin/series-one/Translations/Calcul_distance_milieu_T5_719x464REV_Type3-one-FL.ggb) first restore [this mbz](https://twingsister.github.io/Moodle-Tests-Repository/MoodleQuiz/backup-moodle2-course-14-tobechanged-20230722-1115-nf.mbz), 
[alternate download](https://bitbucket.org/twingsister/moodle-tests-repository/raw/master/MoodleQuiz/backup-moodle2-course-14-tobechanged-20230722-1115-nf.mbz). 

This MBZ simply adds two quizzes named TENSIXPLUSFOURQUIZ-TOOL and TENSIXPLUSFOURQUIZ-NOTOOL. 
One has the GGB toolbar visible the other not.
You  can keep both or drop one and  rename  them to WHATYOULIKE. Also you MUST rename the question bank cathergories "Default for TENSIXPLUSFOURQUIZ-[NO]TOOL" to "Default for WHATYOULIKE"

This new quiz act as a wrapper around the .ggb with most of what needed to be set is already in place. You have to add  the URL of the .ggb as explained before and click the button to reload it. Second, check that the Seed is set if needed.
If you run into problems delete all the questions from the quiz (not from the question bank!) and add them again taking a fresh copy from the question bank. 