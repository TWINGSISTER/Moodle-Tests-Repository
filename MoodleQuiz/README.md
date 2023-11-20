# Moodle Tests Cartridges
In this folder you will find a collection of activities for Moodle. Some of them use Geogebra. 
They are distributed in the MoodleQuiz folder and sub-folders. They are distributed as a backup of a Moodle course i.e. as a .mbz file.
The normal way of using this is to restore this course in your Moodle site as a separate course and then import activities into your course. The plugin import to a section that is archived [here](https://web.archive.org/web/20231002132300/https://moodle.org/plugins/download.php/21708/local_importtosection_moodle39_2020061403.zip) is especially useful to control these imports. See [here](https://web.archive.org/web/20231002132946/https://moodle.org/plugins/local_importtosection) for details.

The most of the tests are  developed using Geogebra and must be used installing in your Moodle site the plugin for a modified qtype for Geogebra.
This plugin is contained in  the zip that can be downloaded from 
[here](https://github.com/TWINGSISTER/moodle-qtype_geogeobra/archive/refs/heads/twingsisterdev.zip).

Once that this plugin is installed you can devise your own  tests. Sample pattern empty tests are availble in this  
[download](https://bitbucket.org/twingsister/moodle-tests-repository/raw/master/MoodleQuiz/backup-moodle2-course-14-tobechanged-20230722-1115-nf.mbz). 

list of the available cartridges is:
 1. Empty cartridge with pattern tests for both XML import and Geogebra tests.[(download)](https://bitbucket.org/twingsister/moodle-tests-repository/raw/master/MoodleQuiz/backup-moodle2-course-14-tobechanged-20230722-1115-nf.mbz)
    - Three types of tests for GGB are proposed. The first  two are two versions of a 6+4 scheme. One version is with GGB toolbar the other without. 
      - The first six questions are the same across the class so you can have all the audience aligned upon the same test. 
      - The remaining four are the same upon every entry but are different for each student. 
      - One attempt is foreseen and the results comes out when the test is closed. You have to set the closure date. By default is set to 2050
      - The third GGB  pattern is without GGB toolbar and is totally random. 
All students receive ten different tests and these tests change upon re-entering the quiz. After the test the solution is immediately visible so it is suitable for individual challenge with unlimited attempts and best mark assignment.
      - The other two pattern questions are for import XML tests.One attempt is foreseen and the results comes out when the test is closed. You have to set the closure date. By default is set to 2050
 1. A cartridge for the cartesian plane 
 [(download)](https://bitbucket.org/twingsister/moodle-tests-repository/raw/master/MoodleQuiz/backup-moodle2-course-12-cartesianplane-20231120-1703-nu.mbz). 
    - GGB Exercises are without toolbar and with possible review only after assignment closure (set to 2050 by default) 
    - tests follows a 6+4 scheme: first six questions are the same across the class so you can have all the audience aligned upon the same test. The remaining four are the same upon every entry but are different for each student. 
      - One attempt is foreseen
    - Exercises for understanding coordinates, distance between two points, midpiont, vectors and their operations, line equation, loci equation (segment axis and angle bisector).