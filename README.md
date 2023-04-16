# Restaurant-Landing-Page
My Frontend JavaScript Project

<!-- Replace "path/to/folder" with the relative path to your folder -->
<!-- Replace ".png" with the file extension of your images -->
<!-- This assumes that all the images in the folder are of the same type (e.g. png) -->

<!-- Loop through all the images in the folder and add them to the README.md file -->
<!-- The loop generates markdown syntax for each image and concatenates them to a single string -->
<!-- The string is then added to the README.md file -->

<!-- language: lang-none -->

`<!-- markdown -->`
`<p align="center">`
`    <!-- Loop through all the files in the folder -->`
`    <!-- Generate markdown syntax for each image -->`
`    <!-- Concatenate all the markdown syntax into a single string -->`
`    <!-- Add the string to the README.md file -->`
`    `<?php`
`    $folder_path = ""C:\Users\atharva jadhav\OneDrive\Pictures\Screenshots"";`
`    $files = glob($folder_path . "/*.png");`
`    $markdown = "";`
`    foreach($files as $file) {`
`        $markdown .= "![alt text]($file) ";`
`    }`
`    echo $markdown;`
`    ?>`
`</p>`
`<!-- markdown -->`
