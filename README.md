# Lifesums-Younger-Cousin
*refer back to name
function getRecipeJson() {
var apiKey = "your-api-key-here";
var RecipeID = 196149;
var url = "https://api2.bigoven.com/recipe/" + RecipeID + "?api_key="+apiKey;
$.ajax({
         type: "GET",
         dataType: 'json',
         cache: false,
         url: url,
         success: function (data) {
            alert('success');
            //console.log(data);
            }
         });
       }
    function getRecipeJson() {
        var apiKey = "your-api-key-here";
        var TitleKeyword = "lasagna";
        var url = "https://api2.bigoven.com/recipes?pg=1&rpp=25&title_kw="
                  + TitleKeyword 
                  + "&api_key="+apiKey;
        $.ajax({
            type: "GET",
            dataType: 'json',
            cache: false,
            url: url,
            success: function (data) {
                alert('success');
                //console.log(data);
            }
        });
    }
   {
  "ResultCount": 2829,
  "Results": [
    {
      "RecipeID": 242305,
      "Title": "Lasagna",
      "Cuisine": null,
      "Category": "Main Dish",
      "Subcategory": "Casseroles",
      "Microcategory": "",
      "StarRating": 5,
      "WebURL": "https://www.bigoven.com/recipe/lasagna/242305",
      "ReviewCount": 2,
      "Poster": {
        "UserName": "wurstel",
        "UserID": 1402778,
        "FirstName": null,
        "LastName": null,
        "PhotoUrl": "https://photos.bigoven.com/avatar/photo/wurstel.jpg"
      },
      "IsPrivate": false,
      "Servings": 6,
      "CreationDate": "2012-02-05T06:38:44.000Z",
      "IsRecipeScan": false,
      "IsBookmark": false,
      "TotalTries": 62,
      "PhotoUrl": "https://photos.bigoven.com/recipe/hero/kellys-lasagne.jpg"
    },
    {
      "RecipeID": 630008,
      "Title": "Lasagna",
      "Cuisine": "Italian",
      "Category": "Main Dish",
      "Subcategory": "Pasta",
      "Microcategory": "",
      "StarRating": 4.5,
      "WebURL": "https://www.bigoven.com/recipe/lasagna/630008",
      "ReviewCount": 2,
      "Poster": {
        "UserName": "docsmw",
        "UserID": 2104036,
        "FirstName": null,
        "LastName": null,
        "PhotoUrl": "https://photos.bigoven.com/avatar/photo/avatar-default.png"
      },
      "IsPrivate": false,
      "Servings": 6,
      "CreationDate": "2013-09-07T15:45:58.553Z",
      "IsRecipeScan": false,
      "IsBookmark": false,
      "TotalTries": 58,
      "PhotoUrl": "https://photos.bigoven.com/recipe/hero/lasagna-39.jpg"
    }
  ],
  "SpellSuggest": null
}
{ 
"RecipeID": 530115, 
"Title": "Teriyaki Chicken", 
"Description": "Great basic Chicken Teriyaki recipe. Why use the bottled stuff when the make-it-yourself marinade is easy and so much tastier?", 
"Cuisine": "Japanese", 
"Category": "Main Dish", 
"Subcategory": "Grill and BBQ", 
"Microcategory": null, 
"PrimaryIngredient": "Chicken", 
"StarRating": 4.5714285714285712, 
"WebURL": "https://www.bigoven.com/recipe/teriyaki-chicken/530115", 
"ImageURL": "http://redirect.bigoven.com/pics/rs/640/chicken-teriyaki-10.jpg", 
"ReviewCount": 7, 
"MedalCount": 0, 
"FavoriteCount": 450, 
"Poster": { 
"UserID": 29, 
"UserName": "stevemur", 
"PhotoUrl": "https://photos.bigoven.com/avatar/photo/stevemur.jpg", 
"IsPremium": true, 
"IsKitchenHelper": true, 
"PremiumExpiryDate": "2100-01-01T00:00:00.000Z", 
"MemberSince": "2004-01-19T15:59:00.000Z", 
"IsUsingRecurly": true, 
"FirstName": null, 
"LastName": null 
}, 
"Ingredients": [ 
{ 
"IngredientID": 5247317, 
"DisplayIndex": 0, 
"IsHeading": false, 
"Name": "Soy Sauce", 
"HTMLName": "Soy Sauce", 
"Quantity": 0.333333333333333, 
"DisplayQuantity": "1/3", 
"Unit": "cup", 
"MetricQuantity": 79, 
"MetricDisplayQuantity": "79", 
"MetricUnit": "ml", 
"PreparationNotes": null, 
"IngredientInfo": { 
"Name": "Soy sauce", 
"Department": "Asian", 
"MasterIngredientID": 165, 
"UsuallyOnHand": true 
}, 
"IsLinked": true 
}, 
{ 
"IngredientID": 5247318, 
"DisplayIndex": 1, 
"IsHeading": false, 
"Name": "Dry sherry", 
"HTMLName": "Dry sherry", 
"Quantity": 0.25, 
"DisplayQuantity": "1/4", 
"Unit": "cup", 
"MetricQuantity": 59, 
"MetricDisplayQuantity": "59", 
"MetricUnit": "ml", 
"PreparationNotes": null, 
"IngredientInfo": { 
"Name": "Dry sherry", 
"Department": "Wines", 
"MasterIngredientID": 156, 
"UsuallyOnHand": false 
}, 
"IsLinked": true 
}, 
{ 
"IngredientID": 5247319, 
"DisplayIndex": 2, 
"IsHeading": false, 
"Name": "Vegetable Oil", 
"HTMLName": "Vegetable Oil", 
"Quantity": 0.333333333333333, 
"DisplayQuantity": "1/3", 
"Unit": "cup", 
"MetricQuantity": 79, 
"MetricDisplayQuantity": "79", 
"MetricUnit": "ml", 
"PreparationNotes": null, 
"IngredientInfo": { 
"Name": "Vegetable oil", 
"Department": "Oils", 
"MasterIngredientID": 33, 
"UsuallyOnHand": false 
}, 
"IsLinked": true 
}, 
{ 
"IngredientID": 5247320, 
"DisplayIndex": 3, 
"IsHeading": false, 
"Name": "Brown Sugar", 
"HTMLName": "Brown Sugar", 
"Quantity": 1.5, 
"DisplayQuantity": "1 1/2", 
"Unit": "tablespoons", 
"MetricQuantity": 22, 
"MetricDisplayQuantity": "22", 
"MetricUnit": "ml", 
"PreparationNotes": null, 
"IngredientInfo": { 
"Name": "Brown sugar", 
"Department": "Baking", 
"MasterIngredientID": 124, 
"UsuallyOnHand": false 
}, 
"IsLinked": true 
}, 
{ 
"IngredientID": 5247321, 
"DisplayIndex": 4, 
"IsHeading": false, 
"Name": "Fresh Ginger", 
"HTMLName": "Fresh Ginger", 
"Quantity": 1, 
"DisplayQuantity": "1", 
"Unit": "tablespoon", 
"MetricQuantity": 15, 
"MetricDisplayQuantity": "15", 
"MetricUnit": "ml", 
"PreparationNotes": "grated", 
"IngredientInfo": { 
"Name": "Fresh ginger", 
"Department": "Produce", 
"MasterIngredientID": 365, 
"UsuallyOnHand": false 
}, 
"IsLinked": true 
}, 
{ 
"IngredientID": 5247322, 
"DisplayIndex": 5, 
"IsHeading": false, 
"Name": "boneless chicken breast halves", 
"HTMLName": "boneless chicken breast halves", 
"Quantity": 4, 
"DisplayQuantity": "4", 
"Unit": null, 
"MetricQuantity": 4, 
"MetricDisplayQuantity": "4", 
"MetricUnit": "", 
"PreparationNotes": "trimmed of fat", 
"IngredientInfo": { 
"Name": "Boneless chicken breast halves", 
"Department": "Poultry", 
"MasterIngredientID": 674, 
"UsuallyOnHand": false 
}, 
"IsLinked": true 
}, 
{ 
"IngredientID": 5247323, 
"DisplayIndex": 6, 
"IsHeading": true, 
"Name": "Optional garnish", 
"HTMLName": "", 
"Quantity": 1, 
"DisplayQuantity": null, 
"Unit": null, 
"MetricQuantity": 0, 
"MetricDisplayQuantity": "", 
"MetricUnit": "", 
"PreparationNotes": null, 
"IngredientInfo": null, 
"IsLinked": false 
}, 
{ 
"IngredientID": 5247324, 
"DisplayIndex": 7, 
"IsHeading": false, 
"Name": "Sesame seeds", 
"HTMLName": "Sesame seeds", 
"Quantity": 1, 
"DisplayQuantity": null, 
"Unit": null, 
"MetricQuantity": 0, 
"MetricDisplayQuantity": "", 
"MetricUnit": "", 
"PreparationNotes": null, 
"IngredientInfo": { 
"Name": "Sesame seeds", 
"Department": "Spices", 
"MasterIngredientID": 402, 
"UsuallyOnHand": false 
}, 
"IsLinked": true 
}, 
{ 
"IngredientID": 5247325, 
"DisplayIndex": 8, 
"IsHeading": false, 
"Name": "Scallions", 
"HTMLName": "Scallions", 
"Quantity": 1, 
"DisplayQuantity": null, 
"Unit": null, 
"MetricQuantity": 0, 
"MetricDisplayQuantity": "", 
"MetricUnit": "", 
"PreparationNotes": null, 
"IngredientInfo": { 
"Name": "Scallions", 
"Department": "Produce", 
"MasterIngredientID": 170, 
"UsuallyOnHand": false 
}, 
"IsLinked": true 
} 
], 
"Instructions": "Prepare marinade:\r\n\r\nMix soy sauce, dry sherry, vegetable oil, brown sugar and ginger. Whisk to incorporate. \r\n\r\nAdd to plastic ziptop bag with chicken breasts. Gently press to remove air, and place in a bowl in the fridge for at least 2 hours, up to 6. \r\n\r\nTurn on grill to medium heat. Oil grill. Place chicken breasts on grill, and let cook for 2 minutes. Then turn 90 degrees. Cook for 2 more minutes and flip. Cook for 2 more minutes. Turn 90 degrees. Check for doneness, remove from grill when done. Let rest on cutting board for 2 minutes. Slice on bias and serve atop white rice. Sprinkle with sesame seeds and or grilled scallions to garnish. ", 
"YieldNumber": 4, 
"YieldUnit": "Servings", 
"TotalMinutes": 180, 
"ActiveMinutes": 20, 
"NutritionInfo": { 
"SingularYieldUnit": "1 Serving (466g)", 
"TotalCalories": 528, 
"TotalFat": 23.316175517769967, 
"CaloriesFromFat": 210, 
"TotalFatPct": 0.3108823402369329, 
"SatFat": 3.3890373011313577, 
"SatFatPct": 0.1694518650565679, 
"MonoFat": 14.082038863021811, 
"PolyFat": 4.3831784526794566, 
"TransFat": 1.4619209009373422, 
"Cholesterol": 55.68, 
"CholesterolPct": 0.17132307692307691, 
"Sodium": 18999.911704439732, 
"SodiumPct": 6.5516936911861148, 
"Potassium": 968.83082711414147, 
"PotassiumPct": 0.25495548081951092, 
"TotalCarbs": 38.398373828370659, 
"TotalCarbsPct": 0.11293639361285487, 
"DietaryFiber": 3.080270053353249, 
"DietaryFiberPct": 0.12321080213412997, 
"Sugar": 35.318103775017413, 
"Protein": 39.848609560708425, 
"ProteinPct": 0.56926585086726322 
}, 
"IsPrivate": false, 
"CreationDate": "2013-05-25T13:41:41.000Z", 
"LastModified": "2016-04-28T21:08:19.400Z", 
"IsBookmark": false, 
"BookmarkURL": null, 
"BookmarkSiteLogo": "", 
"BookmarkImageURL": null, 
"IsRecipeScan": null, 
"MenuCount": 7, 
"NotesCount": 4, 
"AdTags": "simplypotatoes15", 
"IngredientsTextBlock": null, 
"AllCategoriesText": "", 
"IsSponsored": false, 
"VariantOfRecipeID": null, 
"Collection": "", 
"CollectionID": null, 
"AdminBoost": 100, 
"VerifiedDateTime": "2013-05-25T18:41:53.000Z", 
"MaxImageSquare": 256, 
"ImageSquares": [ 
256, 
200, 
128, 
120, 
64, 
48, 
36 
], 
"PhotoUrl": "https://photos.bigoven.com/recipe/hero/chicken-teriyaki-10.jpg", 
"VerifiedByClass": "editor" 
}
         
