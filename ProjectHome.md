This app makes use of the Voting component in the App Inventor for Android environment. The app is a client app and works together with a web service which is available at   http://androvote.appspot.com.

The web service is used to create, start, close, repeat or delete polls.
A poll has a question and 2 to 5 answer options. If a poll is open, the client app retrieves a ballot, the user chooses an option and submits the vote. The web service collects and tallies all received votes and can also show the results in a pie chart.

**Problems with the web service**

  * It can run only one poll at a time.
  * Sometimes, even if a poll is open, the phone gets the message "No open poll". In these cases, one needs to reload the HTML page.

The source to install the app are on the 'Downloads' page.
