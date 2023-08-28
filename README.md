<h1>RapidFort Offline Project</h1>
<a name="website"></a>

- #### website : https://adresterr.github.io/anjan-rapidfort-front-end/ 
- #### backend-end repo : https://github.com/ADresteRR/rapidfort-back-end

## Overview
This project is a simple HTML website that allows the user to upload a file and make an API call to a server. The website will display the result of the API call in a table below the input field. The table will be responsive and scrollable, and the input field and the footer will always stay at the top and bottom of the screen, respectively.
API call returns basic information related to the file that is being uploaded

<h2>How it works</h2>
The website consists of three files: index.html, style.css and script.js. The index.html file contains the basic structure of the website, which includes a container div element, a file input element, a footer element, and links to the style.css and script.js files. The style.css file contains the styling rules for the website, such as the colors, fonts, sizes, positions, and layouts of the elements. The script.js file contains the logic for the website, such as creating a FormData object from the selected file, sending a fetch request to the API endpoint, parsing the JSON response, creating a table from the JSON object, and appending the table to the container div element.

<h2>How to use it</h2>

<p> you can open the https://adresterr.github.io/anjan-rapidfort-front-end/ . You will see a file input element at the top of the screen, where you can choose a file from your device. After you select a file, the website will automatically send a request to the API endpoint with the file as a form data parameter. The website will then display the result of the API call in a table below the input field. The table will have one row for each key-value pair in the JSON object returned by the API. If the value is another JSON object, it will create a nested table inside the cell. If the value is longer than 250 characters, it will truncate it and add an ellipsis at the end. You can scroll up and down inside the container div element to see more rows of the table. You will also see a footer element at the bottom of the screen, where you can add any information or links you want.</p>
