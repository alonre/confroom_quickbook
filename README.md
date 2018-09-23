# confroom_quickbook
Quickly book/release conference rooms (GApps/Google Calendar)    
This is a static single-page app meant to be served from AWS S3.

# Features
- Authorizes GApps user
- Lists available conference rooms
- Quickbook a room for 30 minutes starting NOW (variable timeframe coming soon)
- View my currently booked rooms
- Release a booked room (removes the room from the calendar event)

# Aligning Expectations
This was built in a day. This code looks like crap.

# Getting Started
1. This code was built on the Google Calendar API quickstart: https://developers.google.com/calendar/quickstart/js
Read through it and understand it and you're good to go.
2. This code uses "Material Design Lite": https://getmdl.io/started/index.html
And specifically based on this template: https://getmdl.io/templates/text-only/index.html
3. Finally, it is served from an AWS S3 bucket: https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html
4. Bonus: How to setup a record in Route 53 to point to your S3 bucket: https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/RoutingToS3Bucket.html
Example: https://docs.aws.amazon.com/AmazonS3/latest/dev/website-hosting-custom-domain-walkthrough.html
