# Bonita Application Directory

This repository aggregates all the development artifacts of the Bonita Application Directory.

## Build 

Run `./mvnw clean verify` in a terminal. The result of the build is a BOS Archive in the `target` folder.

## Application content

* An application descriptor for the Bonita Application Directory (`applications/bonita-application-directory.xml`)
* A layout without menu as a development artifact
* The application directory page development artifact

## Customize the theme

In addition to development pages, you may also customize the default Bonita theme just by creating a new Theme in the Studio.
By the default the Bonita theme is used as starting point, so you just have to update the theme id in the application descriptor with your custom theme id.