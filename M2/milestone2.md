# Milestone 2: Low-Fi Prototyping - Clean Kitchen

## Storyboards

<img src="res/story.png" width="800"/>

### <!--- blank line -->

| 1 | 2 | 3 |
|:--:|:---:|:---:|
|**4**|**5**|**6**|
|**7**|**8**|**9**|

The storyboard illustrate a typical situation that can happen in a kitchen.

The user wants to cook a new recipe and he encounters some issues during the process. The first problem is about changing the page of the recipe while he’s cooking and he has dirty hands.
The second one is about asking for help in case he has any kind of doubt about the description of the recipe.

The strength is that the user's needs while he’s cooking are easily understandable and this helps the reader to empathize with the user.
The only weakness could be about understanding how the application will help the user when he needs help (figure 6-7), due to the fact that we thought about different kinds of implementations and we didn’t want to specify one.

## Paper Prototypes

These prototypes tackle the project in two different ways, starting by the type of sensors used to satisfy the user need of having an hygienic workspace, but also differing in the core functionalities and flow of the app.

### Paper Prototype #1

| 1 | 2  | 3  | 4  | 5  | 6  |
:--:|:--:|:--:|:--:|:--:|:--:|
<img src="res/proto1-1.png" width="200"/>|<img src="res/proto1-2.png" width="200"/>|<img src="res/proto1-3.png" width="200"/>|<img src="res/proto1-4.png" width="200"/>|<img src="res/proto1-5.png" width="200"/>|<img src="res/proto1-6.png" width="200"/>

<table>
  <tr>
    <td width="227">Welcome Tutorial Screen 1</td>
    <td width="227">Welcome Tutorial Screen 2</td>
    <td width="227">Main user screen with the overview of his/her recipes</td>
    <td width="227">An example of recipe screen with the details of the recipe and a timer to set</td>
    <td width="227">Subsequent screen of the recipe example</td>
    <td width="227">The "social" screen composed of user's registered friends, a search bar to search for them, a button to invite them</td>
  </tr>
</table>

#### Flow

<img src="res/flow1.jpg" width="500"/>

#### Description

CleanKitchen enables people to cook using their saved favourite recipes or their friends’ ones, all without touching the screen, by using the proximity sensor to navigate through the various steps.

## <!--- blank line -->

### Paper Prototype #2

| 1 | 2  | 3  | 4  | 5  |
:--:|:--:|:--:|:--:|:--:|
<img src="res/proto2-1.png" width="200"/>|<img src="res/proto2-2.png" width="200"/>|<img src="res/proto2-3.png" width="200"/>|<img src="res/proto2-4.png" width="200"/>|<img src="res/proto2-5.png" width="200"/>|

<table>
  <tr>
    <td width="227">Home page with search functionalites (by keyword and filters) and suggested content</td>
    <td width="227">Search results page with results and filter options</td>
    <td width="227">Chosen recipe overview, with button to enter in "cooking mode"</td>
    <td width="227">Tutorial popup showing how to use the app functionalities</td>
    <td width="227">"Cooking mode" screen with voice recognition enabled</td>
  </tr>
</table>

#### Flow

<img src="res/flow2.jpg" width="500"/>

#### Description

This prototype is focused on the possibility to use a voice recognition system that, by saying a keyword, enables the user to navigate the various steps of the recipe and to ask for help if needed. Thus, as presented in the project description and in the storyboard, giving the user the ability to keep an high level of hygiene by not requiring him to touch his phone during the cooking process (see panels 3-4 from the storyboard), while also giving an option to receive some help if needed (see panels 6-7 from the storyboard).
The UI includes a menu where the user can check again the tutorial and access the app settings (hypotetically e.g. language selection).

## Selection Rationale

### Prototype #1 Pros and Cons

#### Pros

- Welcome Tutorial: it is useful to introduce the users to the app functionalities from the beginning
- Ability to set a timer: the user doesn't have to switch to another app to start it
- Ability to use touch while cooking, not just the sensor: the user has multiple way to interact with the app

#### Cons

- Missing search feature: basic and fundamental feature for this kind of app, so that the user can easily search the database of recipes
- Tutorial visible only at the start of the app: user may find useful to be reminded of how to use the app, since the app uses non-conventional ways of interaction
- No way to exit the "cooking mode"
- Sensor may be easy to trigger involuntarily

### Prototype #2 Pros and Cons

#### Pros

- Search feature: basic and fundamental feature for this kind of app, so that the user can easily search the database of recipes
- Smaller and more clear recipe steps when in "cooking mode": it is a friendlier way to present information to the user
- Tutorial reminder before entering in "cooking mode": user may find useful to be reminded of how to use the app, since the app uses non-conventional ways of interaction
- System status is clear to the user while in "cooking mode":
    - An icon signals when the voice recognition is active and listening to queries
    - The progress is clearly visible at the bottom

#### Cons

- Missing a Welcome Tutorial: it is useful to introduce the users to the app functionalities from the beginning
- No way to exit the "cooking mode"
- Missing an alternative way to interact while in "cooking mode". The UI is missing buttons for next/previous/exit actions.
- Missing some text descriptions on the home page
- Sensor may catch unwanted queries if the system is always listening

### Selection

We decide to choose the Prototype #2 as a base to continue our exploration because it is the one with the most features we think we need for our app and we find its UI/UX (see Pros and Cons) a better starting point. However, the Prototype #1 includes some interesting features that we're going to merge to the base:

- The two sensors may work better together to accomplish our goal of interacting with the app without being forced to use the touchscreen. (e.g. we can use the proximity sensor to trigger the start of the voice recognition process).
- The Welcome Tutorial is necessary to explain to the user how our app works from the beginning.
- The user should still be able to use the touchscreen while in "cooking mode". The UI is missing buttons for next/previous/exit actions.
