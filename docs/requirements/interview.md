# Interview

Simulated interview of questions that could be asked to a client that needs a
URL shortener, used to gather the system requirements

## Questions and answers

* **Q**: What does the current process look like?
  * **A**: We use Bitly, but the cost is getting expensive for the whole team,
  and we don't want to share our data with third parties.
* **Q**: Why does the system need to be built?
  * **A**: To save money and avoid sharing our data with third parties.
* **Q**: What should the users be able to do?
  * **A**: They need to be able to paste a long link, click a button, and get a
  short one. They also must be able to see a list of all the links they've made.
* **Q**: What should the shortened URL track?
  * **A**: Just total clicks with their date and time to see which marketing
  campaign is getting more traction.
* **Q**: Who should be able to delete URLs?
  * **A**: Only the person who created it or an administrator.
* **Q**: Should the URLs expire? What happens when they do?
  * **A**: The user should be able to set an expiration date, with the default
  being one year, but the tracked information should remain for two years after
  the creation of the link.
* **Q**: Who can create links?
  * **A**: Only our staff should be able to create links with their authorized
  accounts, our clients should only be able to click the link and they shouldn't
  be able to make their own accounts without authorization.
* **Q**: Should we shorten links that are already short as well?
  * **A**: We should shorten them as well for the tracking.
* **Q**: How long should the URLs be?
  * **A**: 6 characters long after the slash in the URL.
* **Q**: How many URLs and clicks are we expecting?
  * **A**: We create around 100 links a month, and get around 100,000 clicks
  distributed around those links a month, but most of those clicks go to the 10
  most popular links soon after their creation when the campaign is really successful.
* **Q**: How fast should the system be?
  * **A**: The users should not notice any delay, it should feel instant.
* **Q**: In what hardware will the system run?
  * **A**: A machine running Fedora Linux 43 with 4GB of RAM and 64GB of disk.
* **Q**: Will the machine running the server be running any other program?
  * **A**: No, the machine will be running only the server.
