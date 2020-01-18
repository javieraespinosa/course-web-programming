---
title: Final Project
share: false
---

### Description

As a final project you have to develop a collaborative web based music player where users (i) define the current playlist by proposing songs from a music catalogue and (ii) select the next song on the playlist by "voting".

Your application has to follow a 3-tier architecture (i.e., client, server and database):

-   The **client** must display and manage the user interface (e.g., updating and ordering the playlist).
-   The **server** must manage the database and handle the requests of multiple users (e.g., counting the number of votes and updating the users' interfaces to reflect the votes).
-   The **database** must store the music catalogue composed of songs coming from [Deezer](http://developers.deezer.com/). For instance, each entry on the catalogue may contain:
    -   Artist and song' name
    -   Photo of the artist or group
    -   A preview of the song
    -   The URL of the song (complete version)

### To Do

-   **Server-side**: Develop the CRUD operations (i.e. create, read, update, delete) for managing the music catalogue.
-   **Client-side**: Develop two types of interfaces:
    -   An interface for managing the music catalogue (i.e., add a new song to the catalogue by using the create operation in the server-side).
    -   An interface containing the current playlist. In this interface you have to offer controls (i.e., a menu, a button) for (i) adding a song from your catalogue to your playlist and (ii) voting for a song. Besides, since multiple users can "vote" for selecting the next song, you have to update the number of votes for each song dynamically using asynchronous calls to the server-side.

Your collaborative web based music player has to play songs automatically following the order of the songs in the current playlist (recall that this list is sorted using the numbers of votes of each song).

For developing this function use your CSS knowledge for adding some "rich experience" to the client-side of your web based music player. For instance, every time the music player plays a new song you can fade-in and fade-out the photos of the previous / new song respectively.

**BONUS**

Implement a function for handling personalized playlists. For example, if user X is a registered user, he/she has to be able to define the playlist "Rock" containing his/her favourites rock songs. Personalized lists have to be stored in the database.

### Evaluation and Demo

The project must be developed by groups of 3 people. Each group will be evaluated during a presentation of 20 minutes (including questions). During the presentation you have to describe the main functions of your system, the hypothesis you make and the data representation you used. Besides, you have to realize a "live demo" of your music player. The presentation has to be organized in a way that it shows the participation of every member of the group.

### Example (live)

-   <http://www.christian-schmidt.fr/ltw2/views/playlist.php>