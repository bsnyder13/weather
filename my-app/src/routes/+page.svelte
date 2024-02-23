<h1>Forecast</h1>

<script>
    
    // const successCallback = (position) => {
    // console.log(position);
    // };  

    // const errorCallback = (error) => {
    // console.log(error);
    // };

    // navigator.geolocation.getCurrentPosition(successCallback, errorCallback);

    // console.log(latitude, longitude);

    const baseURL = "https://api.weather.gov/points/"

    let forecast = async() => {
        let res = await fetch(baseURL);
        console.log(res)

        let json = await res.json();
        console.log(json)
    }


</script>