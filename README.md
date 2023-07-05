Building an address form group using reactive form control in this project. 
The main idea is to implement custom validation. 

Validation Rules -
  1. when a foreign address is selected, the country dropdown should not select 'US' as the country.
  2. when a foreign address is selected, the states dropdown should input text
  3. when a foreign address is selected, the zip code should be non-required and not follow the US zip code validation ( 5 or 9-digit pattern)

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/angular-ivy-3wmluj)
