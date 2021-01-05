# Crowd Monitoring App
Two crowd monitoring apps for the Singapore Airlines AppChallenge 2020, emerging as 1st Runner-ups amongst over 120 participating teams. The apps allow users to be updated on the number of people in another location to know how crowded the place is. One of the app aims to facilitate better pre-planning by the general public while the other helps to notify cleaning staff to clean areas that have been frequented by many.

## Implementation
A local video device (e.g. CCTV) detects and counts the number of people in a location using OpenCV. This count is sent to Firebase which captures the realtime occupancy levels of the area. If the number of people who has been to that area exceeds a certain number, the device also updates Firebase on the need to notify cleaning staff to clean the area. The app made using Flutter retrieves the data from Firebase to display the number of people in the area, and to also notify cleaning staff to clean frequently visited spaces.

To understand more about our crowd monitoring app, head to our slides and video demo folder [here](/Slides%20and%20Video%20Demo).

Slides can also be found here: https://docs.google.com/presentation/d/1zPtZc8nUv7hzd0bPExb2_4jbpMvU9Y6ZpV32kBFPudg/edit#slide=id.g91343fe343_0_2035
