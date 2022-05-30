# Initial wireframe designs for the project

- Wireframes for the poject were created on figma which can be seen [here](https://www.figma.com/file/5e6R25CXvVxV54Rz4OZPDe/Hiking-in-depth?node-id=7%3A262)
- Google material design 3 was used as a basis for the design.
- Design has taken a mobile first approach which will be later adapted to larger screen size devices.
- The goal is to make the project a progressive web app

## Landing page
The user will arrive at the landing page which didplays a search bar or a hikes nearby buttion. Those are the two paths the user can take.

![Landing Page](https://user-images.githubusercontent.com/100104319/171060368-b673db6a-fd1a-4423-9535-b74f16bee26c.jpg)

## Hikes Nearby Path
This will follow the user journey on the hikes nearby path

### Location permissions pop-up
Pop-up informs the user that location permissions is required. If this is declined then the user should be sent back to the landing page.

![Location permissions](https://user-images.githubusercontent.com/100104319/171060449-152b7f3e-18e5-4436-b32a-e411b2e4018c.jpg)

### Results List
Show small cards of X amount of nearby hikes. Will not be infinite scrolling, but perhaps should 15 nearby hikes. Above the results are various filters than can be applied to find hikes more suitable for the user. When a filter is applied it should filter from the database, not just the 15 results.

![Hike List](https://user-images.githubusercontent.com/100104319/171060473-b779a475-c1d1-4eee-88f2-963827297e67.jpg)

### Result Detail View
When a small card is clicked it expands to show more details about the hike. If the solid button clicked it takes the user to the detailed hike page

![Hike List Open](https://user-images.githubusercontent.com/100104319/171060485-bbec5c0e-ec90-46eb-889d-23279c2342f2.jpg)

### Hike page view
The user sees a larger photo of the hike, icons which represent various attributes of the hike and then a detailed written description of the hike.

![Hike page 1](https://user-images.githubusercontent.com/100104319/171060518-389c9251-7ae7-442e-bbe9-6852d0777410.jpg)

By scrolling down on the page the use can find a map of the hike and links to additional resources like articles, videos and podcast about the hike.

![Hike page 2](https://user-images.githubusercontent.com/100104319/171060526-07269c37-6484-48fa-a56f-ef3cc8f27db5.jpg)
