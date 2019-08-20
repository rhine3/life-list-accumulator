# Life list accumulator

Create an accumulated life list for a group of people. Note that the `.gitignore` for this repository ensures that raw lists will not be uploaded to GitHub, maintaining privacy!

Instructions:
* Clone this repository
* Ensure everyone in your group has their eBird "Species name display" preference set to one of the following (https://ebird.org/prefs)
    * "Both"
    * "Scientific name"
    * "Common name" with the English (United States) translation option selected
* Obtain eBird life lists from [this link](https://ebird.org/MyEBird?cmd=list&rtype=custom&r=world&time=life&fmt=csv) while logged into eBird account
* Create two directories, one called `lists_new/` and one called `lists_processed/`
* Place all life list `.csv`s to be processed in the `csv_dir_new` directory
* In `accumulate.ipynb` use the following modes to update your life list:

    * `'new'`: create a new "seen list" from lists in `lists_new/` and move them to `lists_processed/`
    * `'add'`: add to a preexisting "seen list": add lists in  `lists_new/` and move them to `lists_processed/`
    * `'redo'`: redo a preexisting "seen list": recreate with preexisting lists in `lists_processed/` and keep them there
    * `'test'`: create a test "seen list" using the lists in `lists_test/`
