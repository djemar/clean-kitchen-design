# Milestone 3: Wireframe and Heuristic Evaluation - Clean Kitchen

## Wireframe

| Wireframe PDF | [link](res/Wireframe_M3.pdf) |
|:----:|:----:|

The wireframe was built using [Balsamiq Cloud](https://balsamiq.cloud/).
Working on this wireframe we kept in mind the issues and cons emerged from the outcome of M2 during the analysis and the selection of the prototype.
We integrated a Welcome Tutorial and made sure that the user had a familiar way of interacting with the app using standard and well-known actions (buttons), instead of the novelty represented by the use of the proximity sensor and voice recognition.
We addressed the lack of some UI elements, such as back/exit buttons to guarantee a non-disruptive navigation through the app.

We focused mainly on what we thought were the most important part of the application (main features, multimodal interaction, navigation) and less on the content (e.g. the Welcome Tutorial is currently generic since we’re waiting to see how the implementation of the features plays out).

- Page 1, 2: Welcome Tutorial - Tutorial showing how to use the app.
- Page 3: Home - The user can search a recipe by keyword or selecting a category (&#8594; page 5); he can also choose a recipe among the ones suggested (&#8594; page 6). A menu is also accessible anytime from the app bar (&#8594; page 4).
- Page 4: Show Menu - The user can change some settings (not implemented, e.g. language) or look again at the tutorial.
- Page 5: Search Results - Landing page after a search (either by keyword or category); the user can search for something else or select a recipe (&#8594; page 6)
- Page 6, 7: Recipe Overview - (The two pages are the same, used as a workaround to fix “back” navigation) The user can read an overview of the recipe and start the “Cooking Mode” when ready (&#8594; page 8).
- Page 8: Cooking Mode Tutorial Dialog - A quick reminder on how to use the app (&#8594; page 9).
- Page 9, 11: Cooking Mode - The user can use multimodal interaction to navigate through the steps (swipe on the proximity sensor to activate the voice recognition process, touch buttons at the bottom).  
- Page 10: Voice Recognition - Workaround to portray the use of voice recognition after being activated by swiping on the proximity sensor.

## Heuristic Evaluation

The facilitator briefly explained the scope and the main features of the app before letting the evaluators free to explore and examine the wireframe. There were no task prepared for the evaluators, since we believed that the navigation was pretty simple and linear.

The evaluators were given a shared spreadsheet based on the suggested template (linked below) as a way to write down and communicate their findings.

The facilitator was always available to give support and answer questions, the main ones regarding the multimodal interaction (see picture below): since it was difficult to portray the interaction with physical sensors (proximity sensor and microphone), we left most of it to the facilitator to explain.
We believed that portraying the multimodal interaction, even if using a workaround, was important to convey our vision for this project.

<img src="res/screenshot.png" width="700" alt="Screenshot from the evaluation"/>

The observer noted that both the evaluators were confident during the navigation of the app, with only some concerns about the previously stated multimodal interaction screen, and the lack of content.

The evaluation was carried out by the Wallet Manager team, and their results are available on the spreadsheet at this [link](<https://docs.google.com/spreadsheets/d/1-rPi7WNKPGi0WxXWe9Yaszs-QMVgsihDdqkUHmvLkBU/edit?usp=sharing>). The evaluators, after expressing their own comments separatly, performed the joint evaluation by commenting each other findings and averaging their ratings.

This is the joint evaluation we received from them:

|Issue #|Heuristic #|Description                                                                                                                                                                                                                                                        |Joint Evaluation|
|-------|-----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
|1      |H1         |Not clear in which status of the app I am. It misses a title/subtitle describing which task can do the page that I'm using. E.g. : After clicking the search button a subtitle "Searching" can help the user.                                                      |1.5             |
|2      |H1         |Not clear what I'm searching for. In ALL the application there is not the word "Recipe" so only expert users know what they are doing.                                                                                                                             |3.5             |
|3      |H2         |In the real world many details are related to the concept of recipe (for how many people, price of the recipe, vegan, vegetarian ect...). All these details are not present in the application and the recipe can result incomplete.                               |2.5             |
|4      |H7         |The three dots menù it's superfluous since it contains just two voices and one of them ("Help") it's used just at the beginning of user experience. For a better user navigation could be better to have two differents buttons (one for settings and one for Help)|0.5             |
|5      |H3         |The user can not have a list of preferred recipes or a list of most liked ingredients etc.., so is difficult to save some recipe and to find that again                                                                                                            |2.5             |
|6      |H4         |The Icon before "Popular" it's not coherent with the concept of popularity. The icon with the fire means "most liked", the word Popular means "most viewed". How a recipe is defined pupolar?                                                                      |1               |
|7      |H7         |If I start to follow a recipe and I want to see at a glance the list of ingredients I have to exit from the recipe and go back to the general view. Moreover, if I exit to the recipe when I reopen it I'm forced to restart from step 1.                          |2.5             |
|8      |H8         |The main page is too much full of contents and may annoy                                                                                                                                                                                                           |1               |
|9      |NH         |The wireframe is missing most of the elements and is difficult to evaluate other things                                                                                                                                                                            |4               |


### Potential Changes

After discussing the evaluation results, we didn’t find any major (non-trivial) issue that needs to be addressed, except maybe issue #2 from the table (this one will be addressed). We believe a lot of them can be blamed on our misunderstanding regarding the amount of content to put in a wireframe.
We share some of the observations they made (#3 and #7, #9, see table above) and we're going to address them:

- We'll add all the missing information related to the recipes.
- We’ll make sure to add all the important information needed by the user to be sure that the chosen recipe suits them.
- We’ll ensure that the user will have all the necessary pieces of information during each step of the recipe to avoid the need of going back to check something (ingredients, doses etc.).

Regarding issue #5, we acknowledge it is a nice feature to have, but we didn’t have any plan to include any feature linked with the ability for a user to have a personal account. However, having received that input, we will consider adding this feature.

Lastly, regarding issue #8, we don't consider the home page to be that cluttered: this observation may arise by the visual design of the wireframe (thick black lines and boxes). Hovewer, we may consider removing the search bar and moving it inside the appbar as a button, to make the home page breathe a bit more.
