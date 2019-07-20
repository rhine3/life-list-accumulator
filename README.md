# Life list accumulator

Create an accumulated life list for a group of people. Note that the `.gitignore` for this repository ensures that raw lists will not be uploaded to GitHub, maintaining privacy!

Instructions:
* Clone this repository
* Use `initialize_list.ipynb` to generate a base list of all scientific and English (United States) common names
* Ensure everyone in your group has their eBird "Species name display" preference set to one of the following (https://ebird.org/prefs)
    * "Both"
    * "Scientific name"
    * "Common name" with the English (United States) translation option selected
* Obtain eBird life lists from [this link](https://ebird.org/MyEBird?cmd=list&rtype=custom&r=world&time=life&fmt=csv) while logged into eBird account
* Create two directories, one called `lists_new/` and one called `lists_processed/`
* Place all life list `.csv`s to be processed in the `csv_dir_new` directory
* Run `update_list.ipynb` -- this will process all `.csv`s in `lists_new/` and then move them to `lists_processed/`
* If more people add their lists later, copy them into `lists_new/` and run `update_list.ipynb` again

