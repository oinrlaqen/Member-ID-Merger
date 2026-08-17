## Member-ID-Merger

*This script automates routine Member ID update for our clients.*

**Why it's needed**. Each member in our system holds his member ID which provides access to the healthcare services (e.g. buying drugs or taking doctor's appointment). Various clients and brokers send us their files with IDs which we are suppose to merge manually with what we have in our SQL database and then load the result into the system. This is quite <ins>time consuming operation</ins>, as we have *hundreds of such files with thousands of people* inside of them. 

> Because of the massive workload each member of our team has to do some part of this operation each week.

**What does the script do**. The script automates manual IDs merge for one of our biggest brokers - UMR, who sends us about 61 different files each month (22% of all the files sent us by all the brokers and clients). That said, instead of merging each of the 61 files manually in Google Sheets by each of our team member, this whole procedure is performed by a single person in 1.5 hour once a month.

> [!NOTE]
> **Time w/o script:** 15 min * 61 = 915 min\
> **Time with script:** 80 minutes

**Starting from February 2026 little more than 3000 IDs have already been loaded using this script.**

As a result of implementing a new workflow our team now has the third week of the month completely free from loading IDs

---

**NB.** All the real company names in a script changed as well as all the links are shadowed by the asterisks (*).
