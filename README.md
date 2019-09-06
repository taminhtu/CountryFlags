# CountryFlags
Create a java application that displays a flag of a country and requests that the user identify its origin by selecting the corresponding country name from a list.

* How to get the list of countries
1. Country get by Locale.getISOCountries()

* Fetch image and display:
1. User can choose the list of country
2. Load flag images from local
3. If not exist, download flags from the website https://flagpedia.net and load from local
4. Swing app display the flag on change event of Jbox selection
