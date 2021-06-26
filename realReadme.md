# USE NODE.JS v10.24.1
test website by: gatsby develop
create public files by: gatsby build

notes:
banners for events are found in src/images
to add broadcasting, put them in: content/jsons/nshgb.json
just follow the previous formatting
To change the activities within a year, go to content/jsons/Activities.json, then add the event, then add the images at src/images/activities/jong, with {year}-{activity_name} as file name
add jong image here: src/images/activities/jong/0

# How to do things

## Change website banner
in `src/components/Hero/CarouselNews.js`, there is a `const CarouselNews = props => {` \
within the `const images` and `const text`, you can change the image and text
images are located in `src/images/png`, with arabic names

## Change image below view more
in `src/pages/index.js`, there is a graphql code, within that file, search `20gb`, that should be the name of the image

## Add events to timetree
in `content/jsons/timetree.json`



