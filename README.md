# us-license-plates
A database of all 8,331* license plates available in the U.S. (50 states + D.C.) as of June / July 2023. This should be considered a snapshot, as license plate offerings change frequently.

This data goes with the story [All of the 8,291 License Plates in America](https://www.beautifulpublicdata.com/all-of-the-license-plates-in-the-united-states/), published by Jon Keegan at Beautiful Public Data. 

**Update Sept. 28, 2023: This story's dataset was updated to include Illinois' [military plates](https://www.ilsos.gov/departments/vehicles/license_plate_guide/military/home.html ) which were omitted in error.*  

## Data Dictionary
<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: left;">
      <th>Column</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
     <tr>
      <td><strong>state</strong></td>
      <td>State postal code abbreviation.</td>
    </tr>
     <tr>
      <td><strong>plate_title</strong></td>
      <td>The title of the plate collected from the agency website. </td>
    </tr>
 <tr>
      <td><strong>plate_img</strong></td>
      <td>The filename of the local plate image file.</td>
    </tr>
     <tr>
      <td><strong>source_img</strong></td>
      <td>The plate image online at the time of collection.</td>
    </tr>
    <tr>
      <td><strong>source</strong></td>
      <td>The page that contains the plate listing.</td>
    </tr>
    
  </tbody>
</table>


## Data

**[us-license-plates.csv](https://github.com/jonkeegan/us-license-plates/blob/main/us-license-plates.csv)**
*1.6MB. 8,344 rows. First row is the header.*

You will find the license plate images in */plates* with subdirectories named with the postal abbreviation for each state (and D.C.).

Send questions to [beautifulpublicdata@gmail.com](mailto://beautifulpublicdata@gmail.com)