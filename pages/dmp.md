---
title: Data Management Plan
layout: about
permalink: /dmp.html
---

# Data Management Plan

DSCI / LIB 350M: Humanities Research Data Management

# Section 1: Project Overview

This collection explores the theme of Goddesses and Animals, featuring art and images from across time and cultures that represent female deities connected to animals in different ways. Some examples include goddesses directly associated with specific animals, such as Bastet, the Egyptian goddess of cats, while others show female deities alongside their patron animals, such as Athena with owls. The collection includes both historical artwork from the periods in which these goddesses were worshipped and more modern Western depictions, illustrating how their representations have evolved over time. We used Google Sheets to store the url of the image and all of the meta data, and then we stored the sheet and images in Google Drive. For the final product we used Collection Builder on GitHub. This collection will be incredibly useful both for scholars and for normal people interested in History, Religious studies, women & gender studies, mythology and art. This data project will illustrate the diversity of belief systems and how women goddesses are portrayed, both in an art form and in what animal people associated these deities with. 

# Section 2: Roles & Responsibilities

Lila spent a majority of the time finding the images online and filling in the metadata by writing the descriptions, subjects, culture, timeline as well as the title and file name. She also searched for the goddesses and wrote accurate descriptions that match the goddesses domains and characteristics. Lila was also in control of downloading the images, organizing them and putting them into the GitHub. She also made the home banner collage and helped code design of the site including fonts and text size.

Jazmine added and filled out the rights statement column and the latitude and longitude column. Jazmine also helped go through the entire metadata to help make it compatible for GitHub. This involved fixing typos, adding more information, making things in the correct format, and checking for any more little mistakes that might have been made in the columns. Jazmine owns the GitHub page, so she was responsible for big edits and decisions with the site. She also helped organize, design, and code the different texts and tabs in the website, including the map and data management. 

# Section 3: Data Inventory & Provenance 

## Source objects

| The Institution | Object(s) | Rights Statement |
| :---- | :---- | :---- |
| The Metropolitan Museum of Art | Artemis, Taweret, Durga, and Sekhmet | CCO 1.0  |
| The Cleveland Museum of Art | Manasa, Heqet, Athena, Mangala, and Ganga | CCO 1.0 |
| The British Museum | Bastet, Gula, Inanna, and Aphrodite | CC BY-NC-SA 4.0 |
| Brooklyn Museum | Hathor | CC BY-NC-SA 4.0 |
| Bernisches Historisches Museum | Artio | CC BY 3.0 |
| Luxembourg National Art & History Museum | Epona | CCO 1.0 |
| Michael C. Carlos Museum | Serket | CC BY-NC-SA 4.0 |
| National Museum of Asian Art | Chang’e and Magu  | CCO 1.0 |
| New Delhi National Museum | Yogini | CC BY 2.0 |
| Wikipedia Commons | Miami Wara | Public Domain |

## File inventory

| File Types | Quantity | Total Volume (MB) |
| :---- | :---- | :---- |
| Images (objects)  | 22 | \~30 MB |
| CSV (data) | 1 | \~ 7 MB |
| Markdown Files (pages) | 11 | \~22 KB |

## Tools and access

We used a spreadsheet software for viewing and editing metadata in Sheets or Excel and a file storage to access project information, which can be a Google Drive folder or a GitHub repository. GitHub, when it's published to a website it's needed to store, track, and share the dataset. The CollectionBuilder would be used to generate and reproduce the site from metadata and an image file. Also, a web browser to revisit the original source info on the institution's websites.

# Section 4: Storage & Stewardship

## During the project

Our project files are stored in both a shared Google Drive folder and a GitHub repository. The Google Drive folder contains our metadata, images, and documents, and both group members have access to it, but the public does not. The GitHub repository stores the CollectionBuilder project files and supports the public website. Both partners have access to the repository, and the site is public and accessible to anyone online.

## After term

After the term ends, we plan to keep the project publicly available through the GitHub repository and GitHub Pages site for as long as possible. Jazmine, as the repository owner, has chosen to keep the repository open to the public. Lila will take primary responsibility for maintaining the project after the term for at least 2 years, and Jazmine will assist when needed. For our group, maintaining the project means keeping the repository available, preserving the files already uploaded, and making small updates as problems arise. If GitHub Pages stops serving the site, the code and the underlying data would still remain available through the GitHub repository unless it is removed.

# Section 5: Access, Reuse & Rights

## Your license

We license our project content under CC BY 4.0. This allows others to share, reuse, and adapt our metadata, writing, and site content as long as they provide attribution. This license applies only to content we created; it does not override the rights attached to third-party images or institutional object records.

## Rights implications of your sources

The rights statement from source institutions affects what users can do with individual objects in the collection. Many were under Creative Commons law however some objects had more restrictive terms. Certain objects we had researched were under Copyright by certain institutions such as objects in the Boston Fine Arts Museum and Asian Art Museum which had ownership of all items in their online collection so required a fee and a submission form in order to use any images. 


## Ethical Considerations

This collection includes cultural and religious materials, so respectful representation matters. In one case, we chose not to use an image because of tribal intellectual property rights. That decision reflects the fact that ethical concerns can matter even when something is visible online.

# Appendix: Data Dictionary

| Field Name | Definition | Example Value | Notes on Use |
| :---- | :---- | :---- | :---- |
| **title** | The title field was constructed to indicate a standardized name of the items and identify them easily  | Painting of Manasa with Snakes | The form of art with the goddess name, followed by her associated animal. |
| **URL** | The url column helps organize links to where the images were initially found. It shows information about the item and its metadata. | https://asia.si.edu/explore-art-culture/collections/search/edanmdm:fsg\_F1909.244a/ | The urls all lead to online collections that contain the downloadable image and information about the item.  |
| **Source**  | The source column was made to organize the institutions and easily which institution each item was from. | The Metropolitan Museum of Art  | The source labels the institution that currently holds the item and the online collection where it was found.  |
| **Description**  | The descriptions give background information and a deeper description of each art piece. | Bastet is the Egyptian goddess of cats, good health, festivity and fertility. This statue depicts her as women with a cats head standing above 4 kittens and holds a sistrum (egyptian rattle for rituals and celebrations)  | The description started with an explanation of the goddesses culture and her domains. It's followed by a description of how each goddess is portrayed and how she is connected to a certain animal. |
| **Location**  | The location is where the items was originally made or uncovered | Egypt  | Found the location on original collection metadata.  |
| **Date** | The data is when in the item was initially made  | \-450 | The data were with the original meta data and we picked the oldest estimated date if it showed eras and not an exact date. We also used a minus sign to indicate whether the item was before common era or common era  |
| **Format** | The format describes what format the image will be saved and transported as. | image/jpeg | All of the images were saved as image/jpeg for clarity sake and to be used on GitHub.  |
| **File name** | The file name describes what file name the image will be saved as  | artemis\_deer  | The name of the goddess and her associated animal, all lowercase and divided by an underscore. |
| **Medium**  | The medium column organizes what each object was created from. | terracotta | The medium lists the raw materials and art mediums that were used to create each art piece. |
| **Creator**  | The creator column organizes the initial creator and artist of the items shown.  | Peter Paul Rubens | Many of the objects' creators are  unknown, however we listed the artist for the item if it was available in the original metadata.  |
| **Subject**  | The subject column organizes and list each of the items subject matter | dog; moon; health; medicine | The subjects were the goddesses' domains and her associated animal. |
| **Object id**  | The object id organizes all of the objects and makes them usable in GitHub. | 8 | Counts down from the top of the sheet  |
| **Rights**  | The rights are list each of the license that each object is under so it is available to be used in this collection  | CC BY-NC-SA 4.0 | The rights are based on what the Creative Commons labeled each license as |
| **Rights Statement**  | This column organizes the link to each of the license creative commons pages.  | https://creativecommons.org/publicdomain/zero/1.0/ | The links all go to a certain page on the Creative Commons website to show the rights to collect this image.  |
| **Latitude and Longitude**  | This column pinpoints each of the objects location on a map  | Lat: 28.394857 Long: 84.124008 | Used [LatLong.net](http://LatLong.net) to find the coordinates of each item's location. Now we are able to see each item on the CollectionBuilder map  |

