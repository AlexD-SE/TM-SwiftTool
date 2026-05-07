# TM-SwiftTool
MacOS app that ensures a Mac is ready for deployment by checking multiple parts of the computer from software 
installed to hard drive and battery health. 

I created this application during my time as a full-time student and part-time IT technician at Rochester Institute of 
Technology. It was used by myself and fellow employees to verify any managed Mac was ready to be deployed to a user.

## Features
Info View
- Displays hostname, processor architecture type, MacOS version, storage size, and Mac model

Senior Review
- Verifies battery health to ensure it's above or equal to 75%
- Verifies the health of the drive by checking it's SMART status
- Verifies it's connected to the correct wifi network
- Verifies the latest software is installed in Jamf
- Verifies the correct set of apps are installed
- Launches FaceTime briefly to allow the user to verify the camera is working

Add User View
- Quickly add new managed and properly configured user by providing their username

## Authors
Alexander Demerjian (alexander.demerjian@outlook.com)

## License
Copyright (c) 2023 Alexander Demerjian.
