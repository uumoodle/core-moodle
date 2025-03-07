Utrecht University Edits:

This is a local fork for Utrecht University of the main moodle repository.
We have made 2 local modifications to the code.

1. To fix too strict sandbox settings in tinymce editor.

https://github.com/uumoodle/core-moodle/commit/001aa4193cd669162d7aa836c89708cc397890e1

Internal issue https://utrechtuniversity.atlassian.net/browse/MDL-1134

2. To fix broken file serving when filenames contain space

https://github.com/uumoodle/core-moodle/commit/25de687a23203063457941d2a8858f40cb001a44

This commit is to fix https://tracker.moodle.org/browse/MDL-81604

It is based on the pull request by Tim Schroeder, which had not yet been merged into core moodle

****************************************************************************************************************************

                                 .-..-.
   _____                         | || |
  /____/-.---_  .---.  .---.  .-.| || | .---.
  | |  _   _  |/  _  \/  _  \/  _  || |/  __ \
  * | | | | | || |_| || |_| || |_| || || |___/
    |_| |_| |_|\_____/\_____/\_____||_|\_____)

Moodle - the world's open source learning platform

Moodle <https://moodle.org> is a learning platform designed to provide
educators, administrators and learners with a single robust, secure and
integrated system to create personalised learning environments.

You can download Moodle <https://download.moodle.org> and run it on your own
web server, ask one of our Moodle Partners <https://moodle.com/partners/> to
assist you, or have a MoodleCloud site <https://moodle.com/cloud/> set up for
you.

Moodle is widely used around the world by universities, schools, companies and
all manner of organisations and individuals.

Moodle is provided freely as open source software, under the GNU General Public
License <https://moodledev.io/general/license>.

Moodle is written in PHP and JavaScript and uses an SQL database for storing
the data.

See <https://docs.moodle.org> for details of Moodle's many features.
