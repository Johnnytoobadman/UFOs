# UFOs Challenge

## OVERVIEW

### Dana is a Datajounalist.  She is from a town that has a history of UFO sightings and has a big interest in the subject.  She has a javascript datafile on UFO sightings including details like: dates, cities, states, countries, types of sightings and descriptions.

### The plan for Dana is to build a website that will allow users to filter the data as they like (e.g. by date, city, state, type etc.).  This project is going to use JavaScript which is a front end development language.  It adds functions and customizations to enhance the user experience.  The focus of this project will be to develop dynamic webpages.  These will be built by inserting JavaScript into an HTML page.  We will also incorporate our knowledge of CSS, bootstrap and Chrome Development tools.

### The first step in this project will be to build a table and then add filters to the table that will allow users to refine their search on more than one level.  This webpage will also include an attention grabbing header, an article summary and a brief article description with the goal of presenting an interactive webpage that is also visually appealing.

## RESOURCES

### JavaScript ES6, D3 (library)

### Chrome Developer Tools

### HTML5

### Bootstrap 3

### CSS Stylesheet

### VS Code

### Files

### Index.html

### Static

  CSS
  
      Style.css
      
  Images
  
      nasa.jpg
      
      .png files for analysis
      
  js
  
      app.js
      
      data.js
      
## RESULTS

### THE DYNAMIC WEBPAGE

![__](https://github.com/Johnnytoobadman/UFOs/blob/main/static/images/UFO%20_header_description.png) 
![__](https://github.com/Johnnytoobadman/UFOs/blob/main/static/images/UFOs%20_datatable_filters.png)
*Note: table is truncated to save space*

### FILTERING ON DATE

![__](https://github.com/Johnnytoobadman/UFOs/blob/main/static/images/UFO's_date_sort.png)

### FILTERING ON DATE WITH NO DATA AVAILABLE

![__](https://github.com/Johnnytoobadman/UFOs/blob/main/static/images/UFOs_datatable_no_data.png)

### FILTERING ON STATE

![__](https://github.com/Johnnytoobadman/UFOs/blob/main/static/images/UFOs_statedate_sort.png)

### FILTERING ON SHAPE (TYPE)

![__](https://github.com/Johnnytoobadman/UFOs/blob/main/static/images/UFOs_shape_sort.png)

## SUMMARY

### Overview of the analysis :  The webpage was dynamic and correctly filtered the user input.  The overall appearance was great and the response time was perfect.  The header did grab the users interest with the awesome nasa.jpg image provided.  The JavaScript components successfully searched for the user input and properly filtered the table to return the requested values.

### The process for filtering the data and searching for a specific result was fairly easy as long as you input existing data into the input fields.

### The drawbacks observed with this webpage/filtering function was that it required input in a specific order: dates must not include leading "0's", cities, states, countries and shapes must match exactly, or as in this case "lowercase", and lastly the preloaded data is not blanked out after user input filtering which can give misleading results (e.g. boulder, az).

### Recommendations for improvements include 1) providing a "no data available" result such as when I input a date with no related data and  2) making the user input not case sensitive or exact date specific.  Use the regex commands to accept and correct user input to match the existing data if it is within certain parameters.

end
