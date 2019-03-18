# Layer Names
When fetching recipe content, the selected text layers must be named according to the Spoonacular API response fields, *case sensitive.* Here's a listing of common and not-so-common recipe fields.

### Common fields
|Layer name           |Description                                  |
|:--------------------|:--------------------------------------------|
|`title`              |Title of the recipe                          |
|`instructions`       |Full text of recipe preparation instructions |
|`extendedIngredients`|Collected list of recipe ingredients         |
|`creditText`         |Name of recipe source                        |
|`sourceUrl`          |URL of recipe source                         |
|`image`              |URL of image                                 |
|`servings`           |Number of servings                           |
|`readyInMinutes`     |Time required for recipe                     |

### Not-so-common fields
|Layer name           |Description                                  |
|:--------------------|:--------------------------------------------|
|~~`dishTypes`~~          |WIP                                   |
|~~`diets`~~          |WIP                                   |
|~~`occasions`~~          |WIP                                   |
|`vegetarian`         |true/false                                   |
|`vegan`              |true/false                                   |
|`glutenFree`         |true/false                                   |
|`dairyFree`          |true/false                                   |
|`veryHealthy`        |true/false                                   |
|`cheap`              |true/false                                   |
|`veryPopular`        |true/false                                   |
|`sustainable`        |true/false                                   |
|`lowFodmap`          |true/false                                   |
|`ketogenic`          |true/false                                   |
|`whole30`            |true/false                                   |
|`weightWatcherSmartPoints`|Weight Watcher points                   |
|`pricePerServing`    |Usually ridiculously wrong                   |
|`gaps`               |"yes"/"no"                                   |
|`healthScore`        |3                                            |
|`id`                 |Spoonacular recipe ID                        |

