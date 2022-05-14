# form-one
Form in JS

--I. JavaScript constraint API--

The form uses JavaScript API to validate input as it is typed in. It cannot submit until the form is properly filled in. 

--II. Autocomplete Selection--

Country input uses autocomplete to generate a list of available selections. As text is imputed, the list is narrowed to match selection. 

The user must click on a country from the generated list in order to submit. 

If the user hits backspace after clicking a country from the list, the country input will clear.

--III. DOM Manipulation--

Event listeners register input and validity. 

--IV. Non-API error logic--

Custom input errors are introduced in order to meld with the custom autocomplete function of the country input. It uses event listeners attached to event.key actions.  

--V. HTML constraints--

HTML constraints are used to require non-blank input. 

