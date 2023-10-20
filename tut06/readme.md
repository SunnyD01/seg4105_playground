

## October 10, 2023 4:00 - 5:00 PM

### Participants

Michael Bosciglio, Chetan Mandur, Marco Vethanayagam, Hong Yue Wang

### Purpose
Betting table to select a pitch to work on

### Topics discussed
- Went over everyone's pitches
- Decided our main criteria was to have enough work for each teammate.
- We did not choose Chetan's Raspberry Pi pitch since we realized in retrospect that it is not ideal to have all 4 programmers work on a single piece of hardware. Chetan is the only one who has experience with the Raspberry Pi on our team and it would make sense for him to work on it alone.
The same reason we did not pick Michael's pitch on updating the profiles page: we realized it was not enough work for 4 people over 6 weeks.
- We didn't choose Marco's 3D Modelling Pitch as the scope of what it intended to achieve did not meet with the time allocation provided. With a 4-member team working for an uninterrupted 6-weeks, the process of producing said feature would be done too quickly, making it an unviable pitch for the current cycle. This could be something we tackle as a personal ticket rather than a pitch.
- As a result of The Betting Table, the winning pitch was Hong Yue's Electron Desktop App. The main reason for this is because its scope and what it attempts to solve are important for our project and viable within the allocated time. The limitation of solely using a web application is that connection to the hardware is less secure and efficient. There also is no capability to create a desktop overlay for profile switching with a web app; this was one of the client's requirements and can only achieved with the solution identified in this pitch. Furthermore, the scope of the solution can be achieved within the 6-week allocation for our team size, furthering the importance of this pitch.
- Dennis Choose his own pitch
- Updated pitch from [Hong Yue's Github](https://github.com/hongyuewang/seg4105_playground/tree/main/lab03) which can be found [here](https://github.com/Macomatic/T40-Mouse-Accessibility-Attachment/blob/main/SEG4106_Deliverables/Deliverable_2/pitch.md)
## October 12, 2023 4:30 - 5:00 PM

### Participants

Michael Bosciglio, Chetan Mandur, Marco Vethanayagam, Hong Yue Wang

### Purpose
Work cycle kick-off meeting

### Topics discussed
- Confirm that we will be working on Electron prototype for the next cycle
- Discuss selected pitch
- Separate work amongst teammates based on their expertise and previous work done on web app
- Post kick-off message## Betting Table Notes

### Note
I am not a part of the capstone team, therefore, it is difficult for me to comment on the rabbit holes and no gos listed in each pitch. I am only able to comment on the general structure and not the valididty of the content

### Chetan

- Problem
    - Is something that needs to be done for the final product
    - Need to cnnect to the application to the web
- Appetite
    - 6 week time frame is longer than needed
    - Important for the UX of the application
    - Allows for some testing after the feature is implemented
- Solution
    - Has proof of what APIs can be used to connect the device and application
    - Simplifies the code base and keeps it all connected
- Rabbit Holes
    - Try to avoid APIs that may change or harm our software in the future
    - Do research for the correct API to avoid a refactor
- No Gos
    - No comment


### Michael
- Problem
  - Makes sense as it is a key feature of our product
  - Seems more like a bug ticket from the description
- Appetite
  - The indicated time frame doesn't make sense for the problem
  - Definitely can be done with less time; usually, 6 weeks time is uninterrupted and bugs are handled later but interruptions/bug fixes can happen
  - Hard to split with a team of 4
- Solution
  - Seems to only tackle the frontend aspect
  - Swapping and saving also dealt with backend and endpoint integration
  - Is it really a solution that needs a 6-week, uninterrupted cycle to implement?
- Rabbit Holes
  - Don't include other parts of the front-end features
- No Gos
  - No comment

### Marco

- Problem
  - There is no current way for the product to be mounted to a mouse
- Appetite
  - States that this would take 6 weeks seems reasonable 
  - Hardware only feature
- Solution
  - Create a housing and attachment for the Pico Pi using a PLA case
- Rabbit Holes
  - PLA should be good enough
  - Avoid anything permanent to keep it modular
- No Gos
  - Avoid new inputs and Raspberry Pi boards


### Hong Yue

- Problem
  - Important issue that needs to be solved
  - Need an application that can be downloaded to connect directly to the device firmware
  - Web app is missing key functionality that can be solved with a desktop app
- Appetite
  - Recreate the web-app in 6 weeks within a desktop application
  - Should be enough for multiple team members
- Solution
  - Electron will be used for importing the web app code into the desktop app
  - Implemented with Javascript and Typescript
  - Can be used on Windows, macOS, and Linux
- Rabbit Holes
  - Use Typescript as it will be easier to import (same as web app)
  - Keep the same UI and UX as the web app 
- No Gos
  - No new pages


### Dennis (Separate Project)

- Problem
  - Making a game more complex with a heirarchy of attacks and defences.
  - Create priority between attacks and statuses
- Appetite
  - Takes 6 weeks since I am solo, would not be enough work for multiple developers
- Solution
  - Create a class that takes in all information for each unit
  - Save priorities and statuses
- Rabbit Holes
  - N/A
- No Gos
  - Do not update the actual effects and attacks, just the classes.


## The Bet
- We did not choose my pitch as I am not a part of their capstone group. I did present my pitch to them regardless

- I choose my pitch since I win by default

- We did not choose Michaels pitch because the time allocated for the feature would not make sense if we are going to implement it as a team of 4. The feature is mandatory for the application to function but having 4 people is too many

- We did not choose Marco's pitch because the 3D modeling would be hard to separate into work  This is something that needs to be implemnted as a ticket but should be done by one person who is the most knowledgable about 3D modeling and design.

- We did not choose Chetan's pitch because having all four of our developers to work on a hardware solution would limit the progress on the web and desktop application. It would not make sense to stall software development instead of working on both concurently

- The winner of the Betting table was Hong Yue's pitch (Electron Desktop App). This pitch was not only important but allows the workflow to be split well between the differant group members


### The Kick-Off
![image](https://github.com/MichaelBosciglio/seg4105_playground/assets/55165965/acc126a2-110c-478c-82db-aa0e57a0b858)