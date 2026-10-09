# EcoTrack — Personal Carbon Footprint Calculator

A self-contained responsive sustainability calculator built in HTML, CSS, and JavaScript. No dependencies, account, API keys, or server required.

## Run locally
Open `index.html` in a modern browser.

## Publish to GitHub Pages
1. Create a public GitHub repository named `ecotrack`.
2. Upload `index.html` and `README.md`.
3. In Settings → Pages, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
4. Wait for GitHub to publish the URL and open it to confirm that the calculator works.

## Calculation assumptions
- Gasoline car: 0.404 kg CO2/mile (illustrative)
- Flights: 0.16 kg CO2e/passenger-mile, 3,000 miles/round trip (illustrative)
- Electricity: 0.386 kg CO2/kWh (illustrative grid average)
- Natural gas: 5.3 kg CO2/therm (illustrative)
- Food: 3.3 / 2.5 / 1.7 / 1.4 tonnes CO2e/year for meat-heavy / mixed / vegetarian / vegan diets (illustrative diet averages)

This is an educational model, not a precise or location-specific carbon inventory. Emission factors should be checked against reputable sources before presenting the estimates as authoritative.

## Test checklist
- Change each slider and diet menu; results should update.
- Reset restores defaults.
- Download results creates a text file.
- Check on mobile-sized browser and desktop.
