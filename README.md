# BookListing Application
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Development

A native Android app using Java for writing code.

**Installing**

- Fork the repository

- Clone the repository using the terminal command.Make sure you replace `username` with your github username

```
git clone https://github.com/username/BookList.git
```
**Setting up the Android Project**

1.Download the BookList project source. You can do this either by forking and cloning the repository (recommended if you plan on pushing changes) or by downloading it as a ZIP file and extracting it.

2.Open Android Studio, you will see a Welcome to Android window. Under Quick Start, select Import Project (Eclipse ADT, Gradle, etc.)

3.Navigate to the directory where you saved the BookList project, select the root folder of the project (the folder named "BookList"), and hit OK. Android Studio should now begin building the project with Gradle

4.Once this process is complete and Android Studio opens, check the Console for any build errors.

- Note: If you receive a Gradle sync error titled, "failed to find ...", you should click on the link below the error message (if available) that says Install missing platform(s) and sync project and allow Android studio to fetch you what is missing.

5.Once all build errors have been resolved, you should be all set to build the app and test it.

6.To Build the app, go to Build>Make Project (or alternatively press the Make Project icon in the toolbar).

7.If the app was built successfully, you can test it by running it on either a real device or an emulated one by going to Run>Run 'app' or pressing the Run icon in the toolbar.

**Libraries used in this project**

Retrofit [Docs](http://square.github.io/retrofit/2.x/retrofit/)

GSON Converter [Docs](https://github.com/square/retrofit/tree/master/retrofit-converters/gson/)

CardView [Docs](https://developer.android.com/guide/topics/ui/layout/cardview)

RecyclerView [Docs](https://developer.android.com/guide/topics/ui/layout/recyclerview)

Glide [Docs](https://github.com/bumptech/glide)

**API Used**

Google Books [Docs](https://developers.google.com/books/docs/v1/getting_started)

# Screenshots
<table border="0">
  <tr>
    <td><img src="https://user-images.githubusercontent.com/40353347/84052823-b566ed00-a9ce-11ea-834b-c24a9a38f527.jpg" width="300"></td>
      <td><img src="https://user-images.githubusercontent.com/40353347/84052820-b39d2980-a9ce-11ea-981b-b72330f34bdd.jpg" width="300"></td>
    <td><img src="https://user-images.githubusercontent.com/40353347/84052816-b13acf80-a9ce-11ea-8457-a617b655f372.jpg" width="300"></td>
  </tr>
</table>

# Build On

- Android Studio

- Ubuntu 18.04
