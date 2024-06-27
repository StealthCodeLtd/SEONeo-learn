# SEONeo-learn
This repo is for the module **Learn SEO NEO**

# Basic JSON structure
<br/>
`{<br/>
**"fundamentals"**: <br/>
 &emsp;  &emsp; {<br/>
    &emsp; "id": 0,<br/>
    &emsp; "playlistHeader": "SEO NEO Fundamentals",<br/>
    &emsp; "playlistSubHeader": "This video series is tailored for beginners, focusing on the crucial terms and concepts of SEO Neo.",<br/>
    &emsp; "playlistData": <br/>
    &emsp;  &emsp; &emsp; [<br/>
    &emsp; {<br/>
        &emsp;  &emsp; "title": "Accounts & Account Buckets",<br/>
        &emsp;  &emsp; "description": "Learn the basic about Accounts and Account Buckets",<br/>
        &emsp;  &emsp; "thumbnail": "https://i.imgur.com/TsXYMfM.jpg",<br/>
        &emsp;  &emsp; "duration": 3,<br/>
        &emsp;  &emsp; "videoURL": "https://www.youtube.com/embed/E-rS94B5_MM?si=LDJyUhRV0S8hEZmZ"<br/>
    &emsp; },<br/>
    &emsp; {<br/>
        &emsp;  &emsp; "title": "Account Templates",<br/>
        &emsp;  &emsp; "description": "Learn the basic about Account Templates",<br/>
        &emsp;  &emsp; "thumbnail": "https://i.imgur.com/k0dBHlX.jpg",<br/>
        &emsp;  &emsp; "duration": 3,<br/>
        &emsp;  &emsp; "videoURL": "https://www.youtube.com/embed/q-Yxap82F5U?si=6StSGyvC5MWlRrvS"<br/>
    &emsp; },<br/>
    &emsp; {<br/>
        &emsp;  &emsp; "title": "Content Buckets",<br/>
        &emsp;  &emsp; "description": "Learn the basic about Content Buckets",<br/>
        &emsp;  &emsp; "thumbnail": "https://i.imgur.com/Nn1sZsZ.png",<br/>
        &emsp;  &emsp; "duration": 4,<br/>
        &emsp;  &emsp; "videoURL": "https://www.youtube.com/embed/t1bJeJR3Wpg?si=vjJWU1dnfJhuwP2J"<br/>
    &emsp; }<br/>
    &emsp;  &emsp; &emsp;  ]<br/>
  &emsp;  &emsp; }<br/>
}<br/>

# JSON's fields
1) **'fundamentals'** is the name of the playlist that is used in the coding part of the formating in SEO NEO to distinguish the playlists.

 2) (**Each playlist must have:**)
   - **id**: This is a number that is used for optimazation purposes. Begins from 0 and ascends.
   - **playlistHeader** : This is the string that will be displayed in the UI as the Header of the playlist.
   - **playlistSubHeader** : This is the string that will be displayed in the UI as the one line description below the Header.
     ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/1925aac6-0720-431a-9a00-f526735f5e4b)
   - **playlistData** : This is the list of videos that each playlist must have. If the videos are more than 4 the UI will automatically make a <br/>*Show more* button. Each video must have:
     ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/1941ec43-ae64-48f6-b8c2-fbb90e5cec2b)
     -  **title** : The title that will be displayed in each card <br/>
     ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/73019c6b-eae3-437b-bce5-71d1018de43c)
     -  **description** : The description that will be displayed. If the description is more than **70 characters** ellipsis will be applied and a tutorial to show the whole description on Hover  <br/>
     ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/9f34f1a1-0ac9-46c5-861c-bf987681f2c5)
     -  **thumbnail** : The customized thumbnail that will be displayed in the Card <br/>
        <br/> **1) Search imgur add image. If you are logged in you will land on the following page <br/>** ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/594422ba-3f4b-405f-9016-3ff1a8f95ffd)
        <br/> **2) Then go to your profile's photos *NEVER CLICK ON GRAB LINK, IT IS THE WRONG ONE* <br/>** ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/b9521f50-68bb-4387-81f0-1aa6dcc7be62)
        <br/> **3) Find the image you uploaded and click on it<br/>** ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/8d25fdc3-fd97-4de6-a37c-d6212b06a781)
        <br/> **4) Then copy the *DIRECT LINK* | NEVER COPY THE IMAGE LINK, IT IS THE WRONG ONE <br/>** ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/7ec660db-e14f-4e02-abf9-4d86bd7aa24c)
     -  **duration** :The duration of the video. Usually if a video is 3.20 mins the duration should be the number 3 <br/>
     ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/1f8cb798-72a6-4335-92f3-cce9dc8757ad)
     -  **videoURL** :The video that will be displayed when the user clicks one of the Cards. When adding one you need to got to the video and do the following <br/>
        <br/> **1) Pick the video you want and go to share<br/>** ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/6bbbe5a3-e487-4cfb-883a-cbf228fdadf6)
        <br/> **2) Then click the Embed icon<br/>** ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/3337b33c-cf41-4506-b4a8-47679fae2317)
        <br/> **3) And copy the embed link from the iframe<br/>** ![image](https://github.com/StealthCodeLtd/SEONeo-learn/assets/72436770/ba9b7a5d-20cf-4575-831f-2d9a0a207eb6)




