
![Logo](https://enrichmobile.app/images/logo-footer.png)
# About Us
Enrich mobile was founded in the beginning of 2020 with the aim of creating amazing & useful apps for the global mobile app community. Enrich Mobile has two core values that the company is based on; end to end app development and publishing. Since the start of 2021, the firm is now also focused on investing in promising app projects and startups. With a solid in house development and design team and a solid background in mobile app development, Enrich Mobile is bound to become the next big hit in the global mobile arena.

🔗 Links

[![website](https://img.shields.io/badge/Web_Site-000?style=for-the-badge&logoColor=white)](https://enrichmobile.app//)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/enrichmobile)

# iOS Assignment

The purpose of this assignment is creating an iOS app that will fetch the current pre-design instagram templates and display the templates in a clear User Interface.

We expect you to implement three screens consisting of a subscription screen, along with a listing page and a simple detail page of the listed content. 

You can find sample screenshots for all three screens below, along with the requested ones. You don’t have to implement all the exact details such as; colors, tab bar and etc. 

<b>1. Listing Page </b>

Integration of the menu at the top of the page according to the "section" names in the specified endpoint.

When each menu is tapped, the templates of that menu are listed on the page, as in the example screenshot below.
When the template is selected, it is redirected to the detail page. 

<b>2. Detail Page </b>

Displaying the photo of the selected template on the screen.
If “isFree” is false, the button that directs to subscription screen appears, if it’s true, the button is not displayed. The screenshot is also added. 

<b>3. Subscription Page</b>

Creating the design according to the screenshot,
cross button should close the subscription page. 

## API Reference

#### Get all templates

``http
  GET - storly-dev.herokuapp.com/storly/api/templates
``

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `templateCoverImageUrlString` | `string` | image url |
| `section` | `string` |  categories |
| `isFree` | `boolean` |  paid or not status |




## Screenshots
 <b> Listing Page </b>
 
![App Screenshot](https://media.giphy.com/media/TzJ5b2QiQ32yZdSVqO/giphy.gif)

 <b> Detail Page </b>
<p align="left">
<img src="https://www.linkpicture.com/q/IMG_0138.jpg" width ="300" height="600"/>
</p>


 <b> Subscription Page </b>
<p align="left">
<img src="https://www.linkpicture.com/q/IMG_0137.jpg" width ="300" height="600"/>
</p>





## Feedback

If you have questions, you can ask to us when you want or need to help. If there is a problem, please don't hesitate about contact to fatih@enrichmobile.app
