# react native setup
install exo cli      **npm install -g expo-cli**
intsall expo go on you phone using playstore

create my app       **npx create-expo-app MyApp**
craete readme.md
then run npx expo sart

# ProDev Mobile App 0x00 – First Expo App

## Objective
Set up the first mobile application using Expo Router and understand the project structure.

## Scaffolding Steps
1. Navigated to the project directory.
2. Created a new Expo app using the Expo Router template.
3. Selected the Tabs navigation structure.
4. Installed dependencies successfully.

## Home Screen Modification
- Updated the default welcome text in `app/(tabs)/index.tsx`
- Changed text from "Welcome!" to "First App Created"

## Running the Application
- Started the development server using `npx expo start`
- Scanned the QR code using Expo Go
- Verified the app runs successfully on a physical device

## Reset Project Observation
After running `npm run reset-project`:
- Metro bundler cache was cleared
- Project state was refreshed
- The application rebuilt cleanly without errors

## Conclusion
The Expo Router project was successfully created, modified, tested, and reset.


when you run **npm run reset-project** in the termina you get:

Do you want to move existing files to /app-example instead of deleting them? (Y/n): y
📁 /app-example directory created.
➡️ /app moved to /app-example/app.
➡️ /components moved to /app-example/components.
➡️ /hooks moved to /app-example/hooks.
➡️ /constants moved to /app-example/constants.
➡️ /scripts moved to /app-example/scripts.

📁 New /app directory created.
📄 app/index.tsx created.
📄 app/_layout.tsx created.

✅ Project reset complete. Next steps:
1. Run `npx expo start` to start a development server.
2. Edit app/index.tsx to edit the main screen.
3. Delete the /app-example directory when you're done referencing it.