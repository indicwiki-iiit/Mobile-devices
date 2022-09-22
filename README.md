# Mobile-devices
Wikipedia articles for the mobile devices domain were created as part of the IndicWiki project at IIIT Hyderabad. The pipeline given in `IndicWiki Manual` was followed.

The `Data` folder contains the Wikidata (for the images) and the final translated dataset used to generate the articles.

The `Notebooks` folder contains some basic Python code used during the process of creating articles.
- 'Data Exploration' is about creating a SweetViz report to visualize the attributes.
- 'Basic translate' and 'Azure translate' give an overview of the translation/transliteration tools used.
- 'Incorporating Wikidata' deals with getting the image files by querying Wikidata.
- 'Numbers Correct' deals with correcting some numbers that were changed in the translation process
- 'Rendering an article' renders an article to check for the correctness of the Jinja2 template. 
- 'Getting XML dump' is used to get the final XML dump which can then be imported.

The `Template` folder contains the initial text template and the final Jinja template used to generate the articles.

The `XML dump` contains the final XML files that were generated.

`Documentation` contains additional information on the files.
