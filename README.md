Dashboard for SES/SNS notifications
===================

Simple app to receive notifications from Amazon SES through Amazon SNS and save into database(PostgreSQL). Includes dashboard to see list of all notifications.

### Features ###
 - Go 1.6
 - PostgreSQL 9.5
 - React 0.14.7
 - Npm 2.14.2
 - Gulp 3.9.1

### Download Dependencies ###
     go get -v github.com/beetrack/aws-ses-sns-dashboard

### Build App ###
     go build

### Execute App ###
    ./aws-ses-sns-dashboard

### Background processes ###
     nohup ./aws-ses-sns-dashboard &
