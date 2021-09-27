
# Api-Based-Meal-Finder using core Ingredient

This is my first ever Api based project and it is used to find a meal based on the core ingredient which you have searched for in the search bar. It is a work in progress project I would be adding some or the additional features like locality filter, choice of food filter and many more like that so stay tuned.  
## The Demo of working page

The link to the working page is : https://meal-ingredient-api.netlify.app/

This is the video for the working website: 
![27092021-112137-REC](https://user-images.githubusercontent.com/71783722/134852717-a3e8198d-bff4-4d2f-97d2-dd6a508c26f6.gif)




## Features

- Fetches all sorts of recipe based on the core ingredient searched  
- Contains both Text based recipe and Video link of the recipe
- *Will contain filters related to location and food choices.
- Fully Responsive 



  
## FAQ

#### Languages Used

HTML, CSS AND JAVASCRIPT and basic knowledge of Api fetching



## Authors

- [@Shivam Jha](https://github.com/shivam-jha2712)

  
## API Reference

#### Get Api

```http
  www.themealdb.com/api/json/v1/1/filter.php?i=chicken_breast
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `text` | **search-input**. Id of item to fetch |

#### Takes the ingredient

Takes the core ingredient and returns the reciepe corresponding to it

  