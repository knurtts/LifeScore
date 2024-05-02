# LifeScore

A glorified achievements app for life

- Start the app with `npx expo start`
- See expo docs for more info: docs.expo.dev

## Features to create

### MVP

- Personal profile

  - Sign in screen
  - PW recovery
  - Account settings screen
    - What settings do we need here?
    - Delete account
    - Update personal info
    - Profile pic
  - Main Screen

    - List of available achievements

      - Achievement template:

      ```
      {
        name: "",
        description: "",
        category: "",
        worth: 0,
        passed: false,
        saved: false,
        belief: 0,
        date: new Date(Date.now())
      }
      ```

    - List of completed achievements
    - Score tally
    - Ability to mark acheivement as complete

### Additional Features

- Custom URL for profile
- Create your own achievement
  - AI generated icon?
- Monitization?
  - premium currency for AI generation
  - Voluntary ads to earn currency
- AI generated achievements?

## Tasks

- Implement expo router: https://docs.expo.dev/router/introduction/
- Create profile view
  - Create design mock up for this page
- Create sign in view
  - Create design mock up for this page
- Implement a backend infrastructure (research this)
  - Laravel?
  - What is standard for expo apps?
  - What kind of DB makes sense?
