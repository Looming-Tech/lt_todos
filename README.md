# A task to be written using Flutter x Dart OR ReactNative

You have to write the most handsome, beautiful, responsive, well split,
]clean and scalable list of todos there is, using your skills and knowledge of the
Dart/Flutter duo or ReactNative if you feel more like it.

## Getting started

1. Clone this repo, which contains this:
   - lt_todos_flutter (a folder with the default (starter) flutter project with the counter
     (yep, we have all been there));
   - lt_todos_rn_ts (a blank project in ReactNative, using the Typescript template).
     Please note that this project is created, using Expo. If you want to, you can go vanilla RN,
     e.g. get rid of the expo project;
   - This readme file;
   - Two sets of data, namely: data_bg.json and data_en.json
2. Load up the data and start doing your thing.
3. Platform-specific call to action:

- On Flutter: make sure to run `flutter pub get` and `flutter doctor` before you start just to be on the same page.
- On ReactNative: make sure to run `npm install` to get the packages.

## Requirements

As stated earlier, you are required to do a list of todos. This list must display smoothly,
and also must be scalable (e.g. think about a way to display variable number of items without the
app lagging behind). Also, what we would like to see is a feature to make todos urgent and also
(here it is up to you) tabs in the bottom of the screen, which will toggle between urgent
todos and all todos, or a side drawer, which will show paths to reach the "home screen"
with all todos and the "urgent" screen with the urgent todos). Make sure that when you highlight
a todo as urgent, there is an appropriate styling in the general screen, so that the user recalls he
was the one who made it urgent (for example make that item blink, or change its background color,
that sort of thing).
The app is NOT required to meet the specific looks of Android and iOS,
but bonus points will be given if you do so.

## Speaking of bonus points and general criteria

1. General criteria:

- Clean and well structured code: you can go as deep as you want with splitting up the widget
  trees / components and making folders (yes, even if they are for one file). The important
  question that this answers is how quickly will a new developer get acquainted with your codebase
  and understand its structure?
- Make sure you get all the data visible to the user. Descriptions may get lengthy, think about a
  modal popup or a dedicated details screen.
- Way to pass data within the application: think about how to make the app work with its data
  efficiently, and also how to make your life easier down the road. This will answer the question:
  how good do you understand the backbone process of giving data to your widgets?
- Using a theme: pick up your colors and a nice font. Do not let the app look too stock, nor too fancy.
  We would like to see a good amount of theming though. This will answer the question:
  how well do you operate with themes and contexts?
- Responsive design: your solution will be tested (as a bare minimum) on one android phone and one
  IPhone (devices are with different screen sizes). We may use a tablet here and there,
  or rotate the app in landscape mode, so make it look pretty in portrait and get some bonus
  points if it looks good on landscape.
- General code care: make sure your solution has no logs, bugs, errors, lint warnings, crashes and
  so on left over. We love a god clean app, which runs from the get-go. It shows great attention to
  details.

2. Bonus points
   As we mentioned earlier there will be bonus points (because who doesn't like bonus points).
   To get a hold of these you need the following extra milestones:

- Think of a good design in landscape mode;
- Meet the Cupertino and Material looks, so that the app looks as native as it gets on android and iOS;
- Offer us a new feature. An example may be to enable the user to add/edit/delete todos or do a
  localization in BG and EN (use the second JSON named data_bg.json);
- Implement custom logic to make todos urgent. For example look at the created_at timestamp and
  if X number of days have been wasted in procrastination, then go to urgent state automatically.
- Show us your passion about performance and make sure the app is lean, renders as little
  as possible every time, and uses all the performance help it can get;
- Do the interfacing! Do not let your types dangle in open space.
  Make good use of classes/interfaces and have that sweet autocomplete support in place;

3. Most importantly - please do not forget to have fun and write some bomb code. We are ready for it!

## Good luck and happy coding!
