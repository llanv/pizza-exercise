# pizza-exercise

Created by Lan Vy Thach

HTML Deployment: [GitHub Pages](https://llanv.github.io/pizza-exercise/)

Prototype: [Figma Prototype](https://www.figma.com/proto/3au5J5V5s3yxLhDNZrBCQx/Digital-Wireframe-Pizza-Management?node-id=51-585&t=2UfEMdo8eijeOAe2-1)

Figma: [User Flows](https://www.figma.com/design/3au5J5V5s3yxLhDNZrBCQx/Digital-Wireframe-Pizza-Management?node-id=265-2075) | [Paper & Digital Wireframes](https://www.figma.com/design/3au5J5V5s3yxLhDNZrBCQx/Digital-Wireframe-Pizza-Management?node-id=0-1) | [Low-Fidelity-Prototype](https://www.figma.com/design/3au5J5V5s3yxLhDNZrBCQx/Digital-Wireframe-Pizza-Management?node-id=34-1246) | [Hi-Fidelity-Prototype](https://www.figma.com/design/3au5J5V5s3yxLhDNZrBCQx/Digital-Wireframe-Pizza-Management?node-id=51-585)


## Research and Insights

### Users

Pizza Owner (Alex)
- Will most likely not be using the website as often, since ingredients don't tend to change often.
-  Tech savviness: moderate
- Wants to be able to use the website as fast as possible due to how busy restaurant operations can get.
- Busy with other actions, need to prevent duplicating toppings.
- Needs to be able to differentiate visually between each topping.
- Find it hard to keep track of different types of topping.

Chef (John)
- Most likely to be the main one to use the website, because making new pizzas is more common than adding new ingredients.
- Tech savviness: low
- Wants to be able to categorize and find pizzas fast due to busy restaurant schedule.
- Tend to be forgetful, need to prevent duplicating pizzas.
- Want his personal photos of the pizzas to be displayed.
- Wants to easily create and visualize pizzas with various toppings.

### Research
Researched existing pizza store websites:
- Got an idea of various types of pizzas to fill design.
- Found common ingredient types to fill design.
- Found that photo card layout was commonly used.
- Pizza has distinct color, each websites commonly used red to match.

Researched e-commerce admin dashboards:
- Got an idea of the functionality of how the website might behave.
- Clear separation of different types of items (pizza/toppings).
- Found ways to manage existing items (filtering/search).
- Being able to add new items and manage existing items in one place.

### Insight
- Need to keep actions minimalistic and easy to learn because users are not as tech savvy.
- Need to keep actions quick due to busy restaurant operations.
- Color decisions made to compliment pizza images:
	- Blue as primary: Extremely highlighted because it contrasts with all the red on the page from images.
	- Red as secondary: Needed to appeal to the contents on the page (pizzas)
	- Green as tertiary: Green looks healthy and matches toppings on pizzas.
- Pizza index as homepage because the chef will be accessing it more than the pizza owner.
- To differentiate different pizzas and toppings, use images in pizza/topping index as cards.
- Made searching for pizzas easy by using a filter and a search bar.
- Allow custom user filtering by allowing users to create their own categories and set them on items.
- Keep design minimal with less clutter on screen.

## Documentation
- Modal was used because it minimizes distractions and disruptions during item management workflow (searching, filtering, viewing different items, deletion).
- Filtering and search interface was used because it keeps the users workflow and actions on the same page.
- Two separate locations for add buttons to make it convenient depending on where the user is on the page (they might be really far down on the page, or at the very beginning of the page).
- Content of pizza cards are title and image.
	- Image comes first because users need to be able see the contents of pizzas and the name doesn't clearly describe the pizza.
- Pizza form layout is name > image> toppings> categories because operation of importance.
	- Name is first because it's a title.
	- Image is second because user need to see the pizza visually.
	- Toppings is immediately after because user want to describe the toppings on the pizzas in a distinct way.
- The layout for the forms are similar on both pizza and topping index to reduce confusion and minimize learning curve.
- Delete action was placed directly on cards for easy access after search and filter.
- Cut required learning by:
	- Making pizza and topping index similar.
	- Making pizza and topping forms similar.
	- Navigation bar layout mimics common website designs.
	- Filter and search interface mimics common website designs.
	- Used common icons:
		- Trash can for deletion.
		- Filter icon to filter.
- Kept design minimal by implementing a switch that acts as a page title and navigation.
- Made sure the search and filter interface was easy to locate and simple to use.
	- Easy to locate because its on top of the filterable items.
	- Simple to use because the design is minimal and users immediately understand  that this is how we sort/search/filter items.
- Duplicates are prevented with an error message and a red border around the name input when name has been already taken.
