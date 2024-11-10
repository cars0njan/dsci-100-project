> players.csv from github
https://raw.githubusercontent.com/cars0njan/dsci-100-project/refs/heads/main/data/players.csv

> players.csv from GDrive
https://drive.google.com/uc?export=download&id=1Mw9vW0hjTJwRWx0bDXiSpYsO3gKogaPz

> sessions.csv
https://raw.githubusercontent.com/cars0njan/dsci-100-project/refs/heads/main/data/sessions.csv

> sessions.csv from GDrive
https://drive.google.com/uc?export=download&id=14O91N5OlVkvdGxXNJUj5jIsV5RexhzbB

**How to download csv from GDrive**
*example from the book*

```r
url <- "https://someurl"
download.file(url, "data/can_lang.csv")
canlang_data <- read_csv("data/can_lang.csv")
canlang_data
```