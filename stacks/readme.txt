**Stacks** Documentation  
Hypermedia Type Assignment  
Matt Poland  
INLS 490-186 (Shaw)  


**ID attribute values**

* `main`  
Applied to a `div` tag. The main body of the representation which contains all other `div` elements.
* `search`  
Applied to a `div` tag. Contains `form` elements for querying the resources.
* `all-albums`  
Applied to a `div` tag, specifically on the representation of `stacks.html`. Contains the list of all albums in the representation.
* `add-album`  
Applied to a `div` tag, specifically on the representation of `stacks.html`. Contains the `form` element for creating a new album resource.
* `"x"` (Allmusic Album ID number)  
Applied to a `ul` tag. Contains the numerical value of the Allmusic Album ID number for a given album in the stacks.
* `"x"` (Track number - numerical value)  
Applied to a `span` element if `class="track"`. The value for the track number of a track on a given album.

**Class attribute values**

* `album`  
Applied to a `div` tag. Contains all the information pertaining to an album in a given representation.
* `album-name`  
Applied to a `span` tag. Contains the name of the album being represented that corresponds to the Allmusic Album ID number, and thus the URI of the resource.
* `artist-name`  
Applied to a `span` tag. Contains the name of the album that corresponds to the Allmusic Album ID number.
* `x` (Allmusic Album ID number)  
Applied to a `ul` tag. Contains the numerical value of the Allmusic Album ID number which corresponds to the resource's URI.
* `album-id`  
Applied to a `span` tag. Contains the numerical value of the Allmusic Album ID number of the album being represented.
* `year`  
Applied to a `span` tag. Contains the numerical value of the year in which the album being represented was originally released.
* `ep|lp`  
Applied to a `span` tag. Conveys the type of album the album being represented is: EP (extended play) or LP (long play).
* `genre`  
Applied to a `span` tag. Contains information about the genre of the album being represented. A given representation may have more than one `genre` tag.
* `similar`  
Applied to a `div` tag. Contains information about other album resources that are similar to the album being represented and links to those resources. A given representation may have more than one `similar` tag.
* `tracklist`  
Applied to a `div` tag. A component of the `album div`, the `tracklist div` contains all track listing for the album being represented.
* `track`  
Applied to a `span` tag. A component of the `tracklist div` that contains information about and a link to a track on the album being represented.

**Name attribute values**

* `album-id`  
Applied to an `input` tag within a `form` element. Specifies that the value being entered in should be of the `album-id` class.
* `artist-id`   
Applied to an `input` tag within a `form` element. Specifies that the value being entered in should be of the `artist-id` class.

**Rel attribute values**

* `search`  
Applied to an `a` tag. A reference to the search representation.
* `album`  
Applied to an `a` tag. A reference to an album representation.
* `similar`  
Applied to an `a` tag. A reference to a representation of albums similar to a given album representation. Usually within the `span class="similar"`.
* `track`  
Applied to an `a` tag. A reference to a representation of an album track.

