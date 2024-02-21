<h1>Forecast</h1>

<script>
    
    const successCallback = (position) => {
  console.log(position);
};

const errorCallback = (error) => {
  console.log(error);
};

navigator.geolocation.getCurrentPosition(successCallback, errorCallback);

    const baseURL = "https://api.weather.gov/points/"


</script>