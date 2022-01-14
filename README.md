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

Unfortunately, the decision to not use a CSS file meant that I had no ability to customize the font of the jumbotron. Thankfully, the image I selected still allowed for black font.

Also, I was able to add more information about the project as a few sentences on the page. I experimented a little with the column number before settling on 12 so that the index.html syntax looks like this:

```
  <div class="container-fluid">
      <div class="row">
          <div class="col-md-12">
              <p>
                  Our navels, or belly buttons, plays host to multitudes of bacteria, many which are still undocumented to this day <br><br>
                  The purpose of this project is to determine the types and populations of bacteria is living in our sample population's belly buttons. One day, we hope to find the silver bacteria that can synthesize the taste of beef.<br><br>
                  What micro-organisms are in your belly button? If you're up for some navel-gazing, come take a look here.
              </p>
          </div>
      </div>
  </div>
```

I was also able to add a navigation bar to allow the user to toggle the different charts with this function:

```
function changeChartVisibility(option) {
  var element = document.getElementById(option);
  if (element.style.display === "none") {
    element.style.display = "block";
  }
  else {
    element.style.display = "none";
  }
}
```

With the use of the getElementById method, I can toggle whether the chart is displayed on the page or not.