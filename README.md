# Repro Steps
- `cd ./appshell` and run `npm i` and then `npm run build`
- `cd ../blazorpilet` and run `dotnet build` (youl'll get an error here)
- `cd ../.piral~/blazorpilet` and run `npm start`

#  Problem
- open `/pizzas`
- click on `Pizza Salami`
- The single PizzaPage view is shown with the pizza name taken from the url
- now click the `back to overview` link
- click on `Pizza Vegetaria`
- The single PizzaPage view is shown again, but the page still shows `Pizza salami` although the url says `/pizzas/vegetaria`