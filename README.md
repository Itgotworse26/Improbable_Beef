# Improbable_Beef
Practice and Challenge Assignment for Module 12

## Backgound
Roza has a partially completed dashboard that she needs to finish. She has a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.

## Link
In order to access the site, please use this [URL](https://itgotworse26.github.io/Improbable_Beef/).


## Commentary
The most difficulty I had was adjusting the image on the jumbotron without using a CSS file. For Roza's project, I decided to mix things up and not use a CSS file. This meant writing syntax for the jumbotron inside the index.html file. This meant having to figure out the different syntax to adjust the side of the image that would be used for the jumbotron. In the end, I used this line of code to create the jumbotron background:

```
    .jumbotron {
        background-image: url("static/images/jumbotron.jpg");
        background-repeat: no-repeat;
        background-size: 100% 100%;
```

It allowed me to keep the image centered and fill the jumbotron. 