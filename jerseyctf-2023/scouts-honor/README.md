# scouts-honor

## Description
* I lost one of my favorite journals from my childhood and I was hoping to use the time machines to go get a fresh copy. Sadly, I cannot remember when it came out. All I remember are some great
jokes, heroic stories, and a red car that was 4 feet and a couple inches long. I also remember a great joke from someone about a pretty heavy dinosaur that I could not stop laughing at.
Could you find out the ISSN number and the first name of who sent the joke?
* Remember to use underscores instead of spaces. Example: jctf{ISSN_1234-5678_FirstName}

## Solution Steps
* If you picked up on the title of this challenge you can tell there are some descriptions of Scouts BSA magazine called Scout Life. From there it is somewhat straight forward from there.
* From the search bar you can search up __wayback__ and click the one that shows all past editions of the magazine from 1911-2012. https://scoutlife.org/wayback/
* Click any of the links, as it will not matter which decade you choose.
* Once you do there navigate to the search bar that is above a button called *Search all issues*. Click this.
* Click the search bar and type "4 feet 2 inches", including the quotation marks.
* Navigate until you see a July 2011 issue.
* Scroll down to page 52 to find the joke about a dinosaur. Once you do, note the person first name - Kaleb.
* To find the ISSN, click *About this magazine* on the left hand side of your screen.
* You will see the ISSN in about the middle of the page. *Note you must keep the dash in this instance for the flag to be correct*
* Flag: `jctf{ISSN_0006-8608_Kaleb}`
