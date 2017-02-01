# Files for translation of Go Tour in Italian
These repository contains the files translated to [Italian for the Go Tour](https://go-tour-ita.appspot.com).

- _app.yaml_ contains the configuration for the deployment on Google App Engine
- _/content_ contains the translated file for the content of the Tour
- _/static/js_ contains the file javascript with another part translated (for the user interface)
- _/template contains only one HTML template where the only thing to translate is the title

Everytime there's an update in the Tour I just need to get the latest version of the Tour in English and update/override only these files. No need to have the entire Tour on another branch.
