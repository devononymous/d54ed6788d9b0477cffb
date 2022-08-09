# d54ed6788d9b0477cffb
1. Sign up in https://api.nasa.gov/ to get an API key.
2. When the user opens the application, the user sees a form that contains one text input and a
submit button. Use " Enter Asteroid ID as a placeholder text in the text input form field. The
user also sees another button called Random Asteroid*
3. The submit button is disabled if text input is empty.
4. When the user enters an asteroid id in the input field and presses submit, make a call to
https://api.nasa.gov/neo/rest/v1/neo/((ENTER._ASTEROID ID_HEREI/?api_key=
HYOUR API KEY)
5. The user is taken to a screen that now displays the information about the asteroid. Display the
following information:
- name
- nasa_jpl_url
- is potentially_hazardous_asteroid
6. When the user clicks the Random Asteroid* button, make a call to
https://api.nasa.gov/neo/rest/v1/neo/browse?api_key=DEMO_KEY. Select RANDOM asteroid id.
Pass ID to https://api.nasa.gov/neo/rest/v1/neo/((ENTER_ASTEROID_ID_HERE))?api_key=
(YOUR _API_KEY))
7. The user is taken to a screen that now displays the information about the asteroid. Display the
following information:
- name
-nasa_ipl_url
- is_potentially_hazardous asteroid
8. Style application using https://material-ui.com/
9. Write Unit Tests using JEST
10. Expo should be used to run the application
https://api.nasa.gov/neo/rest/v1/neo/2000719/?api_key=zONCDBmTWh8d3ECnsEFpwUeqhoPVarrWDDLhTtTb

11. npm i @react-navigation/native @react-navigation/stack react-native-gesture-handler react-native-paper react-native-safe-area-context expo-updates @expo/vector-icons

12. run the app with expo start or yarn start and select w for web 
