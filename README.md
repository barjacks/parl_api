# Working with the API of Swiss parliament

Swiss parliament offers a real time service on how the representatives of the
Nationalrat vote, this is the equivalent of the House of Representatives in the
US. The API information also contains details on which commissions the
politicians belong to, how old they are, how many children they have, and
much more.

This service [is here](http://ws-old.parlament.ch/) and it is provided by
[Smartvote](http://smartmonitor.ch/).

For this article in the SonntagsZeitung: ["Der Rechtsrutsch war nur ein Rütschlein"](https://github.com/barjacks/parl_api/blob/master/20161225_0_0_6.pdf),
published on December 25 2016. This article shows that parliament isn't leaning as
far right as many predicted after the elections in October 2015.

[This first notebook](https://github.com/barjacks/parl_api/blob/master/Dealing%20with%20the%20Parlament%20API.ipynb) pulls in all the relevant affairs that were discussed and voted on since 2001. The data files only take into consideration votes made of the current term and compares them to the first six sessions of the last term.
[This second notebook](https://github.com/barjacks/parl_api/blob/master/API%2049%20%26%2050.%20Leg%20comp..ipynb) molds and analyses this data.
