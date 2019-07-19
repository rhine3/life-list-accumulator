# Life list accumulator

Create an accumulated life list for a group of people.

Instructions:
* Clone this repository
* Run `initialize_list.ipynb`
* Create two directories, one called `lists_new/` and one called `lists_processed/`
* Have everyone in your group log into eBird, then download their life list by going to [(https://ebird.org/MyEBird?cmd=list&rtype=custom&r=world&time=life&fmt=csv)](https://ebird.org/MyEBird?cmd=list&rtype=custom&r=world&time=life&fmt=csv)
* Put all your .csvs into `lists_new/`
* Run `update_list.ipynb` -- this will process all `.csv`s in `lists_new/` and then move them to `lists_processed/`
* If more people add their lists later, you can run `update_list.ipynb` again

Note that the `.gitignore` for this repository ensures that raw lists will not be uploaded to GitHub, maintaining privacy!
