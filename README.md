Bench Brewing Website 2.0

Step 1 – Install Node.js

Head on over to http://nodejs.org and click install – this should automagically figure out what OS and version.

Step 2 – Install Gulp.js

gulp-2x Open command prompt – (run cmd) then type ‘npm’ – if there is no  error you’ve installed Node.js correctly yay! Otherwise make sure you close and reopen command prompt if it was open during install. Or try rebooting – reinstalling, the usual.

Now type ‘npm install -g gulp’ this will install Gulp.js globally on your system. It will enable you to run the ‘gulp’ command in your command prompt.

Step 3 - Install local Gulp.js

cd bench_2-0/
npm install gulp

Step 4 - Copy the contents of bench2_0/node_overrides over top of bench2_0/node_modules

Overwrite any files in the destination. These are custom node modules you need.

Step 5 - Run local gulp (this will start the server)

gulp