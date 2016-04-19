Final Group Project for the 3 month , 100 hrs Fullstack Coderhouse Course.

The app : an clutter free web calendar app that expose in a single view the next 3 month of activity. Full next 52 w are rendered for easy scrolling. App is online @ http://contcal-lverra.rhcloud.com/ (up to 30 sec of load time, hosted on Openshift, Redhat's PaaS, alternative to heroku) 

Techonoly applied : 
App : Node.Js
Framework : Express.Js @ http://expressjs.com/ ( we used-ish the express generator in order to give some structure but did not made use off the full MVC architecture, for instance views file remain untouched)
DDBB: Mongo.db
FrontEnd: HTML + CSS + Jquery
Additional library used : Moment.Js @ http://momentjs.com/ (adds date intelligence as startoftheweek())
OpenShift free hosting @ https://www.openshift.com/

2 weeks project development with  greggocabral and Pablo 

bugs to correct : Moment.Js Assumes that the start of the week is on Sunday, our application, on Monday. This produce a bug if trying to check your calendar on any given Sunday.

Feel free to use to fork and use the aplication :)
