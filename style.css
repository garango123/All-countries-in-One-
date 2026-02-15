// script.js
const countries = {
  Kenya: { currency: "KES", continent: "Africa", population: "55M", flag: "🇰🇪" },
  "South Sudan": { currency: "SSP", continent: "Africa", population: "11M", flag: "🇸🇸" },
  USA: { currency: "USD", continent: "North America", population: "331M", flag: "🇺🇸" }
};

function searchCountry() {
  const name = document.getElementById("countryInput").value;
  const info = countries[name];
  if(info){
    document.getElementById("result").innerHTML = `
      <p>Currency: ${info.currency}</p>
      <p>Continent: ${info.continent}</p>
      <p>Population: ${info.population}</p>
      <p>Flag: ${info.flag}</p>
    `;
  } else {
    document.getElementById("result").innerHTML = "<p>Country not found!</p>";
  }
}

function toggleDark() {
  document.body.classList.toggle("dark-mode");
}