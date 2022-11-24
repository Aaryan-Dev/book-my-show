### Use, mobile no. - "123456789" to signup

https://user-images.githubusercontent.com/118374868/202278756-53fcc560-9ecf-4066-9f34-dac64b1d67fa.mp4

# FigmaLinks




## [WEBSITE](https://www.figma.com/file/5Uxe9m0u0DDc9MC9Ev9dW5/Aman_Singh-227?node-id=0%3A1&t=YZk14oY85NotUEZ0-0)

## [book-my-show_GIFT-CARD](https://www.figma.com/file/13S5b4ZUCdkbfdA5wgFtg2/Untitled?node-id=0%3A1&t=Q5zbb5HW2I4kgv7W-0)

# bookmyshow

Project to clone bookmyshow

## [Demo](https://cutt.ly/gMQ3GQU)

## Clone of [Bookmyshow](https://in.bookmyshow.com/)

Main website

```
https://in.bookmyshow.com/
```

BookMyShow website is basically for entertainment purpose, In this app, a user can book movie tickets by choosing the different theatres and timings accordingly. The user also can see some events happening around them and can attend the events.

## Using the app

### Technologies used

In this project, a few technologies and packages were used, listed below

FRONTEND

1. React
2. Redux-thunks
3. Redux
4. CSS
5. Axios
6. react-router-dom
7. Material UI
8. antd
9. React multi carousel

BACKEND

1. Express
2. Mongoose
3. Bcrypt
4. JWT

### Install the packages

After cloning this repo do

```
npm install
```

And

```
npm install redux react-redux redux-thunk axios react-router-dom material-ui/@core @material-ui/icons @material-ui/lab antd react-multi-carousel
```

## For database

All josn files are in the scraped data folder

```
Database Name - bookmyshow
Collections Name - movies , foods ,laughters , latests , outdoors ,populars,cinemas
To import --
it will help you to do same collectios put all json file in same folder
and change the path accordingly while importing.
mongoimport --db bookmyshow --collection movies --file F:\data\bookMyshow.json --jsonArray
mongoimport --db bookmyshow --collection foods --file F:\data\food.json --jsonArray
mongoimport --db bookmyshow --collection laughters --file F:\data\laughter.json --jsonArray
mongoimport --db bookmyshow --collection latests --file F:\data\latest_plays.json --jsonArray
mongoimport --db bookmyshow --collection outdoors --file F:\data\outdoor_events.json --jsonArray
mongoimport --db bookmyshow --collection populars --file F:\data\popular_events.json --jsonArray
mongoimport --db bookmyshow --collection cinemas --file F:\data\cinemas.json --jsonArray
To fetch Date:
http://localhost:8000/movies
http://localhost:8000/outdoor
http://localhost:8000/food
http://localhost:8000/laughter
http://localhost:8000/cinema
http://localhost:8000/latest
http://localhost:8000/popular
```

To start the server you can do

```
npm run server
```

## Functionalities associated with this app

1. A user can visit the home page and can see the Movies, Events, Fun activities etc.
2. user can view all the movies by clicking on see all button on the right, there they can also filter the movies according to Language, Genre and Screen type.
3. User would be able to see more details about the movie by clicking any movie.
4. They can rate the movie and can book that particular movie by clicking the Book tickets button.
5. For login user can use mobile number

```
123456789
```

6. The user will be redirected to the page where they can select the Theater followed by their region.
7. After selecting Theater, the user can choose the seating.
8. Now, the user can click on the play button and can see the preview of their selection. Also, they can add some food and snacks.
9. After clicking, Proceed button, the user can make the payment and will be redirected to the home page.
10. At the end, user can see their booking details in the booking history from the profile.

## Some of the snaps from the app

### Home page

![Home page](https://github.com/arshadalitalwar/bookmyshow/blob/main/bookmyshow-app/public/website_images/home_page.JPG)

### See all page

![See all page](https://github.com/arshadalitalwar/bookmyshow/blob/main/bookmyshow-app/public/website_images/seel_all.JPG)

### Movie page

![Movie page](https://github.com/arshadalitalwar/bookmyshow/blob/main/bookmyshow-app/public/website_images/movie_page.JPG)

### Seating page

![Seating page](https://github.com/arshadalitalwar/bookmyshow/blob/main/bookmyshow-app/public/website_images/seeting.JPG)

I want to take this opportunity to thank you for visiting here.
