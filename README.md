### GK Merge Context Menu Repo!

Ultimately, our goal with GK is to be as helpful as possible to users without getting in the way. From time to time, we see users bring up, "hey, I want to merge X branch into Y but GK is only giving me the option
to merge Y into X, what gives?". While in some rare cases this most likely is due to a bug, a majority of the time this is intentional behavior for GK. The purpose behind this, we want to help users prevent
merges they don't *actually* want to do. Below are a few cases you can try out in this repo to better understand how the behavior in GK works.

**Branch A & B**:
In this case, GK will offer the ability to Merge A into B or B into A. This is usually determined by how you utilized drag and drop in GK (or whichever branch you have checked out and right click on).
Either way you do it, you can do A --> B or B --> A. These branches both share a common ancestor and contain commits that the other branch does not.