## Models

### City
- name:string
- country_code:string

## Rails Architecture

## Models
- Store data in database
- Process data

## Views
- Present data

## Helpers
- Help the views to present the data

## Controllers
- Coordinator between the models and views
- Accesses data, whether from the database through models, or from APIs
- Sets data in instance variables

## Routes
- Determine which controller and which of its action to run
- Maps URLs tp a certain controller#action

## Challenges

1. The API gives us temperatures in Kelvin. Convert it to Celcius.
2. Display the maximum temperature.
3. Create a view helper to format Celcius 24C.
4. Add humidity and pressure to your #show page too.
5. Use the dotenv gem to load in the open weather map API key as an environment variable.
